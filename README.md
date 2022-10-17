# Shecodes-Basics-Projects
Projects from Shecodes Basics Coding Workshops
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>SheCodes Week 1 Homework Challenge</title>
    <style>
      body {
        font-family: Arial, Helvetica, sans-serif;
        text-align: center;
      }
      h1 {
        font-size: 34px;
        margin-top: 1px;
        margin-bottom: 5px;
      }
      h3 {
        padding-bottom: 15px;
      }

      .site-emoji {
        display: inline-block;
        font-size: 35px;
        margin-top: 0;
      }
      .current-weather {
        color: #1a65d6;
        font-size: 35px;
        text-align: center;
        font-weight: bold;
      }
      .low-temp {
        font-size: 35px;
        font-weight: 100;
      }

      .high-temp {
        font-weight: bold;
        font-size: 35px;
      }

      .weather-list {
        display: block;
        padding-top: 10px;
      }
      .heading {
        font-size: 12px;
        font-family: Arial, Helvetica, sans-serif;
        margin-top: 0px;
        padding-top: 5px;
      }

      .list-low-temp {
        font-weight: 100;
        font-family: monospace;
      }
      .list-high-temp {
        font-weight: bold;
        font-family: monospace;
      }

      .favorite-styled {
        font-size: 17px;
        margin-bottom: 40px;
        margin-top: 30px;
        background-color: #1a65d6;
        color: white;
        box-shadow: 0px 5px 16px 0 grey;
        font-family: Arial, Helvetica, sans-serif;
        padding: 16px 24px;
        border-radius: 40px;
        border-color: transparent;
        transition: all 200ms ease-in-out;
      }
      .favorite-styled:hover {
        background-color: white;
        border-width: 1px;
        cursor: pointer;
        border-style: solid;
        border-color: #1a65d6;
        color: #1a65d6;
      }
      .name {
        font-family: "Courier New", Courier, monospace;
        font-weight: normal;
      }
      .highlight {
        margin: auto;
        width: 300px;
        border-radius: 25px;
        padding: 10px 50px 10px 50px;
        transition: all 200ms ease-in-out;
      }
      .highlight:hover {
        background-color: rgb(244, 204, 44, 0.1);
      }
    </style>
  </head>

  <body>
    <div class="site-emoji">🌤</div>
    <br />
    <div class="current-weather"><h1>Currently 21° in Tokyo</h1></div>

    <h1>
      <span class="low-temp">13° /</span> <span class="high-temp">23°</span>
    </h1>

    <div class="weather-list">
      <div class="highlight">
        <div class="heading">
          <h2>🌧 Tomorrow</h2>
        </div>
        <h3>
          <span class="list-low-temp">10° /</span>
          <span class="list-high-temp">22°</span>
        </h3>
      </div>
      <div class="highlight">
        <div class="heading">
          <h2>⛅️ Saturday</h2>
        </div>
        <h3>
          <span class="list-low-temp">15° /</span>
          <span class="list-high-temp"> 17°</span>
        </h3>
      </div>
      <div class="highlight">
        <div class="heading"><h2>☀️Sunday</h2></div>
        <h3>
          <span class="list-low-temp">25° /</span>
          <span class="list-high-temp"> 28°</span>
        </h3>
      </div>
    </div>

    <button class="favorite-styled" type="button">Change city</button>
    <div class="name">Coded by Emem</div>
  </body>
</html>
