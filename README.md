<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>Registration form</h1>
     <form action="">

         <div>
            <label for="fullname">Full Name:</label>
            <input type="text" name="fullname" id="fullname">
         </div>
         <br>
         <div>
            <label for="email">Email:</label>
            <input type="email" name="email" id="email">
         </div>
         <br>
         <div>
            <label for="password">Password:</label>
            <input type="password" name="password" id="password">
         </div>
         <br>
         <div>
            <label for="dob">Date of Birth:</label>
            <input type="date" name="email" id="email">
         </div>
         <br>
         <div>
            <label for="photo">Choose your photo:</label>
            <input type="file" name="photo" id="photo">
         </div>
         <br>
         <div>
            <label for="gender">Gender:</label>
            <input type="radio" name="gender" id="gender" value="male" checked>Male
            <input type="radio" name="gender" id="gender" value="female">Female
         </div>
         <br>
         <div>
            <label for="religion">Religion:</label>
            <input type="checkbox" name="cl" id="muslim" value="muslim">Muslim 
            <input type="checkbox" name="cl" id="hindu" value="hindu" checked>Hindu
         </div>
         <br>
         <div>
            <label for="department">Department:</label>
             <select name="department" id="">
                 <option value="cse">CSE</option>
                 <option value="eee" selected>EEE</option>
                 <option value="llb">LLB</option>
             </select>
         </div>
         <br>
         <div>
             <label for="">Message:</label><br>
             <textarea name="" id="" cols="33" rows="8"></textarea>
         </div>
         <br>
         <div>
             <input type="submit">
         </div>

     </form>
</body>
</html>
