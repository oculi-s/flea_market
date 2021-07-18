<html>

<head>
  <link rel='stylesheet' href='./css/main.css'>
  <link rel='stylesheet' href='./css/index.css'>
</head>

<body>
  <header>
    <span class='_shrink _sleft'>
      <a id='title' href='./index.html'>FLEA MARKET</a>
    </span>
  </header>
  <div>
    <article>
      <div class='_left'>
        <div class='_wrap'>
          <span class='_shrink'>Already have an account?</span>
          <span style='font-size:10pt;'>Login now and enjoy Flea Market!</span>
          <button class='_login' onclick="location.href='./login.html'">Login Now</button>
        </div>
      </div>
      <div class='_right'>
        <div class='_wrap'>
          <span class='_shrink'>CREATE AN ACCOUNT</span>
          <div>
            <label>
              <input id='_seller' type=checkbox> Seller&nbsp;&nbsp;
            </label>
            <label>
              <input id='_buyer' type=checkbox> Buyer
            </label>
            <div class='_sb _deny'>*Please select user type</div>
          </div>

          <input id='_id' type=text placeholder='ID'>
          <div class='_id _deny'>*Please enter your ID</div>
          <div class='_dup _need'>*Duplicate needed</div>
          <div class='_dup _deny'>*Duplicate failed</div>
          <div class='_dup _accept'>*Duplicate succeed</div>

          <button class='_dup' onclick=duplicate()>Duplicate</button>
          <input id='_ml' type=text placeholder='Email Address'>
          <div class='_ml _deny'>*Invalid Email</div>
          <input id='_pw' type=password placeholder='Password'>
          <div class='_pw _main _deny'>*Please enter your Password</div>
          <input id='_cp' type=password placeholder='Confirm Password'>
          <div class='_cp _deny'>*Confirmation denied</div>
          <button class='_register' onclick=main()>REGISTER</button>
        </div>
      </div>
    </article>
  </div>
  <footer>
    <span>
      copyright @ 2020
    </span>
  </footer>

  <script src="https://www.gstatic.com/firebasejs/8.2.1/firebase-app.js"></script>
  <script src="https://www.gstatic.com/firebasejs/8.2.1/firebase-analytics.js"></script>
  <script src="https://www.gstatic.com/firebasejs/8.2.1/firebase-auth.js"></script>
  <script src="https://www.gstatic.com/firebasejs/8.2.1/firebase-firestore.js"></script>
  <script type=text/javascript src=./js/firebase.js></script>
  <script type=text/javascript src=./js/main.js></script>
  <script type=text/javascript src=./js/index.js></script>

</body>

</html>
