# shopsite

#html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="shopstyle.css">
    <title>Register</title>
</head>
<body>
    <div class = "header">
       <div class = "wrap"> 
         <h1 class = "site-title">Webshop</h1>
         <div class = "navigation">
            <ul>
                <li><a href="#">Главная</a></li>
                <li><a href="#">Кухня</a></li>
                <li><a href="#">Спальня</a></li>
                 <li><a href="#">Гостинная</a></li>
         </ul>
         </div>
       </div>    
    </div>
    <div class = "main">
        <div class = "wrap">
            <div class = "goods-min-cart">
                <h3>Раскладной диван</h3>
                <img src = "c:\Users\jeonm\Downloads\divan.jpeg" alt = ""> 
                <p class = "cost">14000 p.</p>
                <button class = "add-to-card">Купить</button>
            </div> 
        </div> 
    </div>
     <div class = "footer">
        <div class = "wrap">
        Webshop
       </div>
     <div> 
</body>
</html>

css

html, body, div, span, applet, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
a, abbr, acronym, address, big, cite, code,
del, dfn, em, img, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var,
b, u, i, center,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, embed, 
figure, figcaption, footer, header, hgroup, 
menu, nav, output, ruby, section, summary,
time, mark, audio, video {
	margin: 0;
	padding: 0;
	border: 0;
	font-size: 230%;
	font: inherit;
	vertical-align: baseline;
}
article, aside, details, figcaption, figure, 
footer, header, hgroup, menu, nav, section {
	display: block;
}
body {
	line-height: 1;
}
ol, ul {
	list-style: none;
}
blockquote, q {
	quotes: none;
}
blockquote:before, blockquote:after,
q:before, q:after {
	content: '';
	content: none;
}
table {
	border-collapse: collapse;
	border-spacing: 0;
}

.header
{
    
    width:100%;
    min-height: 80px;
    background-color: rgb(255, 202, 88);
    color:#fff;
    display:flex;
    justify-content: space-between;
    align-items: center;
    z-index: 99;

}

.wrap {
    max-width: 3000px;
    margin: 0 auto;
       }
.main{
    background: rgb(104, 104, 97);
    color: #fff;
}

.footer {
    min-height: 200 px;
    background: rgb(180, 171, 171);
    color: #fff;
    padding: 20 px;
}

.goods-min-cart{
    width:25%;
    background: rgb(104, 104, 97);
    margin:1%;
    text-align: center;
    font-size:1.3em;
    
}

.goods-min-cart img {
   width: 90%;
}

.site-title{
    font-size:2em;
    color:#fff;
    user-select:none;
    display: table;
    margin: 0 auto;
    width: 1200px;
    text-decoration: none;
}  
 .add-to-card{
    background-color:  rgb(231, 187, 92);
    color:rgb(255, 255, 255);
    display:block;
    width:100px;
    text-align: center;
    font-family: Arial, Helvetica, sans-serif;
    font-size: 14px;
    padding: 8px 16px;
    margin: 20px auto;
    text-decoration: none;
 }
 .navigation ul {
    list-style: none;
    padding: 0;
    margin: 0;
    position:fixed;
    
    }
    
    .navigation ul li {
    display: inline;
    margin-right: 100px;
    }
    
    .navigation ul li a {
    color: #fff;
    }
