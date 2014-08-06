---
title: Order form
heading: "Order form"
layout: subnav
nav: catalog
group: catalog
---


<form action="http://www.fishproducts.com/cgi-bin/formmail/FormMail.pl" method="POST" name="orderform" enctype="x-www-form-urlencoded">
  <center>
    <p><br>
      <b><font size="+1">Note: We have been having trouble with our form being 
      received on our end. We are working on the problem. <br>
      If you really want this order to get to us, do a copy/paste of this entire 
      form into your email program, and then fill out the form and email it to 
      us at this <a href="mailto:FishProductsInfo@gmail.com">LINK</a></font></b><font size="+1"><a href="mailto:form@fishproducts.com">.</a>. 
      </font> </p>
      
    <p><br>
      If you fill in the form on this page and then click <b>Submit</b>, it will 
      probably get to us. We will Email you a confirmation shortly after we get 
      it. To Email us your order, do a "select all" and then paste the 
      blank form into a standard Email message. IF YOU ARE USING AOL, via EMAIL 
      IS THE BEST WAY. Fill in the various blanks on that piece of Email and then 
      send it off. <br>
      What we don't want you to do is send us this form by Email, then call us 
      up and submit another order, or start calling us for a confirmation of the 
      order. If you order by Email, let's keep it to Email. It is confusing enough 
      around here without duplicate orders on the phone, Email and snail mail 
      all coming in from the same guy.<br>
      Another way is print out the <a href="{{ "/files/orderform.pdf" | prepend: site.baseurl }}" target="_blank">PDF 
      form</a>, then mail in your order. Thanks!<br>
      <input type="hidden" name="subject" value="FISH Order">
      <input type="hidden" name="redirect" value="{{ "/catalog/orderconfirm" | prepend: site.baseurl }}">
    </p>
  </center>
  <p> 
    </p><center>
      <b>Email address: </b> 
      <input name="email" type="text" size="44">
      <br>
      <b>Name:</b> 
      <input name="Name" type="text" size="48">
      <br>
      <b>Street Address:</b> 
      <input name="Street" type="text" size="53">
      <br>
      <b>City, State, Zip:</b> 
      <input name="CityStateZip" type="text" size="56">
      <br>
      <b>Phone, Day:</b> 
      <input name="PhoneDay" type="text" size="30">
      <br>
      <b>Phone, Eve:</b> 
      <input name="PhoneEve" type="text" size="30">
      <br>
      <b>Todays Date:</b> 
      <input name="Date" type="text" size="30">
      <br>
      <b>Date Needed:</b> 
      <input name="DateNeeded" type="text" size="30">
      <br>
      <br>
      <b>CRITICAL----&gt; Absolute Drop Dead Date:</b> 
      <input name="DropDead" type="text" size="30">
      <b>(Very Important) </b><br>
      <b>Comments or Billing Address for Credit Card:</b> 
      <textarea name="Comments" rows="6" cols="60"></textarea>
    </center>
  <p></p>

