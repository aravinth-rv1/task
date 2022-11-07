<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <title>example</title>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <link
      rel="stylesheet"
      href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.1/dist/css/bootstrap.min.css" />
    <script src="https://cdn.jsdelivr.net/npm/jquery@3.6.0/dist/jquery.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.1/dist/js/bootstrap.bundle.min.js"></script>
    <script src="index.js"></script>
  </head>
  <body>
    <div class="container-fluid d-flex justify-content-center flex-column mb-5">
      <h1 class="mt-1 ml-1">Instagram</h1>
      <div class="mt-1 ml-1 width-50 d-flex flex-row" style="width: 18rem">
        <input
          type="text"
          class="form-control"
          placeholder="Phone no,username or email"
          id="imageUrl" />
      </div>
      <div class="mt-1 ml-1 width-50 d-flex flex-row" style="width: 18rem">
        <input
          type="text"
          class="form-control"
          placeholder="password"
          id="imageUrl" />
        </div>
        <div class="mt-1 ml-5 width-50 d-flex flex-row" style="width: 5rem">
          <button class="btn btn-primary ml-2" type="button" id="addImage">
      <span>Login</span>
    </button>
   </div>
   <div class="ml-5 mt-2">
   <p>OR</p>
   <button class="btn btn-primary">Log in with Google</button>
   <P>Forgot password?</P>
</div>
<div class="text-center">
      <div id="imageContainer">
        <div class="card mt-1 ml-1" style="width: 18rem">
          <img
            src="https://images.unsplash.com/photo-1661956602153-23384936a1d3?ixlib=rb-4.0.3&ixid=MnwxMjA3fDF8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=870&q=80"
            class="card-img-top"
            alt="..." />
          <div
            class="card-body d-flex justify-content-between align-items-center">
            <a
              class="card-title"
              download="image.jpg"
              href="https://images.unsplash.com/photo-1661956602153-23384936a1d3?ixlib=rb-4.0.3&ixid=MnwxMjA3fDF8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=870&q=80"
              >Download</a>
            
            <button class="btn btn-primary" id="btn"><p>
              likes <span 
              id="display">0</span> 
          </p></button>
          <script type="text/javascript">
            var click = 0;
            var btn = document.getElementById("btn");
            var disp = document.getElementById("display");
      
            btn.onclick = function () {
                click++;
                disp.innerHTML = click;
            }
        </script>
       </div>
          </div>
        </div>
      </div>
    </div>
</body>
</html>
