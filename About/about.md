---
layout: default
title: About
---
# About page

This page tells you a little bit about me.
<!doctype html>
<html>
  <head>
    <meta charset="utf-8">
    <title>{{ page.title }}</title>
  </head>
  <body>
    {% include navigation.html %}
    {{ content }}
  </body>
  <h2>Czarna lista wynajmowania mieszkan.</h2>
  <style>
    #rcorners2 {
    border-radius: 5px;
    border: 1px solid #8AC007;
    padding: 20px; 
    width: 400px;
   
    resize: vertical;
        
}
</style>
<aside>
    <div class="ex4">
     <a href="~/fa fa-thumbs-up"></a><div id="vc-feelback-main" data-access-token="6d31f93bca9335598759477f73a050b0" data-display-type="4"style=" width: 300px;height: 100px;margin-left: -180px;margin-top: -40px"></div></a></div>
    
</aside>
<body>
    <p id="rcorners2">Odwiecznym problemem i mankamentem jest podnajmowanie komuś mieszkania.
                  Za zwyczaj przy zawieraniu umowy są lub raczej starają się zrobić jaknajlepsze
                  wrażenie na właścicielu.Jednak niekiedy w praktyce wygląda to całkiem inaczej:
                  nie płacą w terminie,dewastują co się da, aż w końcu dochodzi do wypowiedzenia
                  przez zniecierpliwionego właściciela i co w tedy?.
                  Dlatego też dobrze jest podać takiego delekwenta na "czarną listę,żeby uchronić
                  następną ofiarę podstępu!
                  Lista jest otwarta dla każdego,kto spotkał się z podobną sytuacją i chce przy tym
                  uchronić nastepną ofiarę.</p>
<div class="ex4">
     <a href="~/fa fa-thumbs-up"></a><div id="vc-feelback-main" data-access-token="6d31f93bca9335598759477f73a050b0" data-display-type="4"style=" width: 300px;height: 100px"></div></a></div>
<script>
     
(function() { 
var v = document.createElement('script'); v.async = true; 
v.src = "http://assets-prod.vicomi.com/vicomi.js"; 
var s = document.getElementsByTagName('script')[0]; s.parentNode.insertBefore(v, s); 
})(); 
</script>

@{
if (IsPost)
{ 
string companyname = Request["CompanyName"]; 
 
<p id="rcorners2"><br> 
 @companyname <br> 
 </p> 
}
else
{
<form method="post" action=""style="margin-top: -100px">
Company Name:<br> 
<p class="padding"><input type="text" name="CompanyName" value=""style="margin-top: -15px"><br></p>
<p id="demo"></p>
<input type="submit" value="Submit" class="submit">
</form> 
}
} 
   
<script>
function myFunction() {
    var c = document.createComment("My personal comments");
    document.body.appendChild(c);
    var x = document.getElementById("demo");
    x.innerHTML = "A comment was added to this document, but as you know, comments are invisible.";
}
</script> 
</body>
</html>