<p></p><center>
    <table border="1" width="563" cellspacing="2" cellpadding="0" height="465">
      <tbody><tr> 
        <th width="10%" height="16">QTY</th>
        <th width="10%" height="16">SIZE</th>
        <th width="13%" height="16">COLOR</th>
        <th width="13%" height="16">CLR #2</th>
        <th width="29%" height="16">ITEM</th>
        <th width="12%" height="16">EACH</th>
        <th width="13%" height="16">TOTAL</th>
      </tr>
      <tr> 
        <td width="10%" height="29"><input name="Qty1" size="5" type="text"></td>
        <td width="10%" height="29"><input name="Size1" size="5" type="text"></td>
        <td width="13%" height="29"><input name="Color1" size="10" type="text"></td>
        <td width="13%" height="29"><input name="Color11" size="10" type="text"></td>
        <td width="29%" height="29"><input name="Item1" size="25" type="text"></td>
        <td width="12%" height="29"><input name="Cost1" size="8" type="text"></td>
        <td width="13%" height="29"><input name="Total1" size="10" type="text"></td>
      </tr>
      <tr> 
        <td width="10%" height="29"><input name="Qty2" size="5" type="text"></td>
        <td width="10%" height="29"><input name="Size2" size="5" type="text"></td>
        <td width="13%" height="29"><input name="Color2" size="10" type="text"></td>
        <td width="13%" height="29"><input name="Color22" size="10" type="text"></td>
        <td width="29%" height="29"><input name="Item2" size="25" type="text"></td>
        <td width="12%" height="29"><input name="Cost2" size="8" type="text"></td>
        <td width="13%" height="29"><input name="Total2" size="10" type="text"></td>
      </tr>
      <tr> 
        <td width="10%" height="29"><input name="Qty3" size="5" type="text"></td>
        <td width="10%" height="29"><input name="Size3" size="5" type="text"></td>
        <td width="13%" height="29"><input name="Color3" size="10" type="text"></td>
        <td width="13%" height="29"><input name="Color33" size="10" type="text"></td>
        <td width="29%" height="29"><input name="Item3" size="25" type="text"></td>
        <td width="12%" height="29"><input name="Cost3" size="8" type="text"></td>
        <td width="13%" height="29"><input name="Total3" size="10" type="text"></td>
      </tr>
      <tr> 
        <td width="10%" height="29"><input name="Qty4" size="5" type="text"></td>
        <td width="10%" height="29"><input name="Size4" size="5" type="text"></td>
        <td width="13%" height="29"><input name="Color4" size="10" type="text"></td>
        <td width="13%" height="29"><input name="Color44" size="10" type="text"></td>
        <td width="29%" height="29"><input name="Item4" size="25" type="text"></td>
        <td width="12%" height="29"><input name="Cost4" size="8" type="text"></td>
        <td width="13%" height="29"><input name="Total4" size="10" type="text"></td>
      </tr>
      <tr> 
        <td width="10%" height="29"><input name="Qty5" size="5" type="text"></td>
        <td width="10%" height="29"><input name="Size5" size="5" type="text"></td>
        <td width="13%" height="29"><input name="Color5" size="10" type="text"></td>
        <td width="13%" height="29"><input name="Color55" size="10" type="text"></td>
        <td width="29%" height="29"><input name="Item5" size="25" type="text"></td>
        <td width="12%" height="29"><input name="Cost5" size="8" type="text"></td>
        <td width="13%" height="29"><input name="Total5" size="10" type="text"></td>
      </tr>
      <tr> 
        <td height="29"><input name="Qty6" type="text" id="Qty6" size="5"></td>
        <td height="29"><input name="Size6" type="text" id="Size6" size="5"></td>
        <td height="29"><input name="Color6" type="text" id="Color6" size="10"></td>
        <td height="29"><input name="Color66" type="text" id="Color66" size="10"></td>
        <td height="29"><input name="Item6" type="text" id="Item6" size="25"></td>
        <td height="29"><input name="Cost6" type="text" id="Cost6" size="8"></td>
        <td height="29"><input name="Total6" type="text" id="Total6" size="10"></td>
      </tr>
      <tr> 
        <td height="29"><input name="Qty7" type="text" id="Qty7" size="5"></td>
        <td height="29"><input name="Size7" type="text" id="Size7" size="5"></td>
        <td height="29"><input name="Color7" type="text" id="Color7" size="10"></td>
        <td height="29"><input name="Color77" type="text" id="Color77" size="10"></td>
        <td height="29"><input name="Item7" type="text" id="Item7" size="25"></td>
        <td height="29"><input name="Cost7" type="text" id="Cost7" size="8"></td>
        <td height="29"><input name="Total7" type="text" id="Total7" size="10"></td>
      </tr>
      <tr> 
        <td height="29"><input name="Qty8" type="text" id="Qty8" size="5"></td>
        <td height="29"><input name="Size8" type="text" id="Size8" size="5"></td>
        <td height="29"><input name="Color8" type="text" id="Color8" size="10"></td>
        <td height="29"><input name="Color88" type="text" id="Color88" size="10"></td>
        <td height="29"><input name="Item8" type="text" id="Item8" size="25"></td>
        <td height="29"><input name="Cost8" type="text" id="Cost8" size="8"></td>
        <td height="29"><input name="Total8" type="text" id="Total8" size="10"></td>
      </tr>
      <tr> 
        <td rowspan="6" colspan="4" valign="TOP"> <p><strong>Mail:</strong><br>
            FISH Products<br>
            HC1 Box 696<br>
            Joshua Tree, Ca. 92252<br>
            <b>Email </b>us: <a href="mailto:FishProductsInfo@gmail.com">FishProductsInfo@gmail.com</a><br>
            <b>Call</b> us:<font face="Arial, Helvetica, sans-serif">(760) 394.6665</font> 
            to leave a message </p>
          <p><b><font size="+1">Shipping Rates:<br>
            Calif:</font></b><font size="+1"> </font><font color="#000000" size="+1">$7.00 minimum</font><font size="+1">, or 6% of order total to 
            a $28.00 Maximum. Ledges and MaxiPads, So. Cal add $6, Nor. Cal add 
            $9</font><font size="+1"><br>
            <b>All other 47 States:</b> </font><font color="#000000" size="+1">$10.00 
            minimum,</font><font size="+1"> or 10% of total order to a maximum 
            of $34.00. Ledges and MaxiPads, Midwest add $9, East Coast add $14<br>
            <b>AK and Hawaii:</b> Tons... email us.</font> </p></td>
        <td colspan="2" height="29">MERCHANDISE TOTAL</td>
        <td width="13%" height="29"><input name="MerchTotal" size="10" type="text"></td>
      </tr>
      <tr> 
        <td colspan="2" height="29">CA 8% SALES TAX</td>
        <td width="13%" height="29"><input name="Tax" size="10" type="text"></td>
      </tr>
      <tr> 
        <td colspan="2" height="29">SUB TOTAL</td>
        <td width="13%" height="29"><input name="Subtotal" size="10" type="text"></td>
      </tr>
      <tr> 
        <td colspan="2" height="38">SHIPPING CHARGES (see chart)<br> <b>Minimum 
          charge in Calif: $7.00<br>
          Minimum Charge all other states: $10.00</b></td>
        <td width="13%" height="38"><input name="UPS" size="10" type="text"></td>
      </tr>
      <tr> 
        <td colspan="2" height="29">Insurance charges for Cam Repair shipping</td>
        <td width="13%" height="29"><input name="COD" size="10" type="text"></td>
      </tr>
      <tr> 
        <td colspan="2" height="29"><p><b><i>If you need room for more items, 
            add them into the comments text block above or just email us your 
            order.</i></b></p>
          <p><b>GRAND TOTAL:<br>
            <br>
            </b></p></td>
        <td width="13%" height="29"><input name="GrandTotal" size="10" type="text"></td>
      </tr>
    </tbody></table>
    <br>
  </center>
  <center>If you fill in the card info below, we will process
