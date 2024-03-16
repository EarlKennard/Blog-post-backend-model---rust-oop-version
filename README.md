# Project description

This program does nothing; it is just one of the two blog post backend model examples in the [rust lang book with the three extra suggestions implemented](https://doc.rust-lang.org/stable/book/ch17-03-oo-design-patterns.html#trade-offs-of-the-state-pattern). This repo is a modification of the example written in OOP-pattern Rust. 

# Notes on the project

Adding the reject() method was trivial. Requiring two calls to approve() is easy in hindsight, but it took me a while to add the approval counter to the Post struct. The add_text() method only being usable while the Post is in the Draft State took me a while to do, if only because I didn't realize the usefulness of traits and implementations quickly enough. 

There is a lot of redundant and/or useless code in this OOP-design pattern. In my opinion, this style of programming is not best suited for Rust.