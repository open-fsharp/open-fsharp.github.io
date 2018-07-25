---
layout: speaker
title: Tomas Petricek
category: Not just a computer scientist
---

<div class="row">
    <div class="col-md-6">
        <div class="speaker-talk">
            <div class="section-head">
                <h2 class="header-title">Reactive and async abstractions</h2>
                    <p class="header-desc">Wed 26th - 02:00 PM (Workshop)</p>
            </div>
            <div>
                <p>
                    F# added support for asynchronous workflows over 10 years ago, so you would think that the problem of asynchronous programming should have been fixed by now. Yet, if you try to make sense of the different abstractions for asynchronous programming, it is easy to get lost! What is the difference between IObservable, IEvent, Async, Task and AsyncSeq? When should you use which of those and does it really matter?
                </p>
                <p>
                    In this hands-on workshop, we're going to look under the cover of F# abstractions for asynchronous and reactive programming. We'll implement some of them from scratch to understand how they actually work. As is often the case in F#, looking at the type definition is the best way to understand what is going on!
                </p>
            </div>
        </div>
    </div>
    <div class="col-md-6">
        <div class="speaker-talk">
            <div class="section-head">
                <h2 class="header-title">Build your own Excel 365 in an hour with F#</h2>
                <p class="header-desc">Fri 28th - 09:00 AM (Talk)</p>
            </div>
            <div>
                <p>
                    There are many interesting things happening in a spreadsheet. It needs an interactive user interface where users can edit data and formulas in cells, it needs to parse formulas that users write, it needs to evaluate formulas and show results on the fly and it also needs to handle errors such as division by zero and circular references. In this live coding session, Tomas will attempt to implement all of these features live on stage. The talk will show a number of techniques and principles that are useful even if you do not plan to create a competition to Excel 365 and Google Sheets! 
                </p>
                <p>
                    Along the way, you will learn about the Fable compiler which makes it easy to compile correct, functional-first code to JavaScript and run it in a browser. You will also learn about a number of powerful functional programming techniques. We will use the Elm architecture to create an interactive web application in a functional way and we will use parser combinators to easily create parser for formulas. Finally, we will look at the tips and tricks for handling errors and creating computations that update on-the-fly when data change.
                </p>
            </div>
            <div>
                <div class="speaker-tag">
                    <ul class="tag">
                        <li><a href="#">Fable</a></li>
                        <li><a href="#">Elmish</a></li>
                        <li><a href="#">Live coding</a></li>
                    </ul>
                </div>
                <div class="talk-level">
                    <img src="{{ site.baseurl }}public/assets/animals/bear.png" alt="This talk is Bear level" />
                </div>														
            </div>
        </div>
    </div>
</div><!-- /.row -->
<div class="row">
    <div class="col-md-12">
        <div class="speaker-about">
            <div class="section-head">
                <h2 class="header-title">About {{ page.title }}</h2>
                <p class="header-desc">
                    <a href="https://twitter.com/tomaspetricek"><i class="fab fa-twitter"></i></a>
					<a href="https://github.com/tpetricek"><i class="fab fa-github-alt"></i></a>
            		<a href="http://tomasp.net/blog/"><i class="fas fa-rss"></i></a>
                </p>					
            </div>
            <div class="row">
                <div class="col-md-2">
                    <img src="{{ site.baseurl }}public/assets/speakers/2018/tomas-petricek.jpg" alt="Tomas Petricek" />
                </div>
                <div class="col-md-10">
                    <p>
                        Tomas is a computer scientist, book author and open-source developer. He wrote a popular book called "Real-World Functional Programming" and is a lead developer of several F# open-source libraries, but he also contributed to the design of the F# language as an intern and consultant at Microsoft Research. He is a partner at <a href="http://fsharpworks.com" target="_blank">fsharpWorks</a> where he provides trainings and consulting services.
                    </p>
                    <p>
                        Tomas recently submitted his PhD thesis at the University of Cambridge focused on types for understanding context usage in programming languages, but his most recent work also includes two essays that attempt to understand programming through the perspective of philosophy of science.
                    </p>
                </div>
            </div>       
        </div>
    </div>
</div>