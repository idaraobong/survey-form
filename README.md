# survey-form
<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css" integrity="sha384-9aIt2nRpC12Uk9gS9baDl411NQApFmC26EwAOH8WgZl5MYYxFfc+NcPb1dKGj7Sk" crossorigin="anonymous">

    <title id="title">form project</title>
    <header>
     <h1> freeCodeCamp Survey Form </h1> 
    <p>Thank you for taking the time to help us improve the platform </p>
  </header>
    <style type="text/css">

      .container{
        text-align: left;
        background-color: rgba(58, 58, 158, 0.8);

      }
      
      header{
        text-align: center;
        font-family: "poppins", sans-serif;
        box-sizing: border-box;
        margin-bottom: 1.875rem;
        padding: 0 0.625rem;
        background-color: rgba(136, 136, 206, 0.7);
      }
      body{
        font-family: sans-serif;
      }
      #survey-form{
        padding: 2.5rem;
        box-sizing: border-box;
        font-size: 1rem;
        border-radius: 0.25rem;

      }
      .submit-button {
        height:4em;
        width:90%;
        text-align: center;
        font-size: 16px;
        padding: 0.75rem;
        background-color: green;
        border-radius: 2px;
        display: block;


      }
      textarea{
        min-height: 120px;
    width: 90%;
    padding: 1.5rem;
    resize: vertical;
      }
      #name-label{
        display: block;
    width: 100%;
    height: 2.375rem;
    padding: 0.375rem 0.75rem;
    color: #495057;
    background-color: #fff;
    background-clip: padding-box;
    border: 1px solid #ced4da;
    border-radius: 0.25rem;
    transition: border-color 0.15s}
    #email-label{
      display: block;
    width: 100%;
    height: 2.375rem;
    padding: 0.375rem 0.75rem;
    color: #495057;
    background-color: #fff;
    background-clip: padding-box;
    border: 1px solid #ced4da;
    border-radius: 0.25rem;
    transition: border-color 0.15s
    }
    #number-label{

      display: block;
    width: 100%;
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
    width: 100%;
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
    width: 100%;
    height: 2.375rem;
    padding: 0.375rem 0.75rem;
    color: #495057;
    background-color: #fff;
    background-clip: padding-box;
    border: 1px solid #ced4da;
    border-radius: 0.25rem;
    transition: border-color 0.15s
    }
        
      
  
  
    </style>
      
      
  </head>
  <body translate="no">
    <div class="container">
    <form id="survey-form" action="" method="post">
      <p>name </p>
     <input type="text" placeholder="enter your name" id="name-label">
     <p> email </p>
     <input type="email" name="email" placeholder="enter your email" id="email-label">
     <p>Age</p> 
     <input type="number" name="Age" placeholder="enter your Age" id="number-label" min="15" max="50">

                   
             <p>Which option best describes your current role?</p>
             <select id = "dropdown">
              <option value="1">select an option</option>
               <option value = "2">student</option>
               <option value = "3">full time job</option>
               <option value = "4">full time learner</option>
               <option value = "5">prefer not to say</option>
               <option value="6">other </option>
             </select>
    <p>Would you recommend freeCodeCamp to a friend?</p>
    <label>  <input type="radio" name="definitely">definitely</label><br>
    <label>  <input type="radio" name="maybe">maybe</label><br>
    <label>  <input type="radio" name="not sure">not sure</label><br>
    
    <p>What is your favorite feature of freeCodeCamp?</p>
    <select id="features">
    <option value="select">select an option</option>
    <option value="challenges">challenges</option>
    <option value="projects">projects</option>
    <option value="community">community</option>
    <option value="open source">open source</option>
    </select>
    
    <p>What would you like to see improved? (Check all that apply)</p>
    
    <label><input type="checkbox" name="">front end projects</label><br>
    <label><input type="checkbox" name="">back end projects</label><br>
    <label><input type="checkbox" name="">data visualization</label><br>
    <label><input type="checkbox" name="">challenges</label><br>
    <label><input type="checkbox" name="">open source community</label><br>
    <label><input type="checkbox" name="">gitter help rooms</label><br>
    <label><input type="checkbox" name="">videos</label><br>
    <label><input type="checkbox" name="">city meet ups</label><br>
    <label><input type="checkbox" name="">wiki</label><br>
    <label><input type="checkbox" name="">forums</label><br>
    <label><input type="checkbox" name="">additional courses</label><br>

  <p>Any comments or suggestions?</p><br>
  <textarea class="form-control" id="comments" rows="6" cols="50"></textarea><br>

<div id="button">
  <button type="submit" id="submit" class="submit-button">submit</button>
</div>

  
    


          
  
    


      
    </form>
    </div>
    

    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/js/bootstrap.min.js" integrity="sha384-OgVRvuATP1z7JjHLkuOU7Xw704+h835Lr+6QL9UvYjZE3Ipu6Tp75j7Bh/kR0JKI" crossorigin="anonymous"></script>
  </body>
</html>
