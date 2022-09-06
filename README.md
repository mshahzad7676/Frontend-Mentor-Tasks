# Frontend-Mentor-Tasks
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://fonts.google.com/specimen/Montserrat">
    <link rel="stylesheet" href="https://fonts.google.com/specimen/Fraunces">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <title>Task 1</title>
<style>
body{

    background-color: gainsboro;
}

#container{
	
	background: rgba(255, 255, 255, 0.90);
	border-radius: 15px;
	overflow: hidden;
	margin: 5em auto;
	height: 400px;
	width: 450px;
	
}
.image {
  
  width: 225px;
  margin: auto;
  text-align: center;
  font-family: arial;
  height: 400px;
    float: left;

}

#container img {
    width: 100%;
    
    height: 100%;
}

#container .product-details p {
	font-family: 'Montserrat';
	font-size: 14px;
	color: #7d7d7d;
    margin: 20px;
   
	
}
#container .product-details h3{
    margin: 20px;
    font-weight: bold;
    font-size: 20px;

}
 .product-details h5 {
	font-family: 'Fraunces';
    font-size: 20px;
    color: #7d7d7d;
    margin-left: 20px;
}

.product-details {
    height: 400px;
    width: 225px;
    float: right;
}
.button{
    margin: 10px 20px;
    background-color: hsl(158, 36%, 37%) ;
    border: none;
    border-radius: 8px;
    height: 33px;
    width: 162px;
    color: white;
}
.button{
    margin-top: 30px;
}

</style>
</head>
<body>
    
   <div id="container">
       <div class="image">
            <img src="desktop.jpg">

       </div>

            <div class="product-details">
                <h5>PERFUME</h5>
                <h3>Gasbrielle Essence Eau De Parfum</h3>
                
                <p class="information">
                    A floral,solar and voluptuous interpretation composed by Olivier Polge,
                    Perfumer-Creator for the House of CHANEL.
                </p>
                    
                <div id="price">
                 <p style=" color: hsl(158, 36%, 37%); font-size: x-large; font-weight: bold;margin-top: 30px;">$149.99
                    <del style=" color: #7d7d7d; margin-left: 10px; font-size: small;">$169.99</del></p>
              
                </div>

                
                    <button class="button button1"><i class="fa fa-shopping-cart" style="font-size:20px;color:white; padding: 0px 8px;"></i>Add to Cart</button>

                
            </div>
 
</body>
</html>