and charge your card inhouse and usually after we are sure<br>
of the totals, your math, and have adjusted your order for items
that are possibly out of stock. <br>
If you use the PayPal link below (you do <b>NOT</b> need a paypal
account to use this link) your card will be charged immediately<br>
and securely processed by PayPal. Your choice. If you choose to
use the PayPal link, and your math is off or something is out
of stock,<br>
we will refund or adjust your payment and then either charge you
more, or refund the balance due via PayPal. If you <br>
want any refunds to go back to the credit card used for the purchase,
I would suggest not using the PayPal option.<table width="550" border="0" cellspacing="2" cellpadding="0" height="161">
  <tbody><tr>
    <td colspan="2" height="16"><strong>Credit Card Payments:</strong></td>
     
  </tr>
  <tr>
    <td colspan="2" height="29">Name on Card <input name="NameOnCard" size="71" type="text"></td>
     
  </tr>
  <tr>
    <td width="42%" height="29">Expiration Date <input name="Expires" size="21" type="text"></td> 
    <td width="58%" height="29"><input type="radio" name="payment_method" value="Visa" checked="1">Visa <input type="radio" name="payment_method" value="Mastercard">Mastercard</td> 
  </tr>
  <tr>
    <td colspan="2" height="46">Card Number 
          <input name="cardnumber" type="text" id="cardnumber" size="12" maxlength="4">
          <input name="cardnumber" type="text" id="cardnumber" size="12" maxlength="4">
          <input name="cardnumber" type="text" id="cardnumber" size="12" maxlength="4">
          <input name="cardnumber" type="text" id="cardnumber" size="12" maxlength="4">
          <br>
      3 digit number on the back of the card: 
          <input name="security code" type="text" size="12" maxlength="3"></td>
     
  </tr>
  <tr>
    <td colspan="2" align="CENTER" height="28"><strong>SHOP EARLY,
      SHOP OFTEN<br>
      SHOP HEAVY</strong></td>
     
  </tr>
