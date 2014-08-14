---
title: Order form
heading: "Order form"
layout: subnav
nav: catalog
group: catalog
---


<form action="http://www.fishproducts.com/cgi-bin/formmail/FormMail.pl" method="POST" name="orderform" enctype="x-www-form-urlencoded" class="form-horizontal">
  <p class="lead">Note: We have been having trouble with our form being 
    received on our end. We are working on the problem.
  </p>
  <p class="lead">
    If you really want this order to get to us, do a copy/paste of this entire 
    form into your email program, and then fill out the form and email it to 
    us at this <a href="mailto:FishProductsInfo@gmail.com">LINK</a>.
  </p>
    
  <p>
    If you fill in the form on this page and then click <b>Submit</b>, it will 
    probably get to us. We will Email you a confirmation shortly after we get 
    it. To Email us your order, do a "select all" and then paste the 
    blank form into a standard Email message. IF YOU ARE USING AOL, via EMAIL 
    IS THE BEST WAY. Fill in the various blanks on that piece of Email and then 
    send it off.
  </p>
  <p>
    What we don't want you to do is send us this form by Email, then call us 
    up and submit another order, or start calling us for a confirmation of the 
    order. If you order by Email, let's keep it to Email. It is confusing enough 
    around here without duplicate orders on the phone, Email and snail mail 
    all coming in from the same guy.
  </p>
  <p>
    Another way is print out the <a href="{{ "/files/orderform.pdf" | prepend: site.baseurl }}" target="_blank">PDF 
    form</a>, then mail in your order. Thanks!
    <input type="hidden" name="subject" value="FISH Order">
    <input type="hidden" name="redirect" value="{{ "/catalog/orderconfirm" | prepend: site.baseurl }}">
  </p>

  <hr />

  <div class="form-group">
    <label class="col-sm-4 control-label">Email address:</label>
    <div class="col-sm-8">
      <input name="email" type="text" class="form-control">
    </div>
  </div>
  <div class="form-group">
    <label class="col-sm-4 control-label">Name:</label>
    <div class="col-sm-8">
      <input name="Name" type="text" class="form-control">
    </div>
  </div>
  <div class="form-group">
    <label class="col-sm-4 control-label">Street Address:</label>
    <div class="col-sm-8">
      <input name="Street" type="text" class="form-control">
    </div>
  </div>
  <div class="form-group">
    <label class="col-sm-4 control-label">City, State, Zip:</label>
    <div class="col-sm-8">
      <input name="CityStateZip" type="text" class="form-control">
    </div>
  </div>
  <div class="form-group">
    <label class="col-sm-4 control-label">Phone, Day:</label>
    <div class="col-sm-8">
      <input name="PhoneDay" type="text" class="form-control">
    </div>
  </div>
  <div class="form-group">
    <label class="col-sm-4 control-label">Phone, Eve:</label>
    <div class="col-sm-8">
      <input name="PhoneEve" type="text" class="form-control">
    </div>
  </div>
  <div class="form-group">
    <label class="col-sm-4 control-label">Todays Date:</label>
    <div class="col-sm-8">
      <input name="Date" type="text" class="form-control">
    </div>
  </div>
  <div class="form-group">
    <label class="col-sm-4 control-label">Date Needed:</label>
    <div class="col-sm-8">
      <input name="DateNeeded" type="text" class="form-control">
    </div>
  </div>
  <div class="form-group">
    <label class="col-sm-4 control-label">CRITICAL----&gt; Absolute Drop Dead Date:</label>
    <div class="col-sm-8">
      <input name="DropDead" type="text" class="form-control">
    </div>
  </div>
  <div class="form-group">
    <label class="col-sm-4 control-label">Comments or Billing Address for Credit Card:</label>
    <div class="col-sm-8">
      <textarea name="Comments" rows="6" cols="60" class="form-control"></textarea>
    </div>
  </div>

  <div class="table-responsive">
    <table class="table table-bordered">
      <thead>
        <tr> 
          <th>QTY</th>
          <th>SIZE</th>
          <th>COLOR</th>
          <th>CLR #2</th>
          <th>ITEM</th>
          <th>EACH</th>
          <th>TOTAL</th>
        </tr>
      </thead>
      <tbody>
        <tr> 
          <td><input name="Qty1" type="text" class="form-control"></td>
          <td><input name="Size1" type="text" class="form-control"></td>
          <td><input name="Color1" type="text" class="form-control"></td>
          <td><input name="Color11" type="text" class="form-control"></td>
          <td><input name="Item1" type="text" class="form-control"></td>
          <td><input name="Cost1" type="text" class="form-control"></td>
          <td><input name="Total1" type="text" class="form-control"></td>
        </tr>
        <tr> 
          <td><input name="Qty2" type="text" class="form-control"></td>
          <td><input name="Size2" type="text" class="form-control"></td>
          <td><input name="Color2" type="text" class="form-control"></td>
          <td><input name="Color22" type="text" class="form-control"></td>
          <td><input name="Item2" type="text" class="form-control"></td>
          <td><input name="Cost2" type="text" class="form-control"></td>
          <td><input name="Total2" type="text" class="form-control"></td>
        </tr>
        <tr> 
          <td><input name="Qty3" type="text" class="form-control"></td>
          <td><input name="Size3" type="text" class="form-control"></td>
          <td><input name="Color3" type="text" class="form-control"></td>
          <td><input name="Color33" type="text" class="form-control"></td>
          <td><input name="Item3" type="text" class="form-control"></td>
          <td><input name="Cost3" type="text" class="form-control"></td>
          <td><input name="Total3" type="text" class="form-control"></td>
        </tr>
        <tr> 
          <td><input name="Qty4" type="text" class="form-control"></td>
          <td><input name="Size4" type="text" class="form-control"></td>
          <td><input name="Color4" type="text" class="form-control"></td>
          <td><input name="Color44" type="text" class="form-control"></td>
          <td><input name="Item4" type="text" class="form-control"></td>
          <td><input name="Cost4" type="text" class="form-control"></td>
          <td><input name="Total4" type="text" class="form-control"></td>
        </tr>
        <tr> 
          <td><input name="Qty5" type="text" class="form-control"></td>
          <td><input name="Size5" type="text" class="form-control"></td>
          <td><input name="Color5" type="text" class="form-control"></td>
          <td><input name="Color55" type="text" class="form-control"></td>
          <td><input name="Item5" type="text" class="form-control"></td>
          <td><input name="Cost5" type="text" class="form-control"></td>
          <td><input name="Total5" type="text" class="form-control"></td>
        </tr>
        <tr> 
          <td><input name="Qty6" type="text" class="form-control" id="Qty6"></td>
          <td><input name="Size6" type="text" class="form-control" id="Size6"></td>
          <td><input name="Color6" type="text" class="form-control" id="Color6"></td>
          <td><input name="Color66" type="text" class="form-control" id="Color66"></td>
          <td><input name="Item6" type="text" class="form-control" id="Item6"></td>
          <td><input name="Cost6" type="text" class="form-control" id="Cost6"></td>
          <td><input name="Total6" type="text" class="form-control" id="Total6"></td>
        </tr>
        <tr> 
          <td><input name="Qty7" type="text" class="form-control" id="Qty7"></td>
          <td><input name="Size7" type="text" class="form-control" id="Size7"></td>
          <td><input name="Color7" type="text" class="form-control" id="Color7"></td>
          <td><input name="Color77" type="text" class="form-control" id="Color77"></td>
          <td><input name="Item7" type="text" class="form-control" id="Item7"></td>
          <td><input name="Cost7" type="text" class="form-control" id="Cost7"></td>
          <td><input name="Total7" type="text" class="form-control" id="Total7"></td>
        </tr>
        <tr> 
          <td><input name="Qty8" type="text" class="form-control" id="Qty8"></td>
          <td><input name="Size8" type="text" class="form-control" id="Size8"></td>
          <td><input name="Color8" type="text" class="form-control" id="Color8"></td>
          <td><input name="Color88" type="text" class="form-control" id="Color88"></td>
          <td><input name="Item8" type="text" class="form-control" id="Item8"></td>
          <td><input name="Cost8" type="text" class="form-control" id="Cost8"></td>
          <td><input name="Total8" type="text" class="form-control" id="Total8"></td>
        </tr>
        <tr> 
          <td rowspan="6" colspan="4">
            <p>
              <strong>Mail:</strong><br>
              FISH Products<br>
              HC1 Box 696<br>
              Joshua Tree, Ca. 92252
            </p>
            <p>
              <strong>Email:</strong> <a href="mailto:FishProductsInfo@gmail.com">FishProductsInfo@gmail.com</a>
            </p>
            <p>
              <strong>Call:</strong> (760) 394.6665 to leave a message
            </p>
            <p>
              <strong>Shipping Rates:</strong><br>
              <strong>Calif:</strong> $7.00 minimum, or 6% of order total to a $28.00 Maximum. Ledges and MaxiPads, So. Cal add $6, Nor. Cal add $9
            </p>
            <p>
              <strong>All other 47 States:</strong> $10.00 minimum, or 10% of total order to a maximum of $34.00. Ledges and MaxiPads, Midwest add $9, East Coast add $14
            </p>
            <p>
              <strong>AK and Hawaii:</strong> Tons... email us.
            </p>
          </td>
          <td colspan="2">MERCHANDISE TOTAL</td>
          <td><input name="MerchTotal" type="text" class="form-control"></td>
        </tr>
        <tr> 
          <td colspan="2">CA 8% SALES TAX</td>
          <td><input name="Tax" type="text" class="form-control"></td>
        </tr>
        <tr> 
          <td colspan="2">SUB TOTAL</td>
          <td><input name="Subtotal" type="text" class="form-control"></td>
        </tr>
        <tr> 
          <td colspan="2">
            SHIPPING CHARGES (see chart)<br>
            <em>Minimum charge in Calif: $7.00</em><br>
            <em>Minimum Charge all other states: $10.00</em>
          </td>
          <td><input name="UPS" type="text" class="form-control"></td>
        </tr>
        <tr> 
          <td colspan="2">Insurance charges for Cam Repair shipping</td>
          <td><input name="COD" type="text" class="form-control"></td>
        </tr>
        <tr> 
          <td colspan="2">
            <p><strong>GRAND TOTAL:</strong></p>
            <p>
              If you need room for more items, 
              add them into the comments text block above or just email us your 
              order.
            </p>
          </td>
          <td><input name="GrandTotal" type="text" class="form-control"></td>
        </tr>
      </tbody>
    </table>
  </div>


  <p>
    If you fill in the card info below, we will process and charge your card inhouse and usually after we are sure of the totals, your math, and have adjusted your order for items that are possibly out of stock. If you use the PayPal link below (you do <strong>NOT</strong> need a paypal account to use this link) your card will be charged immediately and securely processed by PayPal. Your choice. If you choose to use the PayPal link, and your math is off or something is out of stock, we will refund or adjust your payment and then either charge you more, or refund the balance due via PayPal. If you want any refunds to go back to the credit card used for the purchase, I would suggest not using the PayPal option.
  </p>


  <hr />


  <h3>Credit Card Payments:</h3>
  <div class="form-group">
    <label class="col-sm-4 control-label">Name on Card:</label>
    <div class="col-sm-8">
      <input name="NameOnCard" type="text" class="form-control">
    </div>
  </div>
  <div class="form-group">
    <label class="col-sm-4 control-label">Expiration Date:</label>
    <div class="col-sm-8">
      <input name="Expires" type="text" class="form-control">
    </div>
  </div>
  <div class="form-group">
    <div class="col-sm-offset-4 col-sm-8">
      <div class="radio">
        <label>
          <input type="radio" name="payment_method" value="Visa" checked="checked"> Visa
        </label>
      </div>
    </div>
  </div>
  <div class="form-group">
    <div class="col-sm-offset-4 col-sm-8">
      <div class="radio">
        <label>
          <input type="radio" name="payment_method" value="Mastercard"> Mastercard
        </label>
      </div>
    </div>
  </div>
  <div class="form-group">
    <label class="col-sm-4 control-label">Card Number:</label>
    <div class="col-sm-8">
      <input name="cardnumber" type="text" class="form-control" maxlength="16">
    </div>
  </div>
  <div class="form-group">
    <label class="col-sm-4 control-label">3 digit number on the back of the card:</label>
    <div class="col-sm-8">
      <input name="security code" type="text" class="form-control" maxlength="3">
    </div>
  </div>


  <hr />


  <p>
    <strong>SHOP EARLY, SHOP OFTEN, SHOP HEAVY</strong>
  </p>

  <p>
    We're not giant SPAM kings or anything like that, but if you would like to be informed of specials, updates, quizzes, and random wierdness, click the box to get on our mailing list.
  </p>
  <p>
    <input type="checkbox" name="SpamOk" value="checkbox" checked="1">
    SPAM ... or ... <input type="checkbox" name="NoSpam" value="checkbox">
    No SPAM for me
  </p>

  <p>
    <input name="Submit" type="submit" value="Submit the Order" class="btn btn-primary">
    <input name="name" type="reset" value="Reset form" class="btn btn-default">
  </p>
  <p>
    PRESS *SUBMIT* ONLY ONCE!!!
  </p>
  <p>
    If your order form was sent to us (hopefully!) you will be taken to a confirmation page after pressing submit. Use your "BACK" button to return to our site. We will also confirm you again shortly via email. If you do not get an email confirm from a live human within a day or two, please contact us! THANKS!
  </p>


  <hr />


  <p>
    <a href="{{ "/pics/visa.gif" | prepend: site.baseurl }}"><img src="{{ "/pics/visa.gif" | prepend: site.baseurl }}"></a>
    <a href="{{ "/pics/mastercard.gif" | prepend: site.baseurl }}"><img src="{{ "/pics/mastercard.gif" | prepend: site.baseurl }}"></a><br>
    If you want to pay via <strong>PayPal,</strong> simply get your order total and then click on the <strong>PayPal</strong> button below the sample page to be taken directly to their secure site. <strong>Be sure to hit the submit button above so we know what you have ordered.</strong>
  </p>
  <p>
    The <b>PayPal</b> button just lands your cash into our account. It does not give us any order info.
  </p>
  <p>
    Here is a sample of what the PayPal page will look like after you click the button:
    <div class="thumbnail">
      <img src="{{ "/pics/paypal_image.jpg" | prepend: site.baseurl }}">
    </div>
  </p>

  <p>
    To be taken to the PayPal site right now to finish your transaction, click the PayPal button:
  </p>
</form>

<form action="https://www.paypal.com/cgi-bin/webscr" method="POST" enctype="x-www-form-urlencoded" name="paypalform">
  <input type="hidden" name="cmd" value="_xclick">
  <input type="hidden" name="business" value="PayPal@FishProducts.com">
  <input type="hidden" name="item_name" value="FISH Products Order Total">
  <input type="hidden" name="no_shipping" value="1">
  <input type="hidden" name="return" value="{{ site.baseurl }}">
  <input type="hidden" name="cn" value="Special Instructions (optional)">
  <input type="hidden" name="no_note" value="1">
  <input type="hidden" name="currency_code" value="USD">
  <input src="{{ "/pics/x-click-but6.gif" | prepend: site.baseurl }}" type="image" border="0" name="submit" alt="Make payments with PayPal - it&#39;s fast, free and secure!">
</form>



