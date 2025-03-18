# web-development-wk2
its week 2
<!DOCTYPE html>


<html>
    
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        HTMl Assignments.
        <h4> order list</h4>

    </head>
    <body>
        <h2>html lists</h2>
        <h3> computer list types<h3>
           <ol type="i">
            <li> Dell </li>
            <li>    hp </li>
               <li> macbook</li>
               <li> Asus</li>
               <li></li>

            </li>

           </ol>
        <h1> images</h1>
        <a href="https://www.pexels.com/"> </a>
        <img src ="https://www.pexels.com/photo/black-bentley-continental-car-17338554/"  alt="image of the GOAT of cars" width="250" height="350"> 
      <h1> Tables</h1>
      <style>
        table, th, td{
            border:1px solid black;
        }
    </style>

      <table style = "widith:100%"> 
        <thread> 
            <tr>
                <th> Name </th>
                <th> Address </th>
                <th> Mobile</th>
                <th>Emails</th>

            </tr>
            <tr>
            <td>John Modzale</td>
            <td>45 parklands</td>
            <td>0110203450</td>
            <td>John@gmail.com<td>
            
            </tr>
            <tr>
                <td>Goma gomora</td>
                <td>100 sportman avenue</td>
                <td> 07383949475</td>
                    <td>ggomo@gmail.com</td>
                
            </tr>
            <tr>
                <td>Kaka Sudisha</td>
                <td>Goldman street</td>
                <td> 0895967949</td>
                <td>kk23sudi@gmail.com</td>
               
            </tr>
            <tr>
                <td>Mohamed Ali</td>
                <td>jetman clause</td>
                <td>0384859593</td>
                <td>alimoha@gmail.com</td>

            </tr>
            <tr>
                <td>Fatuma Abdi</td>
                <td>south clause</td>
                <td>0110903034</td>
                <td>abdifatuma@gmail.com</td>

            </tr>


        </thread>
      </table>
        <h1>Forms</h1>

        <input type="text" name= "fname" placeholder="Enter your first name"><br>
        <input type="text"name="lname" placeholder="Enter your last name"><br>
        <input type= "password" name="password" placeholder="Enter password" minlength="8" maxlenght="10"><br><br>
        <p> which languages would you like to learn more about<p>
        <input type= "radio" id="django"  name="fav_language" value="django">
        <label for="django" > django</label><br>
        <input type= "radio" id="HTML"  name="fav_language" value="HTML">
        <label for="HTML" > HTML</label><br>
        <input type= "radio" id="java"  name="fav_language" value="java">
        <label for="java" > java</label><br>
        <input type= "radio" id="php"  name="fav_language" value="php">
        <label for="php" > php</label><br>

       <p1> which programming languages do you know<p1>
        <input type= "checkbox" id="skill 1"  name="skill 1" value="python">
        <label for="skill 1" >I know python</label> <br>
        <input type= "checkbox" id="skill 2"  name="skill 2" value="react">
        <label for="skill 2" > I know react</label><br>
        <input type= "checkbox" id="skill 3"  name="skill 3" value="C programming">
        <label for="skill 3" > I know C programming</label><br>
        <input type= "checkbox" id="skill 4"  name="skill 4" value="php">
        <label for="skill 4" > I know php</label><br>
        <input type="submit" value="submit">
    </body>
</html>
