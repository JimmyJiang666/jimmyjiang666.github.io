---
layout: page
permalink: /quiz/
title: Quiz
description: (Under construction!!) 
nav: true
nav_order: 6
---

<p>
These are indisputable things in the world that people often don't realize. I hope you agree with me with most of the things. Otherwise...
</p>

<hr/>


<div class="row">
    <div class="col-sm-4">
        <img class="img-responsive" src="https://a4.espncdn.com/combiner/i?img=%2Fphoto%2F2022%2F1120%2Fr1093637_1296x729_16%2D9.jpg" width="75%"/>
    </div>

    <div class="col-sm-8">
        <p>
        Question 1: Who is the GOAT?
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
