# coursera-test
<!DOCTYPE html>
<html>
<head>
  <title>Responsive Layout</title>
  <style>
    /* Global Styles */
    body {
      font-family: Arial, sans-serif; /* Optional: Set your desired font family */
    }
    
    .container {
      margin: 0 auto;
      max-width: 1200px; /* Adjust this value to fit your desired maximum width */
      padding: 20px;
      box-sizing: border-box;
    }
    
    h1 {
      font-size: 24px;
    }
    
    h2 {
      font-size: 18px;
    }
    
    .section {
      position: relative;
      float: left;
      width: 33.33%;
      padding: 20px;
      box-sizing: border-box;
      border: 1px solid black;
      background-color: #F1F1F1; /* Set your desired section background color */
    }
    
    .section h2 {
      position: absolute;
      top: 10px;
      right: 10px;
      margin: 0;
      background-color: #FFD700; /* Set your desired section title background color */
      padding: 5px 10px;
      color: #000; /* Set your desired text color for section title */
    }
    
    /* Media Queries */
    @media (max-width: 991px) {
      .section {
        width: 50%;
      }
      .section:nth-child(3) {
        clear: both;
        width: 100%;
      }
    }
    
    @media (max-width: 767px) {
      .section {
        width: 100%;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Page Heading</h1>
    <div class="row">
      <div class="section">
        <h2>Chicken</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
      </div>
      <div class="section">
        <h2>Beef</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
      </div>
      <div class="section">
        <h2>Sushi</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
      </div>
    </div>
  </div>
</body>
</html>
