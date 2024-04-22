<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="css\home.css">
    <link rel="stylesheet" href="css\styles.css">
    <link rel="stylesheet" href="css\services.css">
    <link rel="stylesheet" href="css\about-us.css">
    <link rel="stylesheet" href="css\Contactcss.css">
    <link rel="stylesheet" href="css\dev.css">
    <link rel="stylesheet" href="css\modal.css">
    <link rel="stylesheet" href="css\footer.css">
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link rel="shortcut icon" href="images\icon.png" type="image/x-icon">
    <link rel="stylesheet" href="https://unpkg.com/swiper/swiper-bundle.css"/>
    <script src="https://unpkg.com/swiper/swiper-bundle.js"></script>
    <script src="https://unpkg.com/swiper/swiper-bundle.min.js"></script>
    <link rel="stylesheet" href="https://unpkg.com/swiper/swiper-bundle.min.css"/>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/animejs/3.2.1/anime.min.js" integrity="sha512-z4OUqw38qNLpn1libAN9BsoDx6nbNFio5lA6CuTp9NlK83b89hgyCVq+N5FdBJptINztxn1Z3SaKSKUS5UP60Q==" crossorigin="anonymous"></script>
    <link href="https://fonts.googleapis.com/css2?family=Poppins&family=Roboto&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@900&display=swap" rel="stylesheet">
    <script src="https://cdnjs.cloudflare.com/ajax/libs/animejs/2.0.2/anime.min.js"></script>
    <title>PLASTIC WASTE </title>
  </head>
  <body>
    <!-- homepage -->
    <section id="one">
      <div class="right">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQLbxz5G1qL63ATtW_DquaPzc4ydLWB84JYyv3T3U81IV1uF5HhOB2Y7tEPm2begFVQ4pE&usqp=CAU" alt="home image">
      </div>
    </section>

    <!-- ourservices page -->
    <section id="two">
      <h1 id="ourservices">Our Services</h1>
      <div class="service-card1">
        <div class="top-image"><img src="images\map.svg" alt="map logo" srcset=""></div>
        <h2>Drop-off</h2>
        <p>Know our locations near you to drop-off your waste.</p>
        <button class="know-more open-button" id="know-more" onclick="openForm()" type="submit">Know more</button>
        <h5 class="confirm" id="checkauth">Please sign-in to use our services</h5>
      </div>
      <div class="service-card">
        <div class="top-image"><img src="images\local_shipping.svg" alt=""></div>
        <h2>Pickup</h2>
        <p>Want to schedule pickup with us?</p>
        <button class="know-more" id="know-more1" onclick="javascript:window.open('pickup.html','_blank')" formtarget="_blank" type="submit">Know more</button>
        <h5 class="confirm" id="checkauth1">Please sign-in to use our services</h5>
        <h5 class="confirm">You can schedule pickup once in a day.</h5>
      </div>
      <div class="form-popup" id="myForm">
        <form action="/action_page.php" class="form-container">
          <iframe src="" width="580px" height="480" allowfullscreen="allowfullscreen"></iframe>
          <button type="button" class="btn cancel" onclick="closeForm()">Close</button>
        </form>
      </div>
    </section>

    <!-- about-us -->
    <section id="three">
      <h1 id="abt-us">About-us</h1>
      <div class="abt-wrapper">
        <img src="https://w0.peakpx.com/wallpaper/130/681/HD-wallpaper-ecology-environment-water-earth-environmental-concepts-eco.jpg" alt="Pricing Image">
        <div class="abt-content">
          <h3>Pricing</h3>
          <p>We offer standardized pricing in every city across all commodities.Each commodity would have fixed price of it per unit. The price we fix keeps in mind your satisfaction.You would be informed well in advance about prices.
          </p>
        </div>
      </div>
      <div class="abt-wrapper">
        <img src="images\cwa.svg" alt="Commodities Image">
        <div class="abt-content content-2">
          <h3>Commodities we accept</h3>
          <p>Whether it be paper,plastic,steel or old iron we accept everything that's recyclable.To be more specific we accept all paper items, all cardboard items,all metal items inculding tin,and all plastic items that can be recycled.
          </p>
        </div>
      </div>
      <div class="abt-wrapper">
        <img src="images\wwdwyw.svg" alt="Waste Image">
        <div class="abt-content content-3">
          <h3>What we do with your waste?</h3>
          <p>After collecting your waste we segregate it efficiently into dry and wet waste. We then communicate and co-ordinate with all recyclable industries.After that the segregated waste is sent to different plants specializing in that industry.
          </p>
        </div>
      </div>

      <div class="resp-abtus">
        <h2 id="abt-us">About-us</h2>
        <div class="swiper-container">
          <div class="swiper-wrapper">
            <div class="swiper-slide">
              <div class="abt-card">
                <div class="at-card-img">
                  <img src="images\pricing.svg" alt="Pricing Image">
                </div>
                <div class="abt-card-heading">
                  <h3>Pricing</h3>
                </div>
                <div class="abt-card-text">
                  <p>We offer standardized pricing in every city across all commodities.Each commodity would have fixed price of it per unit. The price we fix keeps in mind your satisfaction.You would be informed well in advance about prices.
                  </p>
                </div>
              </div>
            </div>
            <div class="swiper-slide">
              <div class="abt-card" style=" border-color: #FFC906;">
                <div class="at-card-img" style=" background-color: #FFC906;">
                  <img src="images\cwa.svg" alt="Commodities Image">
                </div>
                <div class="abt-card-heading">
                  <h3>Commodities we accept</h3>
                </div>
                <div class="abt-card-text">
                  <p>Whether it be paper,plastic,steel or old iron we accept everything that's recyclable.To be more specific we accept all paper items, all cardboard items,all metal items inculding tin,and all plastic items that can be recycled.
                  </p>
                </div>
              </div>
            </div>
            <div class="swiper-slide">
              <div class="abt-card" style=" border-color: #2B77B5;">
                <div class="at-card-img" style=" background-color: #2B77B5;">
                  <img src="images\wwdwyw.svg" alt="Waste Image">
                </div>
                <div class="abt-card-heading">
                  <h3>What we do with your waste?</h3>
                </div>
                <div class="abt-card-text">
                  <p>After collecting your waste we segregate it efficiently into dry and wet waste. We then communicate and co-ordinate with all recyclable industries.After that the segregated waste is sent to different plants specializing in that industry.
                  </p>
                </div>
              </div>
            </div>

            <!-- Add Pagination -->
            <div class="swiper-pagination"></div>
          </div>
        </div>
      </div>
    </section>
    <!-- contact-us -->
    <section id="four">
      <h1 id="even-h1">Contact-us</h1>
      <div class="contact-us">
        <div class="cnt-img">
          <img src="images\contact-image.svg" alt="Connect Image">
        </div>
        <form class="gform" method="POST" data-email="ucoeproject@gmail.com" name="google-sheet">
          <div class="cnt-bx">
            <input type="text" id="name" class="name" name="name" required="required">
            <span>Full Name(XYZ)</span>
          </div>
          <div class="cnt-bx">
            <input type="text" id="email" class="email" name="email" required="required">
            <span>Email Address(xyz@email.com)</span>
          </div>
          <div class="cnt-bx">
            <textarea name="message" class="message" id="message" cols="80" rows="10" required="required"></textarea>
            <span>Comments/Suggestions/Complaints</span>
          </div>
          <button class="cnt-btn" type="submit" id="contact" onclick="location.href = 'index.html';">Submit</button>
        </form>
      </div>
      <!--mobile view code for contact form --->
      <div class="contact-us-mob">
        <div class="contact-us-form">
          <form class="gform" method="POST" data-email="ucoeproject@gmail.com" name="google-sheet" s="s">
            <div class="cnt-img-mob">
              <img src="images\contact-image.svg" alt="Connect Image">
            </div>
            <label for="fname">Full Name</label>
            <input type="text" id="fname" name="fullname" placeholder="Name">

            <label for="email">Email Id</label>
            <input type="text" id="email" class="email" name="email" placeholder="xyz@email.com" required="required">

            <label for="subject">Comments/Suggestions/Complaints</label>
            <textarea id="subject" name="subject" placeholder="Comments....." style="height:200px"></textarea>

            <button class="cnt-mob-btn" type="submit" id="contact" onclick="location.href = 'index.html';">Submit</button>
          </form>
        </div>
      </div>
    </section>
    <!-- Developer -->
    <section id="five">
      <h1 id="dev">Developers</h1>
      <div class="dev-container">
        <div class="dev-card">
          <div class="card-bottom">
            <div class="dev-name">
              <h3>Deepak</h3>
            </div>
            <div class="dev-title">
              <span>(Web Developer)<span></div>
                <div class="dev-media">
                  <a class="social" href="https://www.facebook.com/vivek.hotti.9/">
                    <svg id="logo" viewbox="0 0 48 47" xmlns="http://www.w3.org/2000/svg">
                      <path
                        d="M47.25 24C47.25 11.1562 36.8438 0.75 24 0.75C11.1562 0.75 0.75 11.1562 0.75 24C0.75 35.6044 9.25219 45.2231 20.3672 46.9688V30.7209H14.4609V24H20.3672V18.8775C20.3672 13.0509 23.8359 9.8325 29.1488 9.8325C31.6931 9.8325 34.3538 10.2863 34.3538 10.2863V16.005H31.4212C28.5338 16.005 27.6328 17.7975 27.6328 19.6359V24H34.0809L33.0497 30.7209H27.6328V46.9688C38.7478 45.2231 47.25 35.6044 47.25 24Z"
                        fill=""/>
                      <defs>
                        <lineargradient id="paint0_linear" x1="24" y1="0" x2="24" y2="48" gradientunits="userSpaceOnUse">
                          <stop stop-color="#F8B195"/>
                          <stop offset="0.225" stop-color="#F67280"/>
                          <stop offset="0.417708" stop-color="#C06C84"/>
                          <stop offset="0.678125" stop-color="#6C5B7B"/>
                          <stop offset="0.907291" stop-color="#013F59"/>
                        </lineargradient>
                      </defs>
                    </svg>

                  </a>
                  <a class="social" href="https://github.com/Vivek-Hotti">
                    <svg id="logo" viewbox="0 0 48 48" xmlns="http://www.w3.org/2000/svg">
                      <path
                        d="M16.0548 38.4583C16.0548 38.6518 15.8323 38.8067 15.5516 38.8067C15.2323 38.8357 15.0097 38.6809 15.0097 38.4583C15.0097 38.2647 15.2323 38.1099 15.5129 38.1099C15.8032 38.0809 16.0548 38.2357 16.0548 38.4583ZM13.0452 38.0228C12.9774 38.2163 13.171 38.4389 13.4613 38.497C13.7129 38.5938 14.0032 38.497 14.0613 38.3034C14.1194 38.1099 13.9355 37.8873 13.6452 37.8002C13.3935 37.7325 13.1129 37.8293 13.0452 38.0228ZM17.3226 37.8583C17.0419 37.926 16.8484 38.1099 16.8774 38.3325C16.9065 38.526 17.1581 38.6518 17.4484 38.5841C17.729 38.5163 17.9226 38.3325 17.8935 38.1389C17.8645 37.9551 17.6032 37.8293 17.3226 37.8583ZM23.6903 0.774414C10.2677 0.774414 0 10.9647 0 24.3873C0 35.1196 6.75484 44.3034 16.4032 47.5357C17.6419 47.7583 18.0774 46.9938 18.0774 46.3647C18.0774 45.7647 18.0484 42.4551 18.0484 40.4228C18.0484 40.4228 11.2742 41.8744 9.85161 37.5389C9.85161 37.5389 8.74839 34.7228 7.16129 33.997C7.16129 33.997 4.94516 32.4776 7.31613 32.5067C7.31613 32.5067 9.72581 32.7002 11.0516 35.0034C13.171 38.7389 16.7226 37.6647 18.1065 37.026C18.329 35.4776 18.9581 34.4034 19.6548 33.7647C14.2452 33.1647 8.7871 32.3809 8.7871 23.0712C8.7871 20.4099 9.52258 19.0744 11.071 17.3712C10.8194 16.7422 9.99677 14.1486 11.3226 10.8002C13.3452 10.1712 18 13.4131 18 13.4131C19.9355 12.8712 22.0161 12.5905 24.0774 12.5905C26.1387 12.5905 28.2194 12.8712 30.1548 13.4131C30.1548 13.4131 34.8097 10.1615 36.8323 10.8002C38.1581 14.1583 37.3355 16.7422 37.0839 17.3712C38.6323 19.0841 39.5806 20.4196 39.5806 23.0712C39.5806 32.4099 33.8806 33.1551 28.471 33.7647C29.3613 34.5293 30.1161 35.9809 30.1161 38.2551C30.1161 41.5163 30.0871 45.5518 30.0871 46.3454C30.0871 46.9744 30.5323 47.7389 31.7613 47.5163C41.4387 44.3034 48 35.1196 48 24.3873C48 10.9647 37.1129 0.774414 23.6903 0.774414ZM9.40645 34.1518C9.28064 34.2486 9.30968 34.4712 9.47419 34.6551C9.62903 34.8099 9.85161 34.8776 9.97742 34.7518C10.1032 34.6551 10.0742 34.4325 9.90968 34.2486C9.75484 34.0938 9.53226 34.026 9.40645 34.1518ZM8.36129 33.368C8.29355 33.4938 8.39032 33.6486 8.58387 33.7454C8.73871 33.8422 8.93226 33.8131 9 33.6776C9.06774 33.5518 8.97097 33.397 8.77742 33.3002C8.58387 33.2422 8.42903 33.2712 8.36129 33.368ZM11.4968 36.8131C11.3419 36.9389 11.4 37.2293 11.6226 37.4131C11.8452 37.6357 12.1258 37.6647 12.2516 37.5099C12.3774 37.3841 12.3194 37.0938 12.1258 36.9099C11.9129 36.6873 11.6226 36.6583 11.4968 36.8131ZM10.3935 35.3905C10.2387 35.4873 10.2387 35.7389 10.3935 35.9615C10.5484 36.1841 10.8097 36.2809 10.9355 36.1841C11.0903 36.0583 11.0903 35.8067 10.9355 35.5841C10.8 35.3615 10.5484 35.2647 10.3935 35.3905Z"
                        fill=""/>
                      <defs>
                        <lineargradient id="paint0_linear" x1="24" y1="0" x2="24" y2="48" gradientunits="userSpaceOnUse">
                          <stop stop-color="#F8B195"/>
                          <stop offset="0.225" stop-color="#F67280"/>
                          <stop offset="0.417708" stop-color="#C06C84"/>
                          <stop offset="0.678125" stop-color="#6C5B7B"/>
                          <stop offset="0.907291" stop-color="#013F59"/>
                        </lineargradient>
                      </defs>
                    </svg>

                  </a>
                  <a class="social" href="https://www.instagram.com/vivek_hotti/">
                    <svg id="logo" viewbox="0 0 48 48" xmlns="http://www.w3.org/2000/svg">
                      <path d="M28.5938 24C28.5938 26.5371 26.5371 28.5938 24 28.5938C21.4629 28.5938 19.4062 26.5371 19.4062 24C19.4062 21.4629 21.4629 19.4062 24 19.4062C26.5371 19.4062 28.5938 21.4629 28.5938 24Z" fill=""/>
                      <path
                        d="M34.7432 15.8723C34.5223 15.2739 34.17 14.7323 33.7123 14.2877C33.2677 13.83 32.7264 13.4777 32.1277 13.2568C31.6421 13.0682 30.9126 12.8438 29.569 12.7826C28.1155 12.7163 27.6797 12.702 24 12.702C20.3199 12.702 19.8842 12.7159 18.431 12.7822C17.0874 12.8438 16.3575 13.0682 15.8723 13.2568C15.2736 13.4777 14.7319 13.83 14.2877 14.2877C13.83 14.7323 13.4777 15.2736 13.2565 15.8723C13.0679 16.3579 12.8434 17.0878 12.7822 18.4314C12.7159 19.8845 12.7017 20.3203 12.7017 24.0004C12.7017 27.6801 12.7159 28.1158 12.7822 29.5693C12.8434 30.913 13.0679 31.6425 13.2565 32.1281C13.4777 32.7268 13.8296 33.2681 14.2874 33.7126C14.7319 34.1704 15.2732 34.5227 15.8719 34.7435C16.3575 34.9325 17.0874 35.157 18.431 35.2181C19.8842 35.2844 20.3196 35.2983 23.9996 35.2983C27.6801 35.2983 28.1158 35.2844 29.5686 35.2181C30.9122 35.157 31.6421 34.9325 32.1277 34.7435C33.3296 34.2799 34.2795 33.33 34.7432 32.1281C34.9318 31.6425 35.1562 30.913 35.2178 29.5693C35.2841 28.1158 35.298 27.6801 35.298 24.0004C35.298 20.3203 35.2841 19.8845 35.2178 18.4314C35.1566 17.0878 34.9321 16.3579 34.7432 15.8723ZM24 31.0767C20.0914 31.0767 16.923 27.9086 16.923 24C16.923 20.0914 20.0914 16.9233 24 16.9233C27.9082 16.9233 31.0767 20.0914 31.0767 24C31.0767 27.9086 27.9082 31.0767 24 31.0767ZM31.3564 18.2974C30.4431 18.2974 29.7026 17.5569 29.7026 16.6436C29.7026 15.7302 30.4431 14.9897 31.3564 14.9897C32.2698 14.9897 33.0103 15.7302 33.0103 16.6436C33.0099 17.5569 32.2698 18.2974 31.3564 18.2974Z"
                        fill=""/>
                      <path
                        d="M24 0C10.7472 0 0 10.7472 0 24C0 37.2528 10.7472 48 24 48C37.2528 48 48 37.2528 48 24C48 10.7472 37.2528 0 24 0ZM37.6981 29.6818C37.6315 31.1488 37.3982 32.1504 37.0576 33.0271C36.3417 34.8783 34.8783 36.3417 33.0271 37.0576C32.1508 37.3982 31.1488 37.6311 29.6821 37.6981C28.2125 37.7651 27.743 37.7812 24.0004 37.7812C20.2573 37.7812 19.7882 37.7651 18.3182 37.6981C16.8516 37.6311 15.8496 37.3982 14.9733 37.0576C14.0533 36.7115 13.2206 36.1692 12.5321 35.4679C11.8312 34.7798 11.2888 33.9467 10.9427 33.0271C10.6022 32.1508 10.3689 31.1488 10.3022 29.6821C10.2345 28.2122 10.2188 27.7427 10.2188 24C10.2188 20.2573 10.2345 19.7878 10.3019 18.3182C10.3685 16.8512 10.6014 15.8496 10.942 14.9729C11.2881 14.0533 11.8308 13.2202 12.5321 12.5321C13.2202 11.8308 14.0533 11.2885 14.9729 10.9424C15.8496 10.6018 16.8512 10.3689 18.3182 10.3019C19.7878 10.2349 20.2573 10.2188 24 10.2188C27.7427 10.2188 28.2122 10.2349 29.6818 10.3022C31.1488 10.3689 32.1504 10.6018 33.0271 10.942C33.9467 11.2881 34.7798 11.8308 35.4683 12.5321C36.1692 13.2206 36.7119 14.0533 37.0576 14.9729C37.3986 15.8496 37.6315 16.8512 37.6985 18.3182C37.7655 19.7878 37.7812 20.2573 37.7812 24C37.7812 27.7427 37.7655 28.2122 37.6981 29.6818Z"
                        fill=""/>
                      <defs>
                        <lineargradient id="paint0_linear" x1="24" y1="0" x2="24" y2="48" gradientunits="userSpaceOnUse">
                          <stop stop-color="#F8B195"/>
                          <stop offset="0.225" stop-color="#F67280"/>
                          <stop offset="0.417708" stop-color="#C06C84"/>
                          <stop offset="0.678125" stop-color="#6C5B7B"/>
                          <stop offset="0.907291" stop-color="#013F59"/>
                        </lineargradient>
                      </defs>
                    </svg>

                  </a>
                  <a class="social" href="https://www.linkedin.com/in/vivekhotti/">
                    <svg id="logo" viewbox="0 0 48 48" xmlns="http://www.w3.org/2000/svg">
                      <path
                        d="M44.5714 0H3.41786C1.53214 0 0 1.55357 0 3.46072V44.5393C0 46.4464 1.53214 48 3.41786 48H44.5714C46.4571 48 48 46.4464 48 44.5393V3.46072C48 1.55357 46.4571 0 44.5714 0ZM14.5071 41.1429H7.39286V18.2357H14.5179V41.1429H14.5071ZM10.95 15.1071C8.66786 15.1071 6.825 13.2536 6.825 10.9821C6.825 8.71072 8.66786 6.85714 10.95 6.85714C13.2214 6.85714 15.075 8.71072 15.075 10.9821C15.075 13.2643 13.2321 15.1071 10.95 15.1071ZM41.175 41.1429H34.0607V30C34.0607 27.3429 34.0071 23.925 30.3643 23.925C26.6571 23.925 26.0893 26.8179 26.0893 29.8071V41.1429H18.975V18.2357H25.8V21.3643H25.8964C26.85 19.5643 29.175 17.6679 32.6357 17.6679C39.8357 17.6679 41.175 22.4143 41.175 28.5857V41.1429Z"
                        fill=""/>
                      <defs>
                        <lineargradient id="paint0_linear" x1="24" y1="0" x2="24" y2="48" gradientunits="userSpaceOnUse">
                          <stop stop-color="#F8B195"/>
                          <stop offset="0.225" stop-color="#F67280"/>
                          <stop offset="0.417708" stop-color="#C06C84"/>
                          <stop offset="0.678125" stop-color="#6C5B7B"/>
                          <stop offset="0.907291" stop-color="#013F59"/>
                        </lineargradient>
                      </defs>
                    </svg>
                  </a>
                </div>
                <div class="dev-btn">
                  <button type="submit" onclick="location.href='mailto:vivekshotti@gmail.com';" target="blank">Connect</button>
                </div>
              </div>
              <div class="imgbox">
                <img class="profile" src="images\Vivek.png" alt="Vivek Profile">
              </div>
            </div>
            <div class="dev-card">
              <div class="card-bottom">
                <div class="dev-name">
                  <h3>Hemanth</h3>
                </div>
                <div class="dev-title">
                  <span>(Web Developer)<span></div>
                    <div class="dev-media">
                      <a class="social" href="https://www.facebook.com/rohan.makwana.1804">
                        <svg id="logo" viewbox="0 0 48 47" xmlns="http://www.w3.org/2000/svg">
                          <path
                            d="M47.25 24C47.25 11.1562 36.8438 0.75 24 0.75C11.1562 0.75 0.75 11.1562 0.75 24C0.75 35.6044 9.25219 45.2231 20.3672 46.9688V30.7209H14.4609V24H20.3672V18.8775C20.3672 13.0509 23.8359 9.8325 29.1488 9.8325C31.6931 9.8325 34.3538 10.2863 34.3538 10.2863V16.005H31.4212C28.5338 16.005 27.6328 17.7975 27.6328 19.6359V24H34.0809L33.0497 30.7209H27.6328V46.9688C38.7478 45.2231 47.25 35.6044 47.25 24Z"
                            fill=""/>
                          <defs>
                            <lineargradient id="paint0_linear" x1="24" y1="0" x2="24" y2="48" gradientunits="userSpaceOnUse">
                              <stop stop-color="#F8B195"/>
                              <stop offset="0.225" stop-color="#F67280"/>
                              <stop offset="0.417708" stop-color="#C06C84"/>
                              <stop offset="0.678125" stop-color="#6C5B7B"/>
                              <stop offset="0.907291" stop-color="#013F59"/>
                            </lineargradient>
                          </defs>
                        </svg>

                      </a>
                      <a class="social" href="https://github.com/RM6501">
                        <svg id="logo" viewbox="0 0 48 48" xmlns="http://www.w3.org/2000/svg">
                          <path
                            d="M16.0548 38.4583C16.0548 38.6518 15.8323 38.8067 15.5516 38.8067C15.2323 38.8357 15.0097 38.6809 15.0097 38.4583C15.0097 38.2647 15.2323 38.1099 15.5129 38.1099C15.8032 38.0809 16.0548 38.2357 16.0548 38.4583ZM13.0452 38.0228C12.9774 38.2163 13.171 38.4389 13.4613 38.497C13.7129 38.5938 14.0032 38.497 14.0613 38.3034C14.1194 38.1099 13.9355 37.8873 13.6452 37.8002C13.3935 37.7325 13.1129 37.8293 13.0452 38.0228ZM17.3226 37.8583C17.0419 37.926 16.8484 38.1099 16.8774 38.3325C16.9065 38.526 17.1581 38.6518 17.4484 38.5841C17.729 38.5163 17.9226 38.3325 17.8935 38.1389C17.8645 37.9551 17.6032 37.8293 17.3226 37.8583ZM23.6903 0.774414C10.2677 0.774414 0 10.9647 0 24.3873C0 35.1196 6.75484 44.3034 16.4032 47.5357C17.6419 47.7583 18.0774 46.9938 18.0774 46.3647C18.0774 45.7647 18.0484 42.4551 18.0484 40.4228C18.0484 40.4228 11.2742 41.8744 9.85161 37.5389C9.85161 37.5389 8.74839 34.7228 7.16129 33.997C7.16129 33.997 4.94516 32.4776 7.31613 32.5067C7.31613 32.5067 9.72581 32.7002 11.0516 35.0034C13.171 38.7389 16.7226 37.6647 18.1065 37.026C18.329 35.4776 18.9581 34.4034 19.6548 33.7647C14.2452 33.1647 8.7871 32.3809 8.7871 23.0712C8.7871 20.4099 9.52258 19.0744 11.071 17.3712C10.8194 16.7422 9.99677 14.1486 11.3226 10.8002C13.3452 10.1712 18 13.4131 18 13.4131C19.9355 12.8712 22.0161 12.5905 24.0774 12.5905C26.1387 12.5905 28.2194 12.8712 30.1548 13.4131C30.1548 13.4131 34.8097 10.1615 36.8323 10.8002C38.1581 14.1583 37.3355 16.7422 37.0839 17.3712C38.6323 19.0841 39.5806 20.4196 39.5806 23.0712C39.5806 32.4099 33.8806 33.1551 28.471 33.7647C29.3613 34.5293 30.1161 35.9809 30.1161 38.2551C30.1161 41.5163 30.0871 45.5518 30.0871 46.3454C30.0871 46.9744 30.5323 47.7389 31.7613 47.5163C41.4387 44.3034 48 35.1196 48 24.3873C48 10.9647 37.1129 0.774414 23.6903 0.774414ZM9.40645 34.1518C9.28064 34.2486 9.30968 34.4712 9.47419 34.6551C9.62903 34.8099 9.85161 34.8776 9.97742 34.7518C10.1032 34.6551 10.0742 34.4325 9.90968 34.2486C9.75484 34.0938 9.53226 34.026 9.40645 34.1518ZM8.36129 33.368C8.29355 33.4938 8.39032 33.6486 8.58387 33.7454C8.73871 33.8422 8.93226 33.8131 9 33.6776C9.06774 33.5518 8.97097 33.397 8.77742 33.3002C8.58387 33.2422 8.42903 33.2712 8.36129 33.368ZM11.4968 36.8131C11.3419 36.9389 11.4 37.2293 11.6226 37.4131C11.8452 37.6357 12.1258 37.6647 12.2516 37.5099C12.3774 37.3841 12.3194 37.0938 12.1258 36.9099C11.9129 36.6873 11.6226 36.6583 11.4968 36.8131ZM10.3935 35.3905C10.2387 35.4873 10.2387 35.7389 10.3935 35.9615C10.5484 36.1841 10.8097 36.2809 10.9355 36.1841C11.0903 36.0583 11.0903 35.8067 10.9355 35.5841C10.8 35.3615 10.5484 35.2647 10.3935 35.3905Z"
                            fill=""/>
                          <defs>
                            <lineargradient id="paint0_linear" x1="24" y1="0" x2="24" y2="48" gradientunits="userSpaceOnUse">
                              <stop stop-color="#F8B195"/>
                              <stop offset="0.225" stop-color="#F67280"/>
                              <stop offset="0.417708" stop-color="#C06C84"/>
                              <stop offset="0.678125" stop-color="#6C5B7B"/>
                              <stop offset="0.907291" stop-color="#013F59"/>
                            </lineargradient>
                          </defs>
                        </svg>

                      </a>
                      <a class="social" href="https://www.instagram.com/rohan_0651/">
                        <svg id="logo" viewbox="0 0 48 48" xmlns="http://www.w3.org/2000/svg">
                          <path d="M28.5938 24C28.5938 26.5371 26.5371 28.5938 24 28.5938C21.4629 28.5938 19.4062 26.5371 19.4062 24C19.4062 21.4629 21.4629 19.4062 24 19.4062C26.5371 19.4062 28.5938 21.4629 28.5938 24Z" fill=""/>
                          <path
                            d="M34.7432 15.8723C34.5223 15.2739 34.17 14.7323 33.7123 14.2877C33.2677 13.83 32.7264 13.4777 32.1277 13.2568C31.6421 13.0682 30.9126 12.8438 29.569 12.7826C28.1155 12.7163 27.6797 12.702 24 12.702C20.3199 12.702 19.8842 12.7159 18.431 12.7822C17.0874 12.8438 16.3575 13.0682 15.8723 13.2568C15.2736 13.4777 14.7319 13.83 14.2877 14.2877C13.83 14.7323 13.4777 15.2736 13.2565 15.8723C13.0679 16.3579 12.8434 17.0878 12.7822 18.4314C12.7159 19.8845 12.7017 20.3203 12.7017 24.0004C12.7017 27.6801 12.7159 28.1158 12.7822 29.5693C12.8434 30.913 13.0679 31.6425 13.2565 32.1281C13.4777 32.7268 13.8296 33.2681 14.2874 33.7126C14.7319 34.1704 15.2732 34.5227 15.8719 34.7435C16.3575 34.9325 17.0874 35.157 18.431 35.2181C19.8842 35.2844 20.3196 35.2983 23.9996 35.2983C27.6801 35.2983 28.1158 35.2844 29.5686 35.2181C30.9122 35.157 31.6421 34.9325 32.1277 34.7435C33.3296 34.2799 34.2795 33.33 34.7432 32.1281C34.9318 31.6425 35.1562 30.913 35.2178 29.5693C35.2841 28.1158 35.298 27.6801 35.298 24.0004C35.298 20.3203 35.2841 19.8845 35.2178 18.4314C35.1566 17.0878 34.9321 16.3579 34.7432 15.8723ZM24 31.0767C20.0914 31.0767 16.923 27.9086 16.923 24C16.923 20.0914 20.0914 16.9233 24 16.9233C27.9082 16.9233 31.0767 20.0914 31.0767 24C31.0767 27.9086 27.9082 31.0767 24 31.0767ZM31.3564 18.2974C30.4431 18.2974 29.7026 17.5569 29.7026 16.6436C29.7026 15.7302 30.4431 14.9897 31.3564 14.9897C32.2698 14.9897 33.0103 15.7302 33.0103 16.6436C33.0099 17.5569 32.2698 18.2974 31.3564 18.2974Z"
                            fill=""/>
                          <path
                            d="M24 0C10.7472 0 0 10.7472 0 24C0 37.2528 10.7472 48 24 48C37.2528 48 48 37.2528 48 24C48 10.7472 37.2528 0 24 0ZM37.6981 29.6818C37.6315 31.1488 37.3982 32.1504 37.0576 33.0271C36.3417 34.8783 34.8783 36.3417 33.0271 37.0576C32.1508 37.3982 31.1488 37.6311 29.6821 37.6981C28.2125 37.7651 27.743 37.7812 24.0004 37.7812C20.2573 37.7812 19.7882 37.7651 18.3182 37.6981C16.8516 37.6311 15.8496 37.3982 14.9733 37.0576C14.0533 36.7115 13.2206 36.1692 12.5321 35.4679C11.8312 34.7798 11.2888 33.9467 10.9427 33.0271C10.6022 32.1508 10.3689 31.1488 10.3022 29.6821C10.2345 28.2122 10.2188 27.7427 10.2188 24C10.2188 20.2573 10.2345 19.7878 10.3019 18.3182C10.3685 16.8512 10.6014 15.8496 10.942 14.9729C11.2881 14.0533 11.8308 13.2202 12.5321 12.5321C13.2202 11.8308 14.0533 11.2885 14.9729 10.9424C15.8496 10.6018 16.8512 10.3689 18.3182 10.3019C19.7878 10.2349 20.2573 10.2188 24 10.2188C27.7427 10.2188 28.2122 10.2349 29.6818 10.3022C31.1488 10.3689 32.1504 10.6018 33.0271 10.942C33.9467 11.2881 34.7798 11.8308 35.4683 12.5321C36.1692 13.2206 36.7119 14.0533 37.0576 14.9729C37.3986 15.8496 37.6315 16.8512 37.6985 18.3182C37.7655 19.7878 37.7812 20.2573 37.7812 24C37.7812 27.7427 37.7655 28.2122 37.6981 29.6818Z"
                            fill=""/>
                          <defs>
                            <lineargradient id="paint0_linear" x1="24" y1="0" x2="24" y2="48" gradientunits="userSpaceOnUse">
                              <stop stop-color="#F8B195"/>
                              <stop offset="0.225" stop-color="#F67280"/>
                              <stop offset="0.417708" stop-color="#C06C84"/>
                              <stop offset="0.678125" stop-color="#6C5B7B"/>
                              <stop offset="0.907291" stop-color="#013F59"/>
                            </lineargradient>
                          </defs>
                        </svg>

                      </a>
                      <a class="social" href="https://www.linkedin.com/in/rohan-makwana-2835bb1a7/">
                        <svg id="logo" viewbox="0 0 48 48" xmlns="http://www.w3.org/2000/svg">
                          <path
                            d="M44.5714 0H3.41786C1.53214 0 0 1.55357 0 3.46072V44.5393C0 46.4464 1.53214 48 3.41786 48H44.5714C46.4571 48 48 46.4464 48 44.5393V3.46072C48 1.55357 46.4571 0 44.5714 0ZM14.5071 41.1429H7.39286V18.2357H14.5179V41.1429H14.5071ZM10.95 15.1071C8.66786 15.1071 6.825 13.2536 6.825 10.9821C6.825 8.71072 8.66786 6.85714 10.95 6.85714C13.2214 6.85714 15.075 8.71072 15.075 10.9821C15.075 13.2643 13.2321 15.1071 10.95 15.1071ZM41.175 41.1429H34.0607V30C34.0607 27.3429 34.0071 23.925 30.3643 23.925C26.6571 23.925 26.0893 26.8179 26.0893 29.8071V41.1429H18.975V18.2357H25.8V21.3643H25.8964C26.85 19.5643 29.175 17.6679 32.6357 17.6679C39.8357 17.6679 41.175 22.4143 41.175 28.5857V41.1429Z"
                            fill=""/>
                          <defs>
                            <lineargradient id="paint0_linear" x1="24" y1="0" x2="24" y2="48" gradientunits="userSpaceOnUse">
                              <stop stop-color="#F8B195"/>
                              <stop offset="0.225" stop-color="#F67280"/>
                              <stop offset="0.417708" stop-color="#C06C84"/>
                              <stop offset="0.678125" stop-color="#6C5B7B"/>
                              <stop offset="0.907291" stop-color="#013F59"/>
                            </lineargradient>
                          </defs>
                        </svg>
                      </a>
                    </div>
                    <div class="dev-btn">
                      <button type="submit" onclick="location.href='mailto:rmdev@gmail.com';" target="blank">Connect</button>
                    </div>
                  </div>
                  <div class="imgbox">
                    <img class="profile" src="images\rohan.png" alt="rohan Profile">
                  </div>
                </div>
                <div class="dev-card">
                  <div class="card-bottom">
                    <div class="dev-name">
                      <h3>Rishab</h3>
                    </div>
                    <div class="dev-title">
                      <span>(Web Developer)<span></div>
                        <div class="dev-media">
                          <a class="social" href="https://www.facebook.com/krish.yash.31/">
                            <svg id="logo" viewbox="0 0 48 47" xmlns="http://www.w3.org/2000/svg">
                              <path
                                d="M47.25 24C47.25 11.1562 36.8438 0.75 24 0.75C11.1562 0.75 0.75 11.1562 0.75 24C0.75 35.6044 9.25219 45.2231 20.3672 46.9688V30.7209H14.4609V24H20.3672V18.8775C20.3672 13.0509 23.8359 9.8325 29.1488 9.8325C31.6931 9.8325 34.3538 10.2863 34.3538 10.2863V16.005H31.4212C28.5338 16.005 27.6328 17.7975 27.6328 19.6359V24H34.0809L33.0497 30.7209H27.6328V46.9688C38.7478 45.2231 47.25 35.6044 47.25 24Z"
                                fill=""/>
                              <defs>
                                <lineargradient id="paint0_linear" x1="24" y1="0" x2="24" y2="48" gradientunits="userSpaceOnUse">
                                  <stop stop-color="#F8B195"/>
                                  <stop offset="0.225" stop-color="#F67280"/>
                                  <stop offset="0.417708" stop-color="#C06C84"/>
                                  <stop offset="0.678125" stop-color="#6C5B7B"/>
                                  <stop offset="0.907291" stop-color="#013F59"/>
                                </lineargradient>
                              </defs>
                            </svg>

                          </a>
                          <a class="social" href="https://github.com/Yash-Dave">
                            <svg id="logo" viewbox="0 0 48 48" xmlns="http://www.w3.org/2000/svg">
                              <path
                                d="M16.0548 38.4583C16.0548 38.6518 15.8323 38.8067 15.5516 38.8067C15.2323 38.8357 15.0097 38.6809 15.0097 38.4583C15.0097 38.2647 15.2323 38.1099 15.5129 38.1099C15.8032 38.0809 16.0548 38.2357 16.0548 38.4583ZM13.0452 38.0228C12.9774 38.2163 13.171 38.4389 13.4613 38.497C13.7129 38.5938 14.0032 38.497 14.0613 38.3034C14.1194 38.1099 13.9355 37.8873 13.6452 37.8002C13.3935 37.7325 13.1129 37.8293 13.0452 38.0228ZM17.3226 37.8583C17.0419 37.926 16.8484 38.1099 16.8774 38.3325C16.9065 38.526 17.1581 38.6518 17.4484 38.5841C17.729 38.5163 17.9226 38.3325 17.8935 38.1389C17.8645 37.9551 17.6032 37.8293 17.3226 37.8583ZM23.6903 0.774414C10.2677 0.774414 0 10.9647 0 24.3873C0 35.1196 6.75484 44.3034 16.4032 47.5357C17.6419 47.7583 18.0774 46.9938 18.0774 46.3647C18.0774 45.7647 18.0484 42.4551 18.0484 40.4228C18.0484 40.4228 11.2742 41.8744 9.85161 37.5389C9.85161 37.5389 8.74839 34.7228 7.16129 33.997C7.16129 33.997 4.94516 32.4776 7.31613 32.5067C7.31613 32.5067 9.72581 32.7002 11.0516 35.0034C13.171 38.7389 16.7226 37.6647 18.1065 37.026C18.329 35.4776 18.9581 34.4034 19.6548 33.7647C14.2452 33.1647 8.7871 32.3809 8.7871 23.0712C8.7871 20.4099 9.52258 19.0744 11.071 17.3712C10.8194 16.7422 9.99677 14.1486 11.3226 10.8002C13.3452 10.1712 18 13.4131 18 13.4131C19.9355 12.8712 22.0161 12.5905 24.0774 12.5905C26.1387 12.5905 28.2194 12.8712 30.1548 13.4131C30.1548 13.4131 34.8097 10.1615 36.8323 10.8002C38.1581 14.1583 37.3355 16.7422 37.0839 17.3712C38.6323 19.0841 39.5806 20.4196 39.5806 23.0712C39.5806 32.4099 33.8806 33.1551 28.471 33.7647C29.3613 34.5293 30.1161 35.9809 30.1161 38.2551C30.1161 41.5163 30.0871 45.5518 30.0871 46.3454C30.0871 46.9744 30.5323 47.7389 31.7613 47.5163C41.4387 44.3034 48 35.1196 48 24.3873C48 10.9647 37.1129 0.774414 23.6903 0.774414ZM9.40645 34.1518C9.28064 34.2486 9.30968 34.4712 9.47419 34.6551C9.62903 34.8099 9.85161 34.8776 9.97742 34.7518C10.1032 34.6551 10.0742 34.4325 9.90968 34.2486C9.75484 34.0938 9.53226 34.026 9.40645 34.1518ZM8.36129 33.368C8.29355 33.4938 8.39032 33.6486 8.58387 33.7454C8.73871 33.8422 8.93226 33.8131 9 33.6776C9.06774 33.5518 8.97097 33.397 8.77742 33.3002C8.58387 33.2422 8.42903 33.2712 8.36129 33.368ZM11.4968 36.8131C11.3419 36.9389 11.4 37.2293 11.6226 37.4131C11.8452 37.6357 12.1258 37.6647 12.2516 37.5099C12.3774 37.3841 12.3194 37.0938 12.1258 36.9099C11.9129 36.6873 11.6226 36.6583 11.4968 36.8131ZM10.3935 35.3905C10.2387 35.4873 10.2387 35.7389 10.3935 35.9615C10.5484 36.1841 10.8097 36.2809 10.9355 36.1841C11.0903 36.0583 11.0903 35.8067 10.9355 35.5841C10.8 35.3615 10.5484 35.2647 10.3935 35.3905Z"
                                fill=""/>
                              <defs>
                                <lineargradient id="paint0_linear" x1="24" y1="0" x2="24" y2="48" gradientunits="userSpaceOnUse">
                                  <stop stop-color="#F8B195"/>
                                  <stop offset="0.225" stop-color="#F67280"/>
                                  <stop offset="0.417708" stop-color="#C06C84"/>
                                  <stop offset="0.678125" stop-color="#6C5B7B"/>
                                  <stop offset="0.907291" stop-color="#013F59"/>
                                </lineargradient>
                              </defs>
                            </svg>

                          </a>
                          <a class="social" href="https://www.instagram.com/yash_r_dave/?hl=en">
                            <svg id="logo" viewbox="0 0 48 48" xmlns="http://www.w3.org/2000/svg">
                              <path d="M28.5938 24C28.5938 26.5371 26.5371 28.5938 24 28.5938C21.4629 28.5938 19.4062 26.5371 19.4062 24C19.4062 21.4629 21.4629 19.4062 24 19.4062C26.5371 19.4062 28.5938 21.4629 28.5938 24Z" fill=""/>
                              <path
                                d="M34.7432 15.8723C34.5223 15.2739 34.17 14.7323 33.7123 14.2877C33.2677 13.83 32.7264 13.4777 32.1277 13.2568C31.6421 13.0682 30.9126 12.8438 29.569 12.7826C28.1155 12.7163 27.6797 12.702 24 12.702C20.3199 12.702 19.8842 12.7159 18.431 12.7822C17.0874 12.8438 16.3575 13.0682 15.8723 13.2568C15.2736 13.4777 14.7319 13.83 14.2877 14.2877C13.83 14.7323 13.4777 15.2736 13.2565 15.8723C13.0679 16.3579 12.8434 17.0878 12.7822 18.4314C12.7159 19.8845 12.7017 20.3203 12.7017 24.0004C12.7017 27.6801 12.7159 28.1158 12.7822 29.5693C12.8434 30.913 13.0679 31.6425 13.2565 32.1281C13.4777 32.7268 13.8296 33.2681 14.2874 33.7126C14.7319 34.1704 15.2732 34.5227 15.8719 34.7435C16.3575 34.9325 17.0874 35.157 18.431 35.2181C19.8842 35.2844 20.3196 35.2983 23.9996 35.2983C27.6801 35.2983 28.1158 35.2844 29.5686 35.2181C30.9122 35.157 31.6421 34.9325 32.1277 34.7435C33.3296 34.2799 34.2795 33.33 34.7432 32.1281C34.9318 31.6425 35.1562 30.913 35.2178 29.5693C35.2841 28.1158 35.298 27.6801 35.298 24.0004C35.298 20.3203 35.2841 19.8845 35.2178 18.4314C35.1566 17.0878 34.9321 16.3579 34.7432 15.8723ZM24 31.0767C20.0914 31.0767 16.923 27.9086 16.923 24C16.923 20.0914 20.0914 16.9233 24 16.9233C27.9082 16.9233 31.0767 20.0914 31.0767 24C31.0767 27.9086 27.9082 31.0767 24 31.0767ZM31.3564 18.2974C30.4431 18.2974 29.7026 17.5569 29.7026 16.6436C29.7026 15.7302 30.4431 14.9897 31.3564 14.9897C32.2698 14.9897 33.0103 15.7302 33.0103 16.6436C33.0099 17.5569 32.2698 18.2974 31.3564 18.2974Z"
                                fill=""/>
                              <path
                                d="M24 0C10.7472 0 0 10.7472 0 24C0 37.2528 10.7472 48 24 48C37.2528 48 48 37.2528 48 24C48 10.7472 37.2528 0 24 0ZM37.6981 29.6818C37.6315 31.1488 37.3982 32.1504 37.0576 33.0271C36.3417 34.8783 34.8783 36.3417 33.0271 37.0576C32.1508 37.3982 31.1488 37.6311 29.6821 37.6981C28.2125 37.7651 27.743 37.7812 24.0004 37.7812C20.2573 37.7812 19.7882 37.7651 18.3182 37.6981C16.8516 37.6311 15.8496 37.3982 14.9733 37.0576C14.0533 36.7115 13.2206 36.1692 12.5321 35.4679C11.8312 34.7798 11.2888 33.9467 10.9427 33.0271C10.6022 32.1508 10.3689 31.1488 10.3022 29.6821C10.2345 28.2122 10.2188 27.7427 10.2188 24C10.2188 20.2573 10.2345 19.7878 10.3019 18.3182C10.3685 16.8512 10.6014 15.8496 10.942 14.9729C11.2881 14.0533 11.8308 13.2202 12.5321 12.5321C13.2202 11.8308 14.0533 11.2885 14.9729 10.9424C15.8496 10.6018 16.8512 10.3689 18.3182 10.3019C19.7878 10.2349 20.2573 10.2188 24 10.2188C27.7427 10.2188 28.2122 10.2349 29.6818 10.3022C31.1488 10.3689 32.1504 10.6018 33.0271 10.942C33.9467 11.2881 34.7798 11.8308 35.4683 12.5321C36.1692 13.2206 36.7119 14.0533 37.0576 14.9729C37.3986 15.8496 37.6315 16.8512 37.6985 18.3182C37.7655 19.7878 37.7812 20.2573 37.7812 24C37.7812 27.7427 37.7655 28.2122 37.6981 29.6818Z"
                                fill=""/>
                              <defs>
                                <lineargradient id="paint0_linear" x1="24" y1="0" x2="24" y2="48" gradientunits="userSpaceOnUse">
                                  <stop stop-color="#F8B195"/>
                                  <stop offset="0.225" stop-color="#F67280"/>
                                  <stop offset="0.417708" stop-color="#C06C84"/>
                                  <stop offset="0.678125" stop-color="#6C5B7B"/>
                                  <stop offset="0.907291" stop-color="#013F59"/>
                                </lineargradient>
                              </defs>
                            </svg>

                          </a>
                          <a class="social" href="https://in.linkedin.com/in/yash-dave-408976199?trk=people-guest_people_search-card">
                            <svg id="logo" viewbox="0 0 48 48" xmlns="http://www.w3.org/2000/svg">
                              <path
                                d="M44.5714 0H3.41786C1.53214 0 0 1.55357 0 3.46072V44.5393C0 46.4464 1.53214 48 3.41786 48H44.5714C46.4571 48 48 46.4464 48 44.5393V3.46072C48 1.55357 46.4571 0 44.5714 0ZM14.5071 41.1429H7.39286V18.2357H14.5179V41.1429H14.5071ZM10.95 15.1071C8.66786 15.1071 6.825 13.2536 6.825 10.9821C6.825 8.71072 8.66786 6.85714 10.95 6.85714C13.2214 6.85714 15.075 8.71072 15.075 10.9821C15.075 13.2643 13.2321 15.1071 10.95 15.1071ZM41.175 41.1429H34.0607V30C34.0607 27.3429 34.0071 23.925 30.3643 23.925C26.6571 23.925 26.0893 26.8179 26.0893 29.8071V41.1429H18.975V18.2357H25.8V21.3643H25.8964C26.85 19.5643 29.175 17.6679 32.6357 17.6679C39.8357 17.6679 41.175 22.4143 41.175 28.5857V41.1429Z"
                                fill=""/>
                              <defs>
                                <lineargradient id="paint0_linear" x1="24" y1="0" x2="24" y2="48" gradientunits="userSpaceOnUse">
                                  <stop stop-color="#F8B195"/>
                                  <stop offset="0.225" stop-color="#F67280"/>
                                  <stop offset="0.417708" stop-color="#C06C84"/>
                                  <stop offset="0.678125" stop-color="#6C5B7B"/>
                                  <stop offset="0.907291" stop-color="#013F59"/>
                                </lineargradient>
                              </defs>
                            </svg>
                          </a>
                        </div>
                        <div class="dev-btn">
                          <button type="submit" onclick="location.href='mailto:daveyashrakesh@gmail.com';" target="blank">Connect</button>
                        </div>
                      </div>
                      <div class="imgbox">
                        <img class="profile" src="images\yash.png" alt="yash Profile">
                      </div>
                    </div>
                    <div class="dev-card">
                      <div class="card-bottom">
                        <div class="dev-name">
                          <h3>Hemanth</h3>
                        </div>
                        <div class="dev-title">
                          <span>(Web Developer)<span></div>
                            <div class="dev-media">
                              <a class="social" href="https://www.facebook.com/profile.php?id=100004412952565">
                                <svg id="logo" viewbox="0 0 48 47" xmlns="http://www.w3.org/2000/svg">
                                  <path
                                    d="M47.25 24C47.25 11.1562 36.8438 0.75 24 0.75C11.1562 0.75 0.75 11.1562 0.75 24C0.75 35.6044 9.25219 45.2231 20.3672 46.9688V30.7209H14.4609V24H20.3672V18.8775C20.3672 13.0509 23.8359 9.8325 29.1488 9.8325C31.6931 9.8325 34.3538 10.2863 34.3538 10.2863V16.005H31.4212C28.5338 16.005 27.6328 17.7975 27.6328 19.6359V24H34.0809L33.0497 30.7209H27.6328V46.9688C38.7478 45.2231 47.25 35.6044 47.25 24Z"
                                    fill=""/>
                                  <defs>
                                    <lineargradient id="paint0_linear" x1="24" y1="0" x2="24" y2="48" gradientunits="userSpaceOnUse">
                                      <stop stop-color="#F8B195"/>
                                      <stop offset="0.225" stop-color="#F67280"/>
                                      <stop offset="0.417708" stop-color="#C06C84"/>
                                      <stop offset="0.678125" stop-color="#6C5B7B"/>
                                      <stop offset="0.907291" stop-color="#013F59"/>
                                    </lineargradient>
                                  </defs>
                                </svg>

                              </a>
                              <a class="social" href="https://github.com/DhruvilShah22">
                                <svg id="logo" viewbox="0 0 48 48" xmlns="http://www.w3.org/2000/svg">
                                  <path
                                    d="M16.0548 38.4583C16.0548 38.6518 15.8323 38.8067 15.5516 38.8067C15.2323 38.8357 15.0097 38.6809 15.0097 38.4583C15.0097 38.2647 15.2323 38.1099 15.5129 38.1099C15.8032 38.0809 16.0548 38.2357 16.0548 38.4583ZM13.0452 38.0228C12.9774 38.2163 13.171 38.4389 13.4613 38.497C13.7129 38.5938 14.0032 38.497 14.0613 38.3034C14.1194 38.1099 13.9355 37.8873 13.6452 37.8002C13.3935 37.7325 13.1129 37.8293 13.0452 38.0228ZM17.3226 37.8583C17.0419 37.926 16.8484 38.1099 16.8774 38.3325C16.9065 38.526 17.1581 38.6518 17.4484 38.5841C17.729 38.5163 17.9226 38.3325 17.8935 38.1389C17.8645 37.9551 17.6032 37.8293 17.3226 37.8583ZM23.6903 0.774414C10.2677 0.774414 0 10.9647 0 24.3873C0 35.1196 6.75484 44.3034 16.4032 47.5357C17.6419 47.7583 18.0774 46.9938 18.0774 46.3647C18.0774 45.7647 18.0484 42.4551 18.0484 40.4228C18.0484 40.4228 11.2742 41.8744 9.85161 37.5389C9.85161 37.5389 8.74839 34.7228 7.16129 33.997C7.16129 33.997 4.94516 32.4776 7.31613 32.5067C7.31613 32.5067 9.72581 32.7002 11.0516 35.0034C13.171 38.7389 16.7226 37.6647 18.1065 37.026C18.329 35.4776 18.9581 34.4034 19.6548 33.7647C14.2452 33.1647 8.7871 32.3809 8.7871 23.0712C8.7871 20.4099 9.52258 19.0744 11.071 17.3712C10.8194 16.7422 9.99677 14.1486 11.3226 10.8002C13.3452 10.1712 18 13.4131 18 13.4131C19.9355 12.8712 22.0161 12.5905 24.0774 12.5905C26.1387 12.5905 28.2194 12.8712 30.1548 13.4131C30.1548 13.4131 34.8097 10.1615 36.8323 10.8002C38.1581 14.1583 37.3355 16.7422 37.0839 17.3712C38.6323 19.0841 39.5806 20.4196 39.5806 23.0712C39.5806 32.4099 33.8806 33.1551 28.471 33.7647C29.3613 34.5293 30.1161 35.9809 30.1161 38.2551C30.1161 41.5163 30.0871 45.5518 30.0871 46.3454C30.0871 46.9744 30.5323 47.7389 31.7613 47.5163C41.4387 44.3034 48 35.1196 48 24.3873C48 10.9647 37.1129 0.774414 23.6903 0.774414ZM9.40645 34.1518C9.28064 34.2486 9.30968 34.4712 9.47419 34.6551C9.62903 34.8099 9.85161 34.8776 9.97742 34.7518C10.1032 34.6551 10.0742 34.4325 9.90968 34.2486C9.75484 34.0938 9.53226 34.026 9.40645 34.1518ZM8.36129 33.368C8.29355 33.4938 8.39032 33.6486 8.58387 33.7454C8.73871 33.8422 8.93226 33.8131 9 33.6776C9.06774 33.5518 8.97097 33.397 8.77742 33.3002C8.58387 33.2422 8.42903 33.2712 8.36129 33.368ZM11.4968 36.8131C11.3419 36.9389 11.4 37.2293 11.6226 37.4131C11.8452 37.6357 12.1258 37.6647 12.2516 37.5099C12.3774 37.3841 12.3194 37.0938 12.1258 36.9099C11.9129 36.6873 11.6226 36.6583 11.4968 36.8131ZM10.3935 35.3905C10.2387 35.4873 10.2387 35.7389 10.3935 35.9615C10.5484 36.1841 10.8097 36.2809 10.9355 36.1841C11.0903 36.0583 11.0903 35.8067 10.9355 35.5841C10.8 35.3615 10.5484 35.2647 10.3935 35.3905Z"
                                    fill=""/>
                                  <defs>
                                    <lineargradient id="paint0_linear" x1="24" y1="0" x2="24" y2="48" gradientunits="userSpaceOnUse">
                                      <stop stop-color="#F8B195"/>
                                      <stop offset="0.225" stop-color="#F67280"/>
                                      <stop offset="0.417708" stop-color="#C06C84"/>
                                      <stop offset="0.678125" stop-color="#6C5B7B"/>
                                      <stop offset="0.907291" stop-color="#013F59"/>
                                    </lineargradient>
                                  </defs>
                                </svg>

                              </a>
                              <a class="social" href="https://www.instagram.com/d_rulezzz/">
                                <svg id="logo" viewbox="0 0 48 48" xmlns="http://www.w3.org/2000/svg">
                                  <path d="M28.5938 24C28.5938 26.5371 26.5371 28.5938 24 28.5938C21.4629 28.5938 19.4062 26.5371 19.4062 24C19.4062 21.4629 21.4629 19.4062 24 19.4062C26.5371 19.4062 28.5938 21.4629 28.5938 24Z" fill=""/>
                                  <path
                                    d="M34.7432 15.8723C34.5223 15.2739 34.17 14.7323 33.7123 14.2877C33.2677 13.83 32.7264 13.4777 32.1277 13.2568C31.6421 13.0682 30.9126 12.8438 29.569 12.7826C28.1155 12.7163 27.6797 12.702 24 12.702C20.3199 12.702 19.8842 12.7159 18.431 12.7822C17.0874 12.8438 16.3575 13.0682 15.8723 13.2568C15.2736 13.4777 14.7319 13.83 14.2877 14.2877C13.83 14.7323 13.4777 15.2736 13.2565 15.8723C13.0679 16.3579 12.8434 17.0878 12.7822 18.4314C12.7159 19.8845 12.7017 20.3203 12.7017 24.0004C12.7017 27.6801 12.7159 28.1158 12.7822 29.5693C12.8434 30.913 13.0679 31.6425 13.2565 32.1281C13.4777 32.7268 13.8296 33.2681 14.2874 33.7126C14.7319 34.1704 15.2732 34.5227 15.8719 34.7435C16.3575 34.9325 17.0874 35.157 18.431 35.2181C19.8842 35.2844 20.3196 35.2983 23.9996 35.2983C27.6801 35.2983 28.1158 35.2844 29.5686 35.2181C30.9122 35.157 31.6421 34.9325 32.1277 34.7435C33.3296 34.2799 34.2795 33.33 34.7432 32.1281C34.9318 31.6425 35.1562 30.913 35.2178 29.5693C35.2841 28.1158 35.298 27.6801 35.298 24.0004C35.298 20.3203 35.2841 19.8845 35.2178 18.4314C35.1566 17.0878 34.9321 16.3579 34.7432 15.8723ZM24 31.0767C20.0914 31.0767 16.923 27.9086 16.923 24C16.923 20.0914 20.0914 16.9233 24 16.9233C27.9082 16.9233 31.0767 20.0914 31.0767 24C31.0767 27.9086 27.9082 31.0767 24 31.0767ZM31.3564 18.2974C30.4431 18.2974 29.7026 17.5569 29.7026 16.6436C29.7026 15.7302 30.4431 14.9897 31.3564 14.9897C32.2698 14.9897 33.0103 15.7302 33.0103 16.6436C33.0099 17.5569 32.2698 18.2974 31.3564 18.2974Z"
                                    fill=""/>
                                  <path
                                    d="M24 0C10.7472 0 0 10.7472 0 24C0 37.2528 10.7472 48 24 48C37.2528 48 48 37.2528 48 24C48 10.7472 37.2528 0 24 0ZM37.6981 29.6818C37.6315 31.1488 37.3982 32.1504 37.0576 33.0271C36.3417 34.8783 34.8783 36.3417 33.0271 37.0576C32.1508 37.3982 31.1488 37.6311 29.6821 37.6981C28.2125 37.7651 27.743 37.7812 24.0004 37.7812C20.2573 37.7812 19.7882 37.7651 18.3182 37.6981C16.8516 37.6311 15.8496 37.3982 14.9733 37.0576C14.0533 36.7115 13.2206 36.1692 12.5321 35.4679C11.8312 34.7798 11.2888 33.9467 10.9427 33.0271C10.6022 32.1508 10.3689 31.1488 10.3022 29.6821C10.2345 28.2122 10.2188 27.7427 10.2188 24C10.2188 20.2573 10.2345 19.7878 10.3019 18.3182C10.3685 16.8512 10.6014 15.8496 10.942 14.9729C11.2881 14.0533 11.8308 13.2202 12.5321 12.5321C13.2202 11.8308 14.0533 11.2885 14.9729 10.9424C15.8496 10.6018 16.8512 10.3689 18.3182 10.3019C19.7878 10.2349 20.2573 10.2188 24 10.2188C27.7427 10.2188 28.2122 10.2349 29.6818 10.3022C31.1488 10.3689 32.1504 10.6018 33.0271 10.942C33.9467 11.2881 34.7798 11.8308 35.4683 12.5321C36.1692 13.2206 36.7119 14.0533 37.0576 14.9729C37.3986 15.8496 37.6315 16.8512 37.6985 18.3182C37.7655 19.7878 37.7812 20.2573 37.7812 24C37.7812 27.7427 37.7655 28.2122 37.6981 29.6818Z"
                                    fill=""/>
                                  <defs>
                                    <lineargradient id="paint0_linear" x1="24" y1="0" x2="24" y2="48" gradientunits="userSpaceOnUse">
                                      <stop stop-color="#F8B195"/>
                                      <stop offset="0.225" stop-color="#F67280"/>
                                      <stop offset="0.417708" stop-color="#C06C84"/>
                                      <stop offset="0.678125" stop-color="#6C5B7B"/>
                                      <stop offset="0.907291" stop-color="#013F59"/>
                                    </lineargradient>
                                  </defs>
                                </svg>

                              </a>
                              <a class="social" href="https://www.linkedin.com/in/dhruvil-shah-502b5a186/">
                                <svg id="logo" viewbox="0 0 48 48" xmlns="http://www.w3.org/2000/svg">
                                  <path
                                    d="M44.5714 0H3.41786C1.53214 0 0 1.55357 0 3.46072V44.5393C0 46.4464 1.53214 48 3.41786 48H44.5714C46.4571 48 48 46.4464 48 44.5393V3.46072C48 1.55357 46.4571 0 44.5714 0ZM14.5071 41.1429H7.39286V18.2357H14.5179V41.1429H14.5071ZM10.95 15.1071C8.66786 15.1071 6.825 13.2536 6.825 10.9821C6.825 8.71072 8.66786 6.85714 10.95 6.85714C13.2214 6.85714 15.075 8.71072 15.075 10.9821C15.075 13.2643 13.2321 15.1071 10.95 15.1071ZM41.175 41.1429H34.0607V30C34.0607 27.3429 34.0071 23.925 30.3643 23.925C26.6571 23.925 26.0893 26.8179 26.0893 29.8071V41.1429H18.975V18.2357H25.8V21.3643H25.8964C26.85 19.5643 29.175 17.6679 32.6357 17.6679C39.8357 17.6679 41.175 22.4143 41.175 28.5857V41.1429Z"
                                    fill=""/>
                                  <defs>
                                    <lineargradient id="paint0_linear" x1="24" y1="0" x2="24" y2="48" gradientunits="userSpaceOnUse">
                                      <stop stop-color="#F8B195"/>
                                      <stop offset="0.225" stop-color="#F67280"/>
                                      <stop offset="0.417708" stop-color="#C06C84"/>
                                      <stop offset="0.678125" stop-color="#6C5B7B"/>
                                      <stop offset="0.907291" stop-color="#013F59"/>
                                    </lineargradient>
                                  </defs>
                                </svg>
                              </a>
                            </div>
                            <div class="dev-btn">
                              <button type="submit" onclick="location.href='mailto:contactdhruvil22@gmail.com';" target="blank">Connect</button>
                            </div>
                          </div>
                          <div class="imgbox">
                            <img class="profile" src="images\dhruvil.png" alt="Dhruvil Profile">
                          </div>
                        </div>
                      </div>
                      <div class="swiper-container">
                        <div class="swiper-wrapper">
                          <div class="swiper-slide">
                            <div class="dev-card">
                              <div class="card-bottom">
                                <div class="dev-name">
                                  <h3>Vivek Hotti</h3>
                                </div>
                                <div class="dev-title">
                                  <span>(Web Developer)<span></div>
                                    <div class="dev-media">
                                      <a class="social" href="https://www.facebook.com/vivek.hotti.9/">
                                        <svg id="logo" viewbox="0 0 48 47" xmlns="http://www.w3.org/2000/svg">
                                          <path
                                            d="M47.25 24C47.25 11.1562 36.8438 0.75 24 0.75C11.1562 0.75 0.75 11.1562 0.75 24C0.75 35.6044 9.25219 45.2231 20.3672 46.9688V30.7209H14.4609V24H20.3672V18.8775C20.3672 13.0509 23.8359 9.8325 29.1488 9.8325C31.6931 9.8325 34.3538 10.2863 34.3538 10.2863V16.005H31.4212C28.5338 16.005 27.6328 17.7975 27.6328 19.6359V24H34.0809L33.0497 30.7209H27.6328V46.9688C38.7478 45.2231 47.25 35.6044 47.25 24Z"
                                            fill="#013F59"/>
                                          <defs>
                                            <lineargradient id="paint0_linear" x1="24" y1="0" x2="24" y2="48" gradientunits="userSpaceOnUse">
                                              <stop stop-color="#F8B195"/>
                                              <stop offset="0.225" stop-color="#F67280"/>
                                              <stop offset="0.417708" stop-color="#C06C84"/>
                                              <stop offset="0.678125" stop-color="#6C5B7B"/>
                                              <stop offset="0.907291" stop-color="#013F59"/>
                                            </lineargradient>
                                          </defs>
                                        </svg>

                                      </a>
                                      <a class="social" href="https://github.com/Vivek-Hotti">
                                        <svg id="logo" viewbox="0 0 48 48" xmlns="http://www.w3.org/2000/svg">
                                          <path
                                            d="M16.0548 38.4583C16.0548 38.6518 15.8323 38.8067 15.5516 38.8067C15.2323 38.8357 15.0097 38.6809 15.0097 38.4583C15.0097 38.2647 15.2323 38.1099 15.5129 38.1099C15.8032 38.0809 16.0548 38.2357 16.0548 38.4583ZM13.0452 38.0228C12.9774 38.2163 13.171 38.4389 13.4613 38.497C13.7129 38.5938 14.0032 38.497 14.0613 38.3034C14.1194 38.1099 13.9355 37.8873 13.6452 37.8002C13.3935 37.7325 13.1129 37.8293 13.0452 38.0228ZM17.3226 37.8583C17.0419 37.926 16.8484 38.1099 16.8774 38.3325C16.9065 38.526 17.1581 38.6518 17.4484 38.5841C17.729 38.5163 17.9226 38.3325 17.8935 38.1389C17.8645 37.9551 17.6032 37.8293 17.3226 37.8583ZM23.6903 0.774414C10.2677 0.774414 0 10.9647 0 24.3873C0 35.1196 6.75484 44.3034 16.4032 47.5357C17.6419 47.7583 18.0774 46.9938 18.0774 46.3647C18.0774 45.7647 18.0484 42.4551 18.0484 40.4228C18.0484 40.4228 11.2742 41.8744 9.85161 37.5389C9.85161 37.5389 8.74839 34.7228 7.16129 33.997C7.16129 33.997 4.94516 32.4776 7.31613 32.5067C7.31613 32.5067 9.72581 32.7002 11.0516 35.0034C13.171 38.7389 16.7226 37.6647 18.1065 37.026C18.329 35.4776 18.9581 34.4034 19.6548 33.7647C14.2452 33.1647 8.7871 32.3809 8.7871 23.0712C8.7871 20.4099 9.52258 19.0744 11.071 17.3712C10.8194 16.7422 9.99677 14.1486 11.3226 10.8002C13.3452 10.1712 18 13.4131 18 13.4131C19.9355 12.8712 22.0161 12.5905 24.0774 12.5905C26.1387 12.5905 28.2194 12.8712 30.1548 13.4131C30.1548 13.4131 34.8097 10.1615 36.8323 10.8002C38.1581 14.1583 37.3355 16.7422 37.0839 17.3712C38.6323 19.0841 39.5806 20.4196 39.5806 23.0712C39.5806 32.4099 33.8806 33.1551 28.471 33.7647C29.3613 34.5293 30.1161 35.9809 30.1161 38.2551C30.1161 41.5163 30.0871 45.5518 30.0871 46.3454C30.0871 46.9744 30.5323 47.7389 31.7613 47.5163C41.4387 44.3034 48 35.1196 48 24.3873C48 10.9647 37.1129 0.774414 23.6903 0.774414ZM9.40645 34.1518C9.28064 34.2486 9.30968 34.4712 9.47419 34.6551C9.62903 34.8099 9.85161 34.8776 9.97742 34.7518C10.1032 34.6551 10.0742 34.4325 9.90968 34.2486C9.75484 34.0938 9.53226 34.026 9.40645 34.1518ZM8.36129 33.368C8.29355 33.4938 8.39032 33.6486 8.58387 33.7454C8.73871 33.8422 8.93226 33.8131 9 33.6776C9.06774 33.5518 8.97097 33.397 8.77742 33.3002C8.58387 33.2422 8.42903 33.2712 8.36129 33.368ZM11.4968 36.8131C11.3419 36.9389 11.4 37.2293 11.6226 37.4131C11.8452 37.6357 12.1258 37.6647 12.2516 37.5099C12.3774 37.3841 12.3194 37.0938 12.1258 36.9099C11.9129 36.6873 11.6226 36.6583 11.4968 36.8131ZM10.3935 35.3905C10.2387 35.4873 10.2387 35.7389 10.3935 35.9615C10.5484 36.1841 10.8097 36.2809 10.9355 36.1841C11.0903 36.0583 11.0903 35.8067 10.9355 35.5841C10.8 35.3615 10.5484 35.2647 10.3935 35.3905Z"
                                            fill="#013F59"/>
                                          <defs>
                                            <lineargradient id="paint0_linear" x1="24" y1="0" x2="24" y2="48" gradientunits="userSpaceOnUse">
                                              <stop stop-color="#F8B195"/>
                                              <stop offset="0.225" stop-color="#F67280"/>
                                              <stop offset="0.417708" stop-color="#C06C84"/>
                                              <stop offset="0.678125" stop-color="#6C5B7B"/>
                                              <stop offset="0.907291" stop-color="#013F59"/>
                                            </lineargradient>
                                          </defs>
                                        </svg>

                                      </a>
                                      <a class="social" href="https://www.instagram.com/vivek_hotti/">
                                        <svg id="logo" viewbox="0 0 48 48" xmlns="http://www.w3.org/2000/svg">
                                          <path d="M28.5938 24C28.5938 26.5371 26.5371 28.5938 24 28.5938C21.4629 28.5938 19.4062 26.5371 19.4062 24C19.4062 21.4629 21.4629 19.4062 24 19.4062C26.5371 19.4062 28.5938 21.4629 28.5938 24Z" fill=""/>
                                          <path
                                            d="M34.7432 15.8723C34.5223 15.2739 34.17 14.7323 33.7123 14.2877C33.2677 13.83 32.7264 13.4777 32.1277 13.2568C31.6421 13.0682 30.9126 12.8438 29.569 12.7826C28.1155 12.7163 27.6797 12.702 24 12.702C20.3199 12.702 19.8842 12.7159 18.431 12.7822C17.0874 12.8438 16.3575 13.0682 15.8723 13.2568C15.2736 13.4777 14.7319 13.83 14.2877 14.2877C13.83 14.7323 13.4777 15.2736 13.2565 15.8723C13.0679 16.3579 12.8434 17.0878 12.7822 18.4314C12.7159 19.8845 12.7017 20.3203 12.7017 24.0004C12.7017 27.6801 12.7159 28.1158 12.7822 29.5693C12.8434 30.913 13.0679 31.6425 13.2565 32.1281C13.4777 32.7268 13.8296 33.2681 14.2874 33.7126C14.7319 34.1704 15.2732 34.5227 15.8719 34.7435C16.3575 34.9325 17.0874 35.157 18.431 35.2181C19.8842 35.2844 20.3196 35.2983 23.9996 35.2983C27.6801 35.2983 28.1158 35.2844 29.5686 35.2181C30.9122 35.157 31.6421 34.9325 32.1277 34.7435C33.3296 34.2799 34.2795 33.33 34.7432 32.1281C34.9318 31.6425 35.1562 30.913 35.2178 29.5693C35.2841 28.1158 35.298 27.6801 35.298 24.0004C35.298 20.3203 35.2841 19.8845 35.2178 18.4314C35.1566 17.0878 34.9321 16.3579 34.7432 15.8723ZM24 31.0767C20.0914 31.0767 16.923 27.9086 16.923 24C16.923 20.0914 20.0914 16.9233 24 16.9233C27.9082 16.9233 31.0767 20.0914 31.0767 24C31.0767 27.9086 27.9082 31.0767 24 31.0767ZM31.3564 18.2974C30.4431 18.2974 29.7026 17.5569 29.7026 16.6436C29.7026 15.7302 30.4431 14.9897 31.3564 14.9897C32.2698 14.9897 33.0103 15.7302 33.0103 16.6436C33.0099 17.5569 32.2698 18.2974 31.3564 18.2974Z"
                                            fill="#013F59"/>
                                          <path
                                            d="M24 0C10.7472 0 0 10.7472 0 24C0 37.2528 10.7472 48 24 48C37.2528 48 48 37.2528 48 24C48 10.7472 37.2528 0 24 0ZM37.6981 29.6818C37.6315 31.1488 37.3982 32.1504 37.0576 33.0271C36.3417 34.8783 34.8783 36.3417 33.0271 37.0576C32.1508 37.3982 31.1488 37.6311 29.6821 37.6981C28.2125 37.7651 27.743 37.7812 24.0004 37.7812C20.2573 37.7812 19.7882 37.7651 18.3182 37.6981C16.8516 37.6311 15.8496 37.3982 14.9733 37.0576C14.0533 36.7115 13.2206 36.1692 12.5321 35.4679C11.8312 34.7798 11.2888 33.9467 10.9427 33.0271C10.6022 32.1508 10.3689 31.1488 10.3022 29.6821C10.2345 28.2122 10.2188 27.7427 10.2188 24C10.2188 20.2573 10.2345 19.7878 10.3019 18.3182C10.3685 16.8512 10.6014 15.8496 10.942 14.9729C11.2881 14.0533 11.8308 13.2202 12.5321 12.5321C13.2202 11.8308 14.0533 11.2885 14.9729 10.9424C15.8496 10.6018 16.8512 10.3689 18.3182 10.3019C19.7878 10.2349 20.2573 10.2188 24 10.2188C27.7427 10.2188 28.2122 10.2349 29.6818 10.3022C31.1488 10.3689 32.1504 10.6018 33.0271 10.942C33.9467 11.2881 34.7798 11.8308 35.4683 12.5321C36.1692 13.2206 36.7119 14.0533 37.0576 14.9729C37.3986 15.8496 37.6315 16.8512 37.6985 18.3182C37.7655 19.7878 37.7812 20.2573 37.7812 24C37.7812 27.7427 37.7655 28.2122 37.6981 29.6818Z"
                                            fill="#013F59"/>
                                          <defs>
                                            <lineargradient id="paint0_linear" x1="24" y1="0" x2="24" y2="48" gradientunits="userSpaceOnUse">
