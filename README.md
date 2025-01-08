<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Email Newsletter</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
      font-family: Arial, sans-serif;
    }
    table {
      border-spacing: 0;
      width: 100%;
    }
    img {
      display: block;
      max-width: 100%;
      height: auto;
    }
    .container {
      max-width: 600px;
      margin: 0 auto;
      background-color: #ffffff;
      border-radius: 8px;
      overflow: hidden;
    }
    .header {
      background-color: #7FD13B;
      text-align: center;
      padding: 20px;
    }
    .header h1 {
      margin: 0;
      font-size: 28px;
      color: #ffffff;
    }
    .section {
      padding: 20px;
    }
    .section h2 {
      font-size: 20px;
      color: #333333;
    }
    .section p {
      font-size: 16px;
      color: #666666;
      line-height: 1.6;
    }
    .btn {
      display: inline-block;
      padding: 10px 20px;
      background-color: #7FD13B;
      color: #ffffff;
      text-decoration: none;
      border-radius: 4px;
      font-size: 16px;
    }
    .features {
      display: flex;
      justify-content: space-between;
      padding: 20px;
    }
    .feature {
      text-align: center;
      width: 30%;
    }
    .footer {
      background-color: #333333;
      color: #ffffff;
      text-align: center;
      padding: 20px;
      font-size: 14px;
    }
    @media (max-width: 600px) {
      .features {
        flex-direction: column;
      }
      .feature {
        width: 100%;
        margin-bottom: 20px;
      }
    }
  </style>
</head>
<body>
  <table class="container">
    <tr>
      <td class="header">
        <h1>Big Idea on Business</h1>
      </td>
    </tr>
    <tr>
      <td class="section">
        <h2>Welcome</h2>
        <p>
          Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
        </p>
        <a href="#" class="btn">Discover More</a>
      </td>
    </tr>
    <tr>
      <td class="features">
        <div class="feature">
          <img src="https://via.placeholder.com/100" alt="Idea & Design">
          <h3>Idea & Design</h3>
          <p>Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.</p>
        </div>
        <div class="feature">
          <img src="https://via.placeholder.com/100" alt="Development">
          <h3>Development</h3>
          <p>Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.</p>
        </div>
        <div class="feature">
          <img src="https://via.placeholder.com/100" alt="Support">
          <h3>Support & Network</h3>
          <p>Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.</p>
        </div>
      </td>
    </tr>
    <tr>
      <td class="footer">
        <p>© 2023 Your Company. All rights reserved.</p>
        <p><a href="#" style="color: #7FD13B; text-decoration: none;">Unsubscribe</a></p>
      </td>
    </tr>
  </table>
</body>
</html>
