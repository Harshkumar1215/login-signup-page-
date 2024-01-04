# login-signup-page-
Login and Sign Up page
<br>
(HTML and CSS)

login page -HTML  



    <title>Login Page</title>
    <link rel="stylesheet" href="login.css">
   

    <form action="">
    <div class="d1">
        <h3>LOGIN PAGE</h3>
        <img src="multimedia/image/7.jpg" alt="User Icon" class="img1"><br><br>
        
    <input  class="input1" type="text" id="userId" placeholder="Enter your user ID" required><br>
    <input class="input2" type="password" id="password" placeholder="Enter your password" required><br>
    <input class="sub" type="submit"><a href="* link page*"> <span>Skip</span></a>
    </div>

CSS of login page 
      body {
    background-image: url(multimedia/image/4.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
}

.d1 {
    background-color: rgba(205, 255, 211, 0.8);
    border-radius: 10px;
    padding: 20px;
    width: 400px;
    text-align: center;
    box-shadow: 0 4px 8px rgba(38, 19, 145, 0.1);
}

.img1 {
    border-radius: 50%;
    width: 100px;
    height: 100px;
    object-fit: cover;
}

.input1 {
    margin: 15px 0;
    padding: 10px;
    width: 100%;
    border-radius: 5px;
    border: 1px solid #ccc;
    box-sizing: border-box;
}

.input2 {
    margin: 15px 0;
    padding: 10px;
    width: 100%;
    border-radius: 5px;
    border: 1px solid #ccc;
    box-sizing: border-box;
}
.sub{
    background-color: #4CAF50;
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    border-radius: 5%;
    margin-right: 10%;

   
    
    

}

span {
    background-color: #4CAF50;
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    border-radius: 5%;
    margin-left: 10%;
    
   
}
      a{
    text-decoration: none;
    }


        
   
