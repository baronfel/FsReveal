- title : SAFE Stack: F# on the web
- description : Introduction to the SAFE Stack
- author : Chet Husk
- theme : night
- transition : default

***

## F# on the web:
## The SAFE Stack

<a href="https://safe-stack.github.io/"><img src="images/safe.png" class="plain" /></a>

Chet Husk 
<br />
[Twitter](http://www.twitter.com/chethusk)
<br />
[GitHub](https://github.com/baronfel)

***

### Agenda

* SAFE
* Demo
* Q&A

***

### SAFE Stack

* What is a 'stack'?

--- 

### MEAN

* Data store
* Web server
* Client-side UI
* Runtime

---

### LAMP

* Operating System
* HTTP server
* Database
* Client-side

--- 

### What's a stack?


<blockquote>
A set of technologies that explicitly work well together
</blockquote>

*** 

### SAFE Stack

* S - Saturn

---

### Saturn

<a href="https://saturnframework.org/"><img src="images/saturn-logo.png" class="plain" /></a>
<br/>
<q>A modern web framework that focuses on developer productivity, performance, and maintainability</q>

A layer on top of the [Giraffe](https://github.com/giraffe-fsharp/Giraffe) web framework for [ASP.Net Core](https://docs.microsoft.com/en-us/aspnet/core/?view=aspnetcore-2.1)

---

### Saturn, cont.

* Inspired by Elixir's [Phoenix framework](https://phoenixframework.org/)
* Batteries-Included
* MVC-esque
* Computation-Expression-based for simplicity
* Access to internals for flexibility

***

### SAFE Stack

* A - Azure

---

### Azure

* Microsoft's cloud environment
* Most SAFE samples showcase Azure deployments
* Most are docker-based, and so will deploy anywhere containers are supported

***
### SAFE Stack

* F - Fable

--- 

### Fable

<a href="http://fable.io/"><img src="images/fable-logo.png" class="plain" width="50%" /></a>
<br/>
<q>The compiler that emits JavaScript you can be proud of!</q>

---
### Fable

* A F#-to-JavaScript compiler that supports seamless interop between .Net/F# and JS code
* Allows for F# to be used on both the client _and_ server
* Client-side and serverside (browser and nodejs)
* Runs on normal Javascript tooling
    * webpack
    * babel

***

### SAFE Stack

* E - Elmish

---

### Elmish

<a href="https://elmish.github.io/elmish/"><img src="images/elmish-logo.png" class="plain" /></a>

A library implementation of Elm's famous [Model/View/Update(MVU)](http://www.elm-tutorial.org/en/02-elm-arch/01-introduction.html) architecture

Actually independent of any UI library.

---

### Elmish

Implementations exist for

* [React](https://elmish.github.io/react/)
* [React Native](https://elmish.github.io/react/native.html)
* [Xamarin Forms (nee Fabulous)](https://fsprojects.github.io/Fabulous/)

***

### SAFE Stack

* Saturn
* Azure
* Fable
* Elmish

<p class="fragment">But each part can be switched out independently to best suit your needs</p>

---
### GGFR Stack

* Giraffe
* Google Cloud
* Fable
* React

---
### FAFA Stack

* Freya
* AWS
* Fable
* Angular

***

### Why SAFE?

* F# end-to-end
* Typesafe
* Flexible
* Tested - run as part of Microsoft's .Net Core validation
* Code-sharing (Isomorphic F# :D)
* Rapid Iteration with [hot module reloading]()

***

### Demo

* [SAFE Bookstore](https://github.com/SAFE-Stack/SAFE-BookStore)

***

### Other Resources

<p>Project Pages</p>

* [SAFE](https://safe-stack.github.io/)
* [Saturn](https://saturnframework.org/)
* [Azure](https://azure.microsoft.com/en-us/)
* [Fable](http://fable.io)
* [Elmish](https://elmish.github.io/elmish/)
* [Giraffe](https://github.com/giraffe-fsharp/Giraffe)

--- 

### Community links
* [Awesome Fable](https://github.com/kunjee17/awesome-fable)
* [SAFE Learning Resources](https://safe-stack.github.io/docs/learning/)

---

### `dotnet` CLI templates

[`dotnet new -i SAFE.Template && dotnet new SAFE`](https://github.com/SAFE-Stack/SAFE-template)

[`dotnet new -i Saturn.Template && dotnet new Saturn`](https://github.com/SaturnFramework/Saturn.Template)

***

### Q & A

***

### Thanks for coming!

Slides are at [https://baronfel.github.io/austin-meetup-2018-09-20](https://baronfel.github.io/austin-meetup-2018-09-20/#/)

Check out the [Austin F#](https://www.meetup.com/Austin-F-Meetup/events/254096582/) MeetUp group for more like this.

Help us decide on the next topic!



Join the F# Software Foundation and visit us on Slack and the [forums](https://forums.fsharp.org)
<a href="https://fsharp.org/"><img src="images/fsharp256" class="plain" width="50%" /></a>