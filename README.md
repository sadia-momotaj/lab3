* {
  font-family: Arial;
}
body {
  color: blue;
  background-color: #E6E6FA;
  border: 1px solid black;
}
h1 {
  color: #E6E6FA;
  background-color: #191970;
  font-family: Times New Roman;
  border: 3px dashed red;
}
h2 {
  border: 3px dashed blue;
}
p {
  color: red;
}
.classforContact{
  color:  #291970;
}
table {
  border-collapse: collapse;
  border: 2px solid red;
  letter-spacing: 1px;
  font-size: 0.8rem;
}
td, th {
  color: black;
  border-collapse: collapse;
  border: 2px solid red;
  padding: 10px 20px;
}
th {
  background-color: #FFCCFF;
}
td {
  text-align: center;
}
tr:nth-child(even) td {
  background-color: #291970;
}
#p1 {
  background-color: blue;
}


<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>My Contact page</title>
    <link rel="stylesheet" href="styles/Externalstylesheet.css">
  </head>
  <body>
    <h1 align="center">Contact Details</h1>

    <p class="classforContact">Phone : <a href="+44444">+4444</a></p>
    <p class="classforContact">Our Location : <a href="https://www.google.com.my/maps">Malaysia, Kuala lumpur</a></p>
    <p >Email:<a href="mailto:m.bluth@example.com">m.bluth@example.com</a></p>
    <P>Thank you for contact us!!!</p>
<br/>

<a href="index.html">Home</a>
  </body>
</html>


<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>CSS test page</title>
     <link rel="stylesheet" href="styles/Externalstylesheet.css">
     <style>
     input:invalid {
       border: 2px dashed red;
     }

     input:valid {
       border: 2px solid black;
     }
     textarea:invalid {
       border: 2px dashed red;
     }

     textarea:valid {
       border: 2px solid black;
     }
     </style>
  </head>
  <body>
    <h1 align="center">Online Market</h1>

    <a href="#">Home</a></li>
    <a href="Contact.html">Contact</a>
<h2>New products Details</h2>

    <table >
      <tr >
        <th rowspan="4">Products</th>

      </tr>
      <tr>
        <th style="color:red;">Name</th>
    <td>x1</td>
      <td>x2</td>
        <td>x3</td>
          <td>x4</td>
      </tr>
      <tr>
            <th>Price</th>
      <td id="p1">3.00</td>
        <td >5.00</td>
  <td >7.00</td>
    <td >9.00</td>
      </tr>
      <tr>
      <th>Quantity</th>
      <td>5</td>
        <td>6</td>
        <td>12</td>
        <td>16</td>
      </tr>
    </table>
    <p>To order product online, please submit form below</p>
    <form>

      <fieldset >
      <label >Name :</label>
      <input  type="text" maxlength="4" required><br/><br/>
      <label >Addres:</label><br/>
      <textarea cols="40" rows="4" required></textarea><br/><br/>
      <label >Email:</label>
      <input type="email" id="email" name="email" multiple required><br/><br/>
      <label >Phone number: +60 </label>
      <input type="number"  maxlength="6" required><br/><br/>




      <select id="simple" name="simple" required>
        <option selected >Product</option>
        <option>X1</option>
        <option>X2</option>
        <option>X3</option>
        <option>X4</option>
      </select><br/><br/>
      <label >Quantity:</label>
      <input type="number"  maxlength="6" required><br/><br/>
      <button type="submit">Submit</button>
      <button type="reset">Reset</button>
    </fieldset >

    </form>
      </body>
    </html>
