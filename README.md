<!DOCTYPE html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no" />

    <!-- Bootstrap CSS -->
    <link
      rel="stylesheet"
      href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css"
      integrity="sha384-9aIt2nRpC12Uk9gS9baDl411NQApFmC26EwAOH8WgZl5MYYxFfc+NcPb1dKGj7Sk"
      crossorigin="anonymous"
    />

    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap" rel="stylesheet">

    <title>Hello, world!</title>
    <style type="text/css">
            #survey-form{
              background-color: rgba(27, 27, 50, 0.8);
              border-radius: 0.25rem;
              margin-top: 0em;
            }
            #number-label{
               display: block;
          width: 95%;
          height: 2.375rem;
          padding: 0.375rem 0.75rem;
          color: #495057;
          background-color: #fff;
          background-clip: padding-box;
          border: 1px solid #ced4da;
          border-radius: 0.25rem;
          transition: border-color 0.15s
          font-size:18px;
          font-family: 'Poppins', sans-serif;

            }
            #email-label{
               display: block;
          width: 95%;
          height: 2.375rem;
          padding: 0.375rem 0.75rem;
          color: #495057;
          background-color: #fff;
          background-clip: padding-box;
          border: 1px solid #ced4da;
          border-radius: 0.25rem;
          transition: border-color 0.15s
          font-family: 'Poppins', sans-serif;
          font-size: 18px;
            }
            #form-control{
               display: block;
          width: 95%;
          height: 2.375rem;
          padding: 0.375rem 0.75rem;
          color: #495057;
          background-color: #fff;
          background-clip: padding-box;
          border: 1px solid #ced4da;
          border-radius: 0.25rem;
          transition: border-color 0.15s
            }
            #dropdown{
               display: block;
          width: 95%;
          height: 2.375rem;
          padding: 0.375rem 0.75rem;
          color: #495057;
          background-color: #fff;
          background-clip: padding-box;
          border: 1px solid #ced4da;
          border-radius: 0.25rem;
          transition: border-color 0.15s
            }
            #features{
               display: block;
          width: 95%;
          height: 2.375rem;
          padding: 0.375rem 0.75rem;
          color: #495057;
          background-color: #fff;
          background-clip: padding-box;
          border: 1px solid #ced4da;
          border-radius: 0.25rem;
          transition: border-color 0.15s
            }


            #button{
              width: 60%
              text-align: center;
              border-radius: 1rem;
            }
            .container{
                  max-width: 720px;
                  width: 100%;
            }

      .bg-survey {
          background-color: rgba(58, 58, 158, 0.8);
          padding: 8rem 0;
      }

            .form-control{
              display: block;
          width: 95%;
          height: 2.375rem;
          padding: 0.375rem 0.75rem;
          color: #495057;
          background-color: #fff;
          background-clip: padding-box;
          border: 1px solid #ced4da;
          border-radius: 0.25rem;
          transition: border-color 0.15s
            }
            #comments{
              min-height: 120px;
          width: 100%;
          padding: 0.625rem;
          resize: vertical;
          width: 95%;
      }
            #submit{
              min-height: 60px;
          width: 100%;
          padding: 0.5rem;
          resize: vertical;
          width: 95%;
          background-color: #37af65;
          color: #fff;
          border: none;

            }
            .header{
              text-align: center;
              font-family: 'Poppins', sans-serif;
            }
            #title{
              font-weight: 400;
          line-height: 1.2;

            }
            body{
              font-family: 'Poppins', sans-serif;
          font-size: 1rem;
          font-weight: 400;
          line-height: 1.4;
          color: var(--color-white);
          margin: 0;

            }
            p{
              color: white;
              font-family: 'Poppins', sans-serif;
            }
            #form-group{
              color: white;
            }
            #survey-form label{
              color: #fff

            }

            input[type=checkbox], input[type=radio] {
                margin-right: 10px;
            }
    </style>
  </head>
  <body>
    <div class="bg-survey">
      <div class="container">
        <header class="header">
          <h1 id="title" class="text-center">freeCodeCamp Survey Form</h1>
          <p id="description" class="description text-center">
            Thank you for taking the time to help us improve the platform
          </p>
        </header>
        <form id="survey-form" action=""class="p-5" method="post">
          <div class="form-group">
            <p>name</p>
            <input type="text" placeholder="enter your name" class="form-control" />
          </div>
          <div class="form-group">
            <p>email</p>
            <input type="email" name="email" placeholder="enter your email" id="email-label" />
          </div>
          <div class="form-group">
            <p>Age(optional)</p>
            <input
              type="number"
              name="Age"
              placeholder="enter your Age"
              id="number-label"
              min="15"
              max="50"
            />
          </div>
          <div class="form-group">
            <p>Which option best describes your current role?</p>
            <select id="dropdown">
              <option value="1">select an option</option>
              <option value="2">student</option>
              <option value="3">full time job</option>
              <option value="4">full time learner</option>
              <option value="5">prefer not to say</option>
              <option value="6">other </option>
            </select>
          </div>
          <div class="form-group">
            <p>Would you recommend freeCodeCamp to a friend?</p>
            <label> <input type="radio" name="definitely" />definitely</label><br />
            <label> <input type="radio" name="maybe" />maybe</label><br />
            <label> <input type="radio" name="not sure" />not sure</label><br />
          </div>
          <div class="form-group">
            <p>What is your favorite feature of freeCodeCamp?</p>
            <select id="features">
              <option value="select">select an option</option>
              <option value="challenges">challenges</option>
              <option value="projects">projects</option>
              <option value="community">community</option>
              <option value="open source">open source</option>
            </select>
          </div>
          <div class="form-group">
            <p>What would you like to see improved? (Check all that apply)</p>

            <label><input type="checkbox" name="" />front end projects</label><br />
            <label><input type="checkbox" name="" />back end projects</label><br />
            <label><input type="checkbox" name="" />data visualization</label><br />
            <label><input type="checkbox" name="" />challenges</label><br />
            <label><input type="checkbox" name="" />open source community</label><br />
            <label><input type="checkbox" name="" />gitter help rooms</label><br />
            <label><input type="checkbox" name="" />videos</label><br />
            <label><input type="checkbox" name="" />city meet ups</label><br />
            <label><input type="checkbox" name="" />wiki</label><br />
            <label><input type="checkbox" name="" />forums</label><br />
            <label><input type="checkbox" name="" />additional courses</label><br />
          </div>
          <div class="form-group">
            <p>Any comments or suggestions?</p>
            <br />
            <textarea class="form-control" id="comments" rows="5" cols="50" placeholder="enter your comments here" ></textarea><br />
          </div>
          <div class="form-group" id="button">
            <button type="submit" id="submit" class="submit-button" placeholder="enter your comments here">
              submit
            </button>
          </div>
        </form>
      </div>
    </div>

    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script
      src="https://code.jquery.com/jquery-3.5.1.slim.min.js"
      integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj"
      crossorigin="anonymous"
    ></script>
    <script
      src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js"
      integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo"
      crossorigin="anonymous"
    ></script>
    <script
      src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/js/bootstrap.min.js"
      integrity="sha384-OgVRvuATP1z7JjHLkuOU7Xw704+h835Lr+6QL9UvYjZE3Ipu6Tp75j7Bh/kR0JKI"
      crossorigin="anonymous"
    ></script>
  </body>
</html>
