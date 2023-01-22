---
layout: page
permalink: /quiz/
title: Quiz
description: (Under construction!!) 
nav: true
nav_order: 6
---

<p>
These are indisputable things in the world that people often don't realize. If you are 100% with me, shoot me an email we should grab a coffee at some point. 
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
        <button onclick="photo1()">Messi</button>
        <div id="answer1" style="display:none;">
            Messi is the only GOAT.
        </div>
        <button onclick="photo1()">Still Messi</button>
        <div id="answer1" style="display:none;">
            The one and the only. Period.
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
<hr/>
<div class="row">
    <div class="col-sm-4">
        <img class="img-responsive" src="http://p9.itc.cn/q_70/images03/20200625/5877604ed4284b149ebddb76d8d84ac1.jpeg"/>
    </div>

    <div class="col-sm-8">
        <p>
        Question 2: which one is better? Zongzi with meat(肉粽)or Zongzi with sugar(甜粽)?
        </p>
        <button onclick="photo2()">Zongzi with meat(肉粽)</button>
        <div id="answer2" style="display:none;">
            Ok, not bad but also not great.
        </div>
        <button onclick="photo2()">Zongzi with sugar(甜粽)</button>
        <div id="answer2" style="display:none;">
            Yay! Zongzi, essentially, is a type of sweet desert :)
        </div>
        <script>
            function photo2() {
              var x = document.getElementById("answer2");
              if (x.style.display === "none") {
                x.style.display = "block";
              } else {
                x.style.display = "none";
              }
            }
        </script>
    </div>
</div>

