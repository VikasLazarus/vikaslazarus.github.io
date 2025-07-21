 <!--bottom fixed-->
  <div id="Fixed"
    class="w3-display-container w3-row w3-white w3-border-top w3-border-light-gray w3-hide-large w3-hide-medium w3-animate-zoom"
    style="width: 100%; padding:12px; position: fixed; bottom: -190px; left: 0px; z-index: 30;">
    <div class="w3-display-topright" style="padding: 0px 12px; margin-top: -96px;">
      <a href="tel:8219471645">
        <div class="w3-ro w3-deep-orange w3-card-4"
          style="border-radius:30px ; height: 40px; width: 40px;  padding: 8px 12px; margin-right: 6px; margin-bottom: 8px;">
          <i class="w3-text-white  fa fa-phone small" style="padding-left:0px ;"></i>
        </div>
      </a>
      <a href="https://wa.me/918219471645">
        <div class="w3-ro w3-green w3-card-4"
          style="border-radius:30px ; height: 40px; width: 40px; padding: 10px 12px; margin-right: 6px;">
          <i class="w3-text-white  fab fa-whatsapp w3-large" style="padding-left:0px ;"></i>
        </div>
      </a>

    </div>
    <div class="w3-row">
      <div class="w3-col w3-right" style="width: 110px;">
        <button onclick="document.getElementById('id01').style.display='block'"
          class="w3-button w3-deep-orange w3-small w3-card-4" style="border-radius: 30px;">Send Enquiry</button>
      </div>
      <div class="w3-rest">
        <b class="w3-xlarge">INR 46,000 <span class="w3-small w3-text-gray">Per Couple</span></b>
      </div>
    </div>
  </div>
  <!--model bottom  fixed-->
  <div class="w3-container">


    <div id="id01" class="w3-modal" style="background-color: #48484889; z-index: 120;">
      <div class="w3-bottom w3-white w3-card-4" style="border-radius: 15px 15px 0px 0px;">
        <div class="w3-row">
          <span onclick="document.getElementById('id01').style.display='none'"
            class="w3-button w3-deep-orange w3-card-4 w3-display-topright"
            style="padding: 6px 12px; border-radius: 30px; margin-top: -45px; margin-right: 12px;">&times;</span>

          <div class="w3-half w3-padding">

            <div class="w3-text-dark-gray" style="border-radius: 15px;">
              <div style="margin-top: 30px;">
                <h2 class="w3-large"><strong>
                    Shimla Couple Tour From Chandigarh 4 Nighs 5 Days
                  </strong></h2>
                <p><b class="w3-xlarge">INR 46,000 <span class="w3-small w3-text-gray">Per Couple</span></b>
                  <br><strike class="w3-text-gray">INR 56,000</strike>
                </p>

              </div>
              <hr>
              <form class="w3-text-dark-gray w3-row"
                onsubmit="alert('Thanks For Submiting The Form. Our Executives Will Reach To You Within 24 Hours');"
                method="page">
                <div style="margin-bottom: 6px;" class="elem-group w3-col s12 m12 l12">
                  <lable class="w3-small" style="margin-bottom: 4px;">Full Name <span class="w3-text-red">*</span>
                  </lable>
                  <input style="border-radius: 15px;" class=" w3-input w3-large w3-round w3-tiny w3-border" type="text"
                    id="name" name="visitor_name" placeholder="Jonh Doe" pattern="[A-Z\sa-z]{3,20}" required="">
                </div>
                <div class="elem-group w3-col s12 m12 l12" style="margin-bottom: 6px;">
                  <lable class="w3-small" style="margin-bottom: 4px;">Email Address <span class="w3-text-red">*</span>
                  </lable>

                  <input style="border-radius: 15px;" class=" w3-input w3-large w3-round w3-tiny w3-border" type="email"
                    id="email" name="visitor_email" placeholder="john.doe@email.com" required="">
                </div>
                <div class="elem-group w3-col s12 m12 l12" style="margin-bottom: 6px;">
                  <lable class="w3-small" style="margin-bottom: 4px;">Contect Number <span class="w3-text-red">*</span>
                  </lable>

                  <input style="border-radius: 15px;" class="w3-input w3-large w3-round w3-tiny w3-border" type="tel"
                    id="phone" name="visitor_phone" placeholder="+91-81294-71645"
                    pattern="(\d{3})-?\s?(\d{3})-?\s?(\d{4})" required="">
                </div>
                <div class="w3-row">
                  <div class=" w3-col s4 m4 l4" style="margin-bottom: 6px;">
                    <lable class="w3-small" style="margin-bottom: 4px;">Traveller Count <span
                        class="w3-text-red">*</span></lable>
                    <input style="border-radius: 15px;" class=" w3-input w3-large w3-round w3-tiny w3-border"
                      type="number" id="adult" name="total_adults" placeholder="Travelrs Count" min="1" required="">
                  </div>

                  <div class="w3-col s8 m8 l8" style="padding-left: 12px;">
                    <lable class="w3-small" style="margin-bottom: 4px;">Travel Date <span class="w3-text-red">*</span>
                    </lable>

                    <input style="margin-bottom: 4px; border-radius: 15px;"
                      class="w3-right-align w3-rest w3-input w3-large w3-round w3-tiny w3-border" type="date"
                      id="checkout-date" name="checkout" required="">
                  </div>

                </div>


            </div>
            <div class="w3-row">
              <button
                class="w3-large w3-mobile w3-button w3-round w3-text-white w3-margin-top w3-margin-bottom w3-left w3-deep-orange w3-small"
                style="border-radius: 30px;" type="submit">Connect With a Expert</button>
            </div>
          </div>

        </div>
      </div>
    </div>
  </div>
  </div>