<html>
    <head>
        <title>Payment form</title>
    </head>
    <body style="border:solid 5px">
        <form>
            <h1 style="text-align:center"><u>Payment form</u></h1><hr>
            
             Required information as follows *
            <hr>
            <h2><u>Contact information</u></h2>
            <p>Name: *<input type="text" name="name" required></p> 
            <p>
                    <legend>Gender: *</legend>
                    <fieldset>
                Male <input type="radio" name="Gender" id="Male" required>
                Female <input type="radio" name="Gender" id="Female" required>
                Other <input type="radio" name="Gender" id="Other" required>
                 </fieldset>     
                </p>
                <p>Address:<textarea name="Address" id="Address" rows="10" col="10"></textarea></p>
           <p>Email *: <input type="email" name="Email" id="Email" required></p>
           <p>Pincode *: <input type="number" name="Pincode" id="Pincode" required></p>
           <hr>
           <h2><u>Payment Information</u></h2>
           <p>Card Type: *
            <select name="card_type" id="card_type" required>
               <option value="">--select a card type--</option>
               <option value="Visa">Visa</option>
               <option value="Rupay">Rupay</option>
               <option value="Master card">Master card</option>
            </select>
           </p>
           <p>
            Card Number: *<input type="number" name="cardNumber" id="cardNumber" required>
           </p>
           <p>
                Expiration Date: *<input type="date" name="exp_Date" id="exp_date" required>
           </p>
           <p>
             CVV *<input type="password" name="cvv" id="cvv" required>
           </p>
           <input type="submit" value="Pay Now">
        </form>
    </body>
</html>
