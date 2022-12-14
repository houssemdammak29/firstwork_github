body{
    background-color: #1B263B;
}
.buy {
  display: inline-block;
    margin :50px;
    background-color:#37425B;
    margin-top: 0%;
    margin-bottom: 0%;
    height: 100%;
    width: 62%;
    margin-left: 8%;


}
h1{
    text-decoration: underline;
    color:rgb(131, 135, 198);
}
.buy1{
    font-size: x-large;
    font-family:arial;
    color: white    ;

}

.titre {

display: inline-block;
color: white;
padding-left: 20px;
}
    .button {
      background-color: #1B263B; color: black;
      border: none;
      color: white;
      padding: 15px 32px;
      text-align: center;
      text-decoration: none;
      display: inline-block;
      font-size: 16px;
      margin: 4px 2px;
      cursor: pointer;
    }
    #myVideo {
      position: fixed;
      right: 0;
      bottom: 0;
      min-width: 100%; 
      min-height: 100%;
      z-index: -1;
      object-fit: cover;
    }

<html>
    <head>
   <title>buying form</title>
   <link rel="stylesheet" href="buying-form.css">
    </head>
<body>
    <body>
        <video autoplay muted loop id="myVideo">
            <source src="background.mp4" type="video/mp4">

          </video>
    <div class="titre"><h2>Festicket.com</h2></div>


    <div class="buy">
         <center>
        <h1> Fill The Form And Get Ready To The Fun !</h1> 
    <form  method="post">

                <table cellspacing="40"   class="buy1" >
                    <tr>
                        <td>Name :</td>
                        <td><input type="texts" placeholder ="Name"></td>
                    </tr>
                    <tr>
                        <td>Family Name :</td>
                        <td><input type="text" placeholder="Family Name"></td>
                    </tr>
                    <tr>
                        <td>Date of birth :</td>
                        <td><input type="date"></td>
                    </tr>
                    <tr>
                        <td>Mail :</td>
                        <td><input type="email" placeholder="Mail"></td>
                    </tr>
                    <tr>
                        <tr>
                            <td>Paiment:</td>
                            <td><div><input type="radio" name="Paiment" id="mc"><label for="mc" >master card</label></div>
                            <div><input type="radio" name="Paiment" id="v"><label for="v" >visa </label></div></td>
                         </tr>
                <tr>
                    <td></td>
                </tr>
                <td>
                    <input type="submit"  class="button"  value="submit">

                </td>


                </table>


       </form> 
    </center> 

    </div>

</body>

    </html>
