# password-generator
password generator creates random passwords by shaft tech

<!DOCTYPE html>
<html>
  <head>
    <title>Password Generator By shaftteach</title>
    <meta name="author" content="alihasan.ml" />
    <meta
      name="keywords"
      content="HTML, CSS, JavaScript, alihasn, dev alihasan, arnobhasan, m. ali hasan"
    />
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link
      rel="stylesheet"
      href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css"
    />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="container">
      <div class="row">
        <div class="col-sm-12 col-md-8 offset-md-2 col-lg-6 offset-lg-3">
          <h1 class="text-center mb-5">Password Generator</h1>
          <div class="form-group">
            <label for="password-length">Password Length:</label>
            <input
              type="number"
              class="form-control"
              id="password-length"
              min="8"
              max="64"
              value="12"
              style="border-radius: 10px"
            />
            <small id="password-length-help" class="form-text text-muted"
              >Choose a length between 8 and 64 characters.</small
            >
          </div>
          <div class="form-group">
            <label for="password-display">Password:</label>
            <div class="input-group">
              <input
                type="text"
                class="form-control"
                id="password-display"
                readonly
                style="border-radius: 10px 0 0 10px"
              />
              <div class="input-group-append">
                <button
                  class="btn btn-primary"
                  id="copy-button"
                  type="button"
                  style="border-radius: 0 10px 10px 0"
                >
                  Copy
                </button>
              </div>
            </div>
            <small id="password-display-help" class="form-text text-muted"
              >Click "Generate Password" to generate a new password.</small
            >
          </div>
          <button
            href="#"
            class="bton btn btn-lg btn-block mb-5"
            id="generate-button"
          >
            Generate Password
          </button>


          
          BY SHAFTTEACH
        </div>
      </div>
    </div>
    <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js"></script>
    <script src="script.js"></script>
  </body>
</html>

 
