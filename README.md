<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Review Cards</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #354199;
      text-align: center;
      padding: 20px;
    }

    .card {
      display: inline-block;
      width: 150px;
      height: 185px;
      background-color: #fff;
      border-radius: 10px;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
      margin: 10px;
      overflow: hidden;
      position: relative;
      cursor: pointer;
      transition: transform 0.15;
    }

    .card:hover {
      transform: scale(1.05);
    }

    .riddle {
      padding: 10px;
      font-weight: bold;
    }

    .answer {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background-color: rgba(255, 255, 255, 0.9);
      display: flex;
      justify-content: center;
      align-items: center;
      opacity: 0;
      transition: opacity 0.5s;
    }

    .card:hover .answer {
      opacity: 1.5;
    }
  </style>
</head>

<body>
  <h1>Review Cards</h1>

  <div class="review card">
    <div class="riddle">What has to be broken before you can use it?</div>
    <div class="answer">an egg!</div>
  </div>

  <div class="review card">
    <div class="riddle">What month has 28 days?</div>
    <div class="answer">All of them!</div>
  </div>

  <div class="review card">
    <div class="riddle">A man who was outside in the rain without an umbrella or hat didn’t get a single hair on his head wet. Why?</div>
    <div class="answer">He was bald!</div>
  </div>

  <div class="review card">
    <div class="riddle">What gets wet while drying?</div>
    <div class="answer">a towel!</div>
  </div>

  <div class="review card">
    <div class="riddle">What five letter word becomes shorter when you add two letters to it?</div>
    <div class="answer">short!</div>
  </div>

  <div class="review card">
    <div class="riddle">You see me once in June, twice in November and not at all in May. What am I?</div>
    <div class="answer">The letter e!</div>
  </div>

  <div class="review card">
    <div class="riddle">What letter is at the end of everything?</div>
    <div class="answer">G</div>
  </div>

  <div class="review card">
    <div class="riddle">How far can you walk into the woods?</div>
    <div class="answer">Halfway. After that, you’re walking out.</div>
  </div>

</body>

</html>
