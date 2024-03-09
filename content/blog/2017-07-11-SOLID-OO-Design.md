---
layout: post
title: "📝 SOLID Object-Oriented Design"
description: "Reflecting on SOLID principles."
categories: [Tech]
tags: [Object-Oriented Design, Sandi Metz, SOLID]
comments: true
date: 2017-07-11
---

# 📝 SOLID Object-Oriented Design[^1]

I have been commenting with _my colleague_ [**Alvaro Salazar**](https://twitter.com/xala3pa)) that I will try to see a more or less technical talk every day, usually related to Software Development, in general, and/or Data Science, in particular. Surely, there will be talks of greater depth, which will require me to dive into the complexities of the code. I do believe that it can be a good use of my time to listen to _inspirational_ people and ideas.

![](/images/99-bottles-of-oop.png)

In this line goes the talk today, by [**Sandi Metz**](https://www.sandimetz.com/), the author of the book [_99 Bottles of OOP_](https://www.sandimetz.com/99bottles) and recommended by Alvaro. Sandi begins to talk about _rigidity + brittleness + immobilize + viscosity_ concepts applied to our applications. It is very possible that an application that we are developing today may run the risk of "breaking" tomorrow with any small change, because of any dependencies among our components. Therefore, she talks to us about object-oriented design and [SOLID](http://butunclebob.com/ArticleS.UncleBob.PrinciplesOfOod) principles. As the _goal_ of this blog aims to help me/you (_at least me, in the first instance, and anyone to whom it can inspire_), I'm reproducing here a few brief notes on the concepts that compose the SOLID acronym, just as I have copied them in my [{{< awesome fab fa-evernote >}} Evernote](https://www.evernote.com/) while watching the video:

- **S - Single responsibility**: only one reason for a class to change.
- **O - Open/closed**: module should be open for extension but closed for modification.
- **L - Liskov substitution**: subclasses should be substitutable for their base classes.
- **I - Interface segregation**: many client specific interfaces better than a general purpose one.
- **D - Dependency inversion**: depend upon abstractions, not upon concretions.

All the above principles revolve around managing properly the dependencies that we can cause in our application.

Now, the video on [{{< awesome fab fa-youtube >}} YouTube](https://www.youtube.com/watch?v=v-2yFMzxqwU):

{{< youtube v-2yFMzxqwU>}}

Finally, I will take this sentence from Sandi:

>{{< awesome fa fa-quote-right >}} _**If your project succeeds, it will continue to cost you money.**_
>
>--Sandi Metz

[^1]: Originally posted [here](https://estraviz.github.io/estraviz2017/software%20design/SOLID-OO-Design/).
