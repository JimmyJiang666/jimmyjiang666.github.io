---
layout: page
permalink: /quiz/
title: Quiz
description: (Under construction!!) 
nav: true
nav_order: 6
---

<p>
These are indisputable things in the world that people often don't realize. (Jk. More like things that characterize me 🤔) Ordered in life-significance (to me). If you are 100% with me, shoot me an email we should grab a coffee at some point. 
</p>

<hr/>

<div class="container">
    <!-- Question 1 -->
    <div class="row mb-4">
        <div class="col-md-4">
            <img class="img-fluid" src="https://cdn.cnn.com/cnnnext/dam/assets/180426115546-cola-wars-coke-pepsi.jpg" alt="Pepsi or Coke"/>
        </div>
        <div class="col-md-8">
            <p>Question 1: Pepsi or Coke?</p>
            <button class="btn btn-primary" onclick="toggleAnswer('answer1')">Pepsi</button>
            <div id="answer1" class="answer">
                Pepsi, something tastes like toilet cleaner.
            </div>
            <button class="btn btn-primary" onclick="toggleAnswer('answer2')">Coke</button>
            <div id="answer2" class="answer">
                Yes, coke please.
            </div>
        </div>
    </div>

    <hr/>

    <!-- Question 2 -->
    <div class="row mb-4">
        <div class="col-md-4">
            <img class="img-fluid" src="https://diffzi.com/wp-content/uploads/2018/11/Lays-vs.-Pringles.jpg" alt="Lays or Pringles"/>
        </div>
        <div class="col-md-8">
            <p>Question 2: Lays or Pringles?</p>
            <button class="btn btn-primary" onclick="toggleAnswer('Lays')">Lays</button>
            <div id="Lays" class="answer">
                When you buy Lays, you are just paying for the air inside.
            </div>
            <button class="btn btn-primary" onclick="toggleAnswer('Pringles')">Pringles</button>
            <div id="Pringles" class="answer">
                MasterPIECE.
            </div>
        </div>
    </div>

    <hr/>

    <!-- Add other questions in similar fashion -->

</div>

<script>
    function toggleAnswer(id) {
        var x = document.getElementById(id);
        if (x.style.display === "none" || x.style.display === "") {
            x.style.display = "block";
        } else {
            x.style.display = "none";
        }
    }
</script>

<style>
    .answer {
        display: none;
        margin-top: 10px;
        font-style: italic;
    }
</style>
