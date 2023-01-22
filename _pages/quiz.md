---
layout: page
permalink: /quiz/
title: Quiz
description: (Under construction!!) To test if we are similar people.
nav: true
nav_order: 6
---

<div class="row">
    <div class="col-sm-4">
        <a href="images/jimmy.jpg">
        <img class="img-responsive" src="https://a4.espncdn.com/combiner/i?img=%2Fphoto%2F2022%2F1120%2Fr1093637_1296x729_16%2D9.jpg"/>
        </a>
    </div>

    <div class="col-sm-8">
        <p>
        Question 1: Who is better?
        </p>
        <button onclick="photo1()">Show answer</button>

        <div id="answer1" style="display:none;">
            Messi is the only GOAT.
        </div>
        <script>
            function photo1() {
              var x = document.getElementById("answer1");
              if (x.style.display === "none") {
                x.style.display = "block";
              } else {
                x.style.display = "none";
              }
            }
        </script>
    </div>
</div>
