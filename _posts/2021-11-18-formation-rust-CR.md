---
layout: post
title:  "Formation Rust Club Robot INSAT"
date:   2021-11-21
categories: [Rust, ClubRobot, Event]
---

This is a recap page for the introduction to Rust presentation I did for the [Robotics Club of INSA Toulouse](https://clubrobotinsat.github.io/).

Here is the summary of the points treated, keep in mind those are cherry-picked in the goal of coding embedded systems in rust.
That's why for example multi-threading and most std features were not included. 
Other's like lifetimes were excluded for simplicity as the objective was to introduce the language in less than 3h.

### Index
- Qu'est-ce que c'est Rust et pourquoi on utilise ?
- Cargo & Hello World
- Concepts communs de la programmation
- The ownership model
- Structs
- Traits
- Généricité
- Enum and pattern matching
- Traitement d’erreurs
- Modules and crates
- Collections (Vec, Strings)
- Tests automatiques
- Iterators
- Closures

### Practice exercice:
- Code together : [Brute force prime number search](https://github.com/joelimgu/brute_force_prime_search)
- [Rustlings exercices](https://github.com/rust-lang/rustlings) with a 
[video explaining most of them](https://egghead.io/courses/learning-rust-by-solving-the-rustlings-exercises-a722) 

### Documents

[Presentation - powerpoint]({{site.url}}/assets/documents/Presentation_Rust.pptx)

[Presentation - PDF]({{site.url}}/assets/documents/Presentation_Rust.pdf)

[Rust cheat sheet](https://letsgetrusty.com/wp-content/uploads/2021/10/LGR-Cheat-Sheet.pdf)

### Rust book ( The real bible )
This presentation is heavily based on the book, with adapted order and content:

[🦀 Bible ](https://doc.rust-lang.org/stable/book/)


<i>And remember failure is not an Option<T> it's a Result<T,E>