</tbody></table>We're not giant SPAM kings or anything like that, but
if you would like to be informed of specials, updates, quizzes,
and random wierdness, click the box to get on our mailing list.<br>
<input type="checkbox" name="SpamOk" value="checkbox" checked="1">
SPAM ... or ... <input type="checkbox" name="NoSpam" value="checkbox">
No SPAM for me</center><p></p>

<p></p><center><font color="#00ff00"><input name="Submit" type="submit" value="Submit the Order"><input name="name" type="reset" value="Reset form"><br>
      </font><b><i><font color="#000000" size="+1">PRESS *SUBMIT* ONLY ONCE!!! 
      If your order form was sent to us (hopefully!) you will be taken to a confirmation 
      page after pressing submit. Use your "BACK" button to return to 
      our site. We will also confirm you again shortly via email. If you do not 
      get an email confirm from a live human within a day or two, please contact 
      us! THANKS!</font></i></b> 
    </center><p></p>

<p></p><center><a href="{{ "/pics/visa.gif" | prepend: site.baseurl }}"><img src="{{ "/pics/visa.gif" | prepend: site.baseurl }}" align="BOTTOM" hspace="10" width="60" height="38" naturalsizeflag="3" name="visa.gif" border="0"></a><a href="{{ "/pics/mastercard.gif" | prepend: site.baseurl }}"><img src="{{ "/pics/mastercard.gif" | prepend: site.baseurl }}" align="BOTTOM" hspace="10" width="60" height="38" naturalsizeflag="3" name="mastercard.gif" border="0"></a><br>
<font size="+1">If you want to pay via<b> PayPal,</b> simply get
your order total and then click on the <b>PayPal</b> button below
the sample page<br>
      to be taken directly to their secure site. <b>Be sure to hit the submit 
      button above so we know what you have ordered.</b> <br>
The <b>PayPal</b> button just lands your cash into our account.
It does not give us any order info.<br>
Here is a sample of what the PayPal page will look like after
you click the button:<br>
<img src="{{ "/pics/paypal_image.jpg" | prepend: site.baseurl }}" width="700" height="524" align="BOTTOM" border="2" naturalsizeflag="3"></font></center><p></p>

<p></p><center><b><font size="+1">To be taken to the PayPal site right
now to finish your<br>
transaction, click the PayPal button:</font></b></center><p></p>

</form>
<form action="https://www.paypal.com/cgi-bin/webscr" method="POST" enctype="x-www-form-urlencoded" name="paypalform">

<p></p><center><input type="hidden" name="cmd" value="_xclick"> <input type="hidden" name="business" value="PayPal@FishProducts.com">
<input type="hidden" name="item_name" value="FISH Products Order Total">
<input type="hidden" name="no_shipping" value="1"> <input type="hidden" name="return" value="{{ site.baseurl }}"> <input type="hidden" name="cn" value="Special Instructions (optional"> <input type="hidden" name="no_note" value="1"> <input type="hidden" name="currency_code" value="USD"> <input src="{{ "/pics/x-click-but6.gif" | prepend: site.baseurl }}" type="image" border="0" name="submit" alt="Make payments with PayPal - it&#39;s fast, free and secure!" align="BOTTOM">
  </center>
  <p>&nbsp;
</p></form>



