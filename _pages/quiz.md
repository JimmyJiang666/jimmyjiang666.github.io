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

<div class="container" id="quiz-container">
    <!-- Question 1 -->
    <div class="row mb-4">
        <div class="col-md-4">
            <img class="img-fluid" src="https://cdn.cnn.com/cnnnext/dam/assets/180426115546-cola-wars-coke-pepsi.jpg" alt="Pepsi or Coke"/>
        </div>
        <div class="col-md-8">
            <p>Question 1: Pepsi or Coke?</p>
            <button class="btn btn-primary" onclick="selectAnswer(1, 'Pepsi, something tastes like toilet cleaner.', 1)">Pepsi</button>
            <button class="btn btn-primary" onclick="selectAnswer(1, 'Yes, coke please.', 2)">Coke</button>
            <div id="answer1" class="answer"></div>
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
            <button class="btn btn-primary" onclick="selectAnswer(2, 'When you buy Lays, you are just paying for the air inside.', 1)">Lays</button>
            <button class="btn btn-primary" onclick="selectAnswer(2, 'MasterPIECE.', 2)">Pringles</button>
            <div id="answer2" class="answer"></div>
        </div>
    </div>

    <hr/>

    <!-- Question 3 -->
    <div class="row mb-4">
        <div class="col-md-4">
            <img class="img-fluid" src="http://p9.itc.cn/q_70/images03/20200625/5877604ed4284b149ebddb76d8d84ac1.jpeg" alt="Zongzi with meat or Zongzi with sugar"/>
        </div>
        <div class="col-md-8">
            <p>Question 3: Zongzi with meat(肉粽) or Zongzi with sugar(甜粽)?</p>
            <button class="btn btn-primary" onclick="selectAnswer(3, 'Ok, not bad but also not great.', 1)">Zongzi with meat(肉粽)</button>
            <button class="btn btn-primary" onclick="selectAnswer(3, 'Yay! Zongzi, essentially, is a type of sweet dessert :)', 2)">Zongzi with sugar(甜粽)</button>
            <div id="answer3" class="answer"></div>
        </div>
    </div>

    <hr/>

    <!-- Question 4 -->
    <div class="row mb-4">
        <div class="col-md-4">
            <img class="img-fluid" src="https://cdn.britannica.com/86/166986-050-4CEFE5DE/cute-kitten-and-puppy-outdoors-in-grass.jpg" alt="Dog or cat"/>
        </div>
        <div class="col-md-8">
            <p>Question 4: Dog or cat?</p>
            <button class="btn btn-primary" onclick="selectAnswer(4, 'Yes. Labrador. The best.', 1)">Dog</button>
            <button class="btn btn-primary" onclick="selectAnswer(4, '🐱', 2)">Cat</button>
            <div id="answer4" class="answer"></div>
        </div>
    </div>

    <hr/>

    <!-- Question 5 -->
    <div class="row mb-4">
        <div class="col-md-4">
            <img class="img-fluid" src="http://img.mp.itc.cn/upload/20170407/6ed9c11c35344c4387e4c67adac3b920_th.png" alt="Chongqing hotpot or Chengdu hotpot"/>
        </div>
        <div class="col-md-8">
            <p>Question 5: Chongqing hotpot or Chengdu hotpot?</p>
            <button class="btn btn-primary" onclick="selectAnswer(5, 'There are many reasons that you should (always🤓) go with Chongqing hotpot. In short, check out this <a href=\'https://www.sohu.com/a/132630554_385445\'>article</a>.', 1)">Chongqing</button>
            <button class="btn btn-primary" onclick="selectAnswer(5, 'Click the other one I\'ll tell you.', 2)">Chengdu</button>
            <div id="answer5" class="answer"></div>
        </div>
    </div>

    <hr/>

    <!-- Question 6 -->
    <div class="row mb-4">
        <div class="col-md-4">
            <img class="img-fluid" src="https://thumbs.dreamstime.com/z/%E7%8C%8E%E8%B1%B9%E5%92%8C%E4%B9%8C%E9%BE%9F-%E5%BF%AB%E9%80%9F%E5%92%8C%E6%85%A2%E8%BD%BD%E9%87%8D%E6%A2%81-95250308.jpg" alt="Leopard that runs for 50 years or turtle that sleeps for 150 years"/>
        </div>
        <div class="col-md-8">
            <p>Question 6: A leopard that runs for 50 years or a turtle that sleeps for 150 years? (Credit to my mom who asked me this question all the time when I was little)</p>
            <button class="btn btn-primary" onclick="selectAnswer(6, 'I want to be a leopard. For now. Maybe I want to switch to a turtle when I am older :)', 1)">Leopard🐆</button>
            <button class="btn btn-primary" onclick="selectAnswer(6, 'I can\'t imagine myself sleeping for 150 years. Headache.', 2)">Turtle🐢</button>
            <div id="answer6" class="answer"></div>
        </div>
    </div>

    <hr/>

    <!-- Question 7 -->
    <div class="row mb-4">
        <div class="col-md-4">
            <img class="img-fluid" src="https://media.licdn.com/dms/image/C4E12AQHUqdLSIYhFWQ/article-cover_image-shrink_600_2000/0/1520172015994?e=2147483647&v=beta&t=FtcUUgDliRSuBZGimArPTTcb1MVcHk5vLhQ-g4PSzH4" alt="Satisfied pig or dissatisfied Socrates"/>
        </div>
        <div class="col-md-8">
            <p>Question 7: Satisfied pig or dissatisfied Socrates?</p>
            <button class="btn btn-primary" onclick="selectAnswer(7, 'An oink! An oink! 🐷', 1)">Satisfied pig</button>
            <button class="btn btn-primary" onclick="selectAnswer(7, 'Il n\'ya qu\'un héroïsme au monde：c\'est de voir le monde tel qu\'il est et de l\'aimer. So yes, I\'d rather be a dissatisfied Socrates.', 2)">Dissatisfied Socrates</button>
            <div id="answer7" class="answer"></div>
        </div>
    </div>

    <hr/>

    <!-- Question 8 -->
    <div class="row mb-4">
        <div class="col-md-4">
            <img class="img-fluid" src="https://a4.espncdn.com/combiner/i?img=%2Fphoto%2F2022%2F1120%2Fr1093637_1296x729_16%2D9.jpg" alt="GOAT - Messi"/>
        </div>
        <div class="col-md-8">
            <p>Question 8: Now the most important question. Who is the GOAT?</p>
            <button class="btn btn-primary" onclick="selectAnswer(8, 'Messi is the only GOAT.', 1)">Messi</button>
            <button class="btn btn-primary" onclick="selectAnswer(8, 'The one and the only. Period.', 2)">Still Messi</button>
            <div id="answer8" class="answer"></div>
        </div>
    </div>

    <hr/>

    <!-- Submit Button -->
    <div class="text-center mb-4">
        <button class="btn btn-success" onclick="submitQuiz()">Submit</button>
    </div>

    <!-- Result Display -->
    <div class="text-center">
        <div id="result" style="display: none;">
            <svg viewBox="0 0 36 36" class="circular-chart green">
                <path class="circle-bg"
                    d="M18 2.0845
                        a 15.9155 15.9155 0 0 1 0 31.831
                        a 15.9155 15.9155 0 0 1 0 -31.831" />
                <path id="circle" class="circle"
                    stroke-dasharray="0, 100"
                    d="M18 2.0845
                        a 15.9155 15.9155 0 0 1 0 31.831
                        a 15.9155 15.9155 0 0 1 0 -31.831" />
                <text x="18" y="20.35" class="percentage" id="percentage">0%</text>
            </svg>
            <p>You matched <span id="percentage-text">0</span>% of my answers!</p>
            <p id="message" style="display: none;">Shoot me a message! Few people can get me this much :)</p>
        </div>
    </div>
