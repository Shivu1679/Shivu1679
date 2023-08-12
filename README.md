<!DOCTYPE html>
<html lang="en">
<head>
    <style>
         
body{
          background-image: url(https://images.unsplash.com/photo-1601564350184-9e93c13df688?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=870&q=80 ) ;
          background-repeat: no-repeat;
          background-size:cover ;
          background-position: center center;
          background-attachment: fixed;
          
 } 
        
body{
    font-family: Arial, sans-serif;
    background-color: #f2f2f2;
    margin: 0;
    padding: 0;
}
h1{
    
    text-align:center;
    size: 10px;
    color: black;
    font-style:italic ;
    position: absolute;
    top: 8px;
    left: 16px;
    font-size: 25px;
}

/* #container{ */
 /* background-image: url(https://images.unsplash.com/photo-1601564350184-9e93c13df688?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=870&q=80); */


nav {
    background-color: #007bff;
    color: #fff;
    padding: 10px;
}

nav ul {
    list-style-type: none;
    padding: 0;
    display: flex;
    justify-content: center;
    align-items: center;
}

nav li {
    margin: 0 15px;
}

nav a {
    color: #fff;
    text-decoration: none;
}

.container {
    background-color: #fff;
    padding: 20px;
    border-radius: 5px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    width: 400px;
    margin: auto;
    margin-top: 20px;
}

h1 {
    text-align: center;
    margin-bottom: 20px;
}

form {
    display: flex;
    flex-direction: column;
}

label {
    margin-bottom: 5px;
}

input, select, textarea {
    padding: 10px;
    margin-bottom: 10px;
    border: 1px solid #ccc;
    border-radius: 3px;
    font-size: 14px;
}

button {
    background-color: #007bff;
    color: #fff;
    border: none;
    padding: 10px 20px;
    border-radius: 3px;
    cursor: pointer;
    font-size: 14px;
    transition: background-color 0.3s;
}

button:hover {
    background-color: #0056b3;
}

    </style>
    <meta charset="UTF-8">
    <title>Go Play n Connect</title>
    <link rel="C:\Users\chauh\OneDrive\Desktop\VS Code (Yashvi)\logo.jpg" href="logo.jpg">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>User Profile</title>
</head>
<body>
    <H1>Go Play n Connect</H1>
    <nav>
        <ul>
            <li><a href="#create-account">Create Account</a></li>
            <li><a href="#sign-in">Sign In</a></li>
            <li><a href="#sign-up">Sign Up</a></li>
            <li><a href="#Sports"> Sports Category</a></li>
            <li><a href="#Location"> Location</a></li>
        </ul>
    </nav>
    
    <div class="container">
        <!-- <img src="https://images.unsplash.com/photo-1601564350184-9e93c13df688?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=870&q=80" alt="image of players" width="650" height="600"> -->
       
        <!-- <h2>Create Your Profile</h2> -->
       <div class="Parent">
           <div class="C1">
        <form action="#">
            <label for="fullname">Full Name:</label>
            <input type="text" id="fullname" name="fullname" required>
            
            <label for="age">Age:</label>
            <input type="integer" id="age" name="age" required>
            
            <label for="bio">Bio:</label>
            <textarea id="bio" name="bio" rows="4" required></textarea>
             </div>
             <div class="C2">
          
            <label for="sport">Preferred Sport:</label>
            <select id="sport" name="sport" required>
                <option value="soccer">Soccer</option>
                <option value="basketball">Basketball</option>
                <option value="tennis">Tennis</option>
                <option value="Kho-kho">Kho-kho</option>
                <option value="Badminton">Badminton</option>
                <option value="Volley ball">Volley Ball</option>
                <option value="Cricket">Cricket</option>
                <option value="Kabbadi">Kabbadi</option>
                <option value="Handball">Handball</option>
            </select>
        <br>
            <label for="skill">Skill Level:</label>
            <select name="skill" id="skill">
                <option value="Beginner">Beginner</option>
                <option value="Intermediate">Intermediate</option>
                <option value="Advanced">Advanced</option>
            </select>
<br>
            <label for="profile-picture">Profile Picture:</label>
            <input type="file" id="profile-picture" name="profile-picture">
         <br>   
            <label for="cover-photo">Cover Photo:</label>
            <input type="file" id="cover-photo" name="cover-photo">
            
            <button type="submit">Create Profile</button>
        </form>
    </div>
    </div>
    </div>
</body>
</html>

