+++

outputs = ["Reveal"]
[reveal_hugo]
theme = "league"
transition = 'zoom'
progress= "true"
highlight_theme = "zenburn"

+++
# Functional Programming

---
### Definition
* Functions are first class citizens: Higher order functions
* No OOP or other features 
* Purity => no side effects in functions
* Data transformations

---
### Origins and development
* Lambda calculus => https://en.wikipedia.org/wiki/Lambda_calculus
* Introduced in early programming languages like LISP
* Grand grand father: ML Language.
* Functional traits in every language: lambdas, LINQ
* Current samples: Haskell, Elm, Ocaml, F#, Scala, Kotlin...

{{% fragment %}}
* Not samples: C#{{% /fragment %}}

{{% fragment %}}, Java{{% /fragment %}} 

{{% fragment %}} and Javascript (of course) {{% /fragment %}}


---
### Main features expected
* Pure functions
* Lazy function application
* Persistent data structures
* Algebraical data structures
* Memoization
* Type inference

---
### Why should I care?
* Less runtime errors
* More succinct coding

* And also...

---
## ...functional mindset

---
Product people: find common use patterns and understand that requisites should work better in code if they are idempotent, no dependencies between them

{{% fragment %}}
You'll think in business data structures and global patterns that transform data{{% /fragment %}}

{{% fragment %}}
You'll find that composing small functions is better that create a whole framework to support all kind of use cases{{% /fragment %}}

---
You'll start trusting your programming language and you'll low the amount of defensive code you create...

{{% fragment %}}
less cluttered code...{{% /fragment %}}

{{% fragment %}}
better development time... {{% /fragment %}}

{{% fragment %}}
more quality{{% /fragment %}}

{{% fragment %}}
And everything will flow...{{% /fragment %}}

---
### Videos
"Make impossible states impossible"
https://www.youtube.com/watch?v=IcgmSRJHu_8

---
### Web
https://fsharpforfunandprofit.com/ specially this: https://fsharpforfunandprofit.com/series/thinking-functionally/

Learn you a Haskell for a great good: http://www.learnyouahaskell.com/ Free reading online

---
### Books
Domain Modeling Made Functional https://fsharpforfunandprofit.com/books/

Purely functional data structures: https://leer.amazon.es/kp/embed?asin=B00AKE1V04&preview=newtab&linkCode=kpe&ref_=cm_sw_r_kb_dp_64SZYM83TTJ8Q2Z7F989

And https://web.engr.oregonstate.edu/~walkiner/teaching/cs583-sp21/files/9.DataStructures.pdf