</div>

<script>
    const correctAnswers = [2, 2, 2, 1, 1, 1, 2, 1, 2];
    let userAnswers = new Array(correctAnswers.length).fill(null);

    function selectAnswer(question, text, answer) {
        if (userAnswers[question - 1] !== null) {
            return; // Answer already selected
        }
        document.getElementById(`answer${question}`).innerText = text;
        userAnswers[question - 1] = answer;
    }

    function submitQuiz() {
        let score = 0;
        for (let i = 0; i < correctAnswers.length; i++) {
            if (i === correctAnswers.length - 1) {
                if (userAnswers[i] === 1 || userAnswers[i] === 2) {
                    score++;
                }
            } else if (userAnswers[i] === correctAnswers[i]) {
                score++;
            }
        }
        const percentage = Math.round((score / correctAnswers.length) * 100);
        animatePercentage(percentage);
        document.getElementById("result").style.display = "block";
        if (percentage >= 80) {
            document.getElementById("message").style.display = "block";
        }
    }

    function animatePercentage(percentage) {
        const circle = document.getElementById('circle');
        const text = document.getElementById('percentage');
        const textValue = document.getElementById('percentage-text');
        let progress = 0;
        const interval = setInterval(() => {
            if (progress >= percentage) {
                clearInterval(interval);
            } else {
                progress++;
                circle.style.strokeDasharray = `${progress}, 100`;
                text.innerHTML = `${progress}%`;
                textValue.innerHTML = `${progress}`;
            }
        }, 20);
    }
</script>

<style>
    .answer {
        margin-top: 10px;
        font-style: italic;
    }
    button.btn.btn-primary {
        margin-right: 10px;
    }
    .circular-chart {
        display: block;
        margin: 10px auto;
        max-width: 80%;
        max-height: 250px;
    }
    .circle-bg {
        fill: none;
        stroke: #eee;
        stroke-width: 3.8;
    }
    .circle {
        fill: none;
        stroke-width: 2.8;
        stroke-linecap: round;
        animation: progress 1s ease-out forwards;
    }
    .green .circle {
        stroke: #4caf50;
    }
    .percentage {
        font-size: 0.5em;
        text-anchor: middle;
        fill: #333;
    }
</style>
