# Recipe
Copy code
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Recipe Ingredients</title>

<style>
body{
    font-family: Arial, sans-serif;
    background: linear-gradient(120deg,#ffecd2,#fcb69f);
    display:flex;
    justify-content:center;
    align-items:center;
    height:100vh;
}

.recipe-card{
    background:white;
    width:320px;
    padding:25px;
    border-radius:15px;
    box-shadow:0 10px 25px rgba(0,0,0,0.2);
}

.recipe-card h2{
    text-align:center;
    color:#ff6b6b;
    margin-bottom:20px;
}

.ingredients{
    list-style:none;
    padding:0;
}

.ingredients li{
    background:#fff4f4;
    margin:8px 0;
    padding:10px;
    border-radius:8px;
    display:flex;
    align-items:center;
    transition:0.3s;
}

.ingredients li:hover{
    background:#ffe3e3;
    transform:scale(1.03);
}

.ingredients input{
    margin-right:10px;
    accent-color:#ff6b6b;
}

.footer{
    text-align:center;
    margin-top:15px;
    font-size:12px;
    color:#888;
}
</style>

</head>
<body>

<div class="recipe-card">
<h2>🍝 Pasta Ingredients</h2>

<ul class="ingredients">
<li><input type="checkbox"> 200g Pasta</li>
<li><input type="checkbox"> 2 tbsp Olive Oil</li>
<li><input type="checkbox"> 3 Garlic Cloves</li>
<li><input type="checkbox"> 1 Cup Tomato Sauce</li>
<li><input type="checkbox"> 1 tsp Salt</li>
<li><input type="checkbox"> 1/2 tsp Black Pepper</li>
<li><input type="checkbox"> Parmesan Cheese</li>
</ul>

<div class="footer">✔ Check items while cooking</div>

</div>

</body>
</html>
