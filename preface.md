# 🚀 Understanding Astro

By [Ohans Emmanuel](https://www.ohansemmanuel.com/)

<br />

## Introduction

I'm not one of those bandwagon-jumping folks who drool over every shiny new library or framework that hits the scene just because it's trending. I'm more of a "wait-and-see" kinda person.

So, you're probably wondering why I wrote a book about the reasonably new UI framework, Astro.

Well, let me tell you.

I’ve been in this game for almost a decade now, and I've seen frameworks come and go like a bad case of indigestion. And Astro will not live forever, either. Let’s be honest.

But here's the thing: when you use a new UI framework, it's not just about getting stuff to work and slapping some apps willy-nilly. No, no, no. The real magic lies in understanding the principles and concepts behind the framework's creation. And that's exactly the mindset I had when I wrote this book.

You’ve got to ask yourself: what makes this framework so unique? How is it different from all the other fluff out there? How can you apply its mental model to the bigger picture of developing applications for the web? Plus, what framework-agnostic principles can you pick up along the way?

The good news is I've got answers to all these burning questions sprinkled throughout the book like confetti.

Now, let's talk about performance, shall we? Of course, that’s a whole different ballgame depending on what kind of application you're dealing with. But for specific applications, e.g., content-focused applications, Astro is a total game-changer. Its performance defaults are off the charts!

The more I researched Astro, the more I was fascinated to write this book.

And here's the kicker: this book goes beyond just Astro. In specific chapters, we will discuss concepts you can apply to whatever framework you work with. And that's not just cool; that’s downright practical.

Astro is paving the way for a new architecture on the web: the component island architecture. And my goal is to help you understand it well enough to build some seriously robust production applications.

So, don't just scratch the surface. Instead, let’s dive deep and get to know this bad boy.

This is why I am writing this book. And hey, six months in, and I’m still loving it.

So, what are you waiting for? Grab your favourite drink (tea over coffee here), dig in, and let's get building!

Cheers 🥂

## Don’t be displeased

Okay, If you haven’t already noticed, I write like I speak. I use plain language and analogies that even my nan could (potentially) understand — when I do it right.

I respect your preferences for technical books, but this book does not read in a typical technical documentation style—sorry fellow nerds.

If this writing style bothers you, seems like a complete joke to you, or strikes the wrong chord, I advise we part ways now. Don’t read further. You’ll only get displeased even more.

Technical books should be easy on the eyes and a breeze to read. And why not have a bit of a laugh while we're at it?

If you're up for a good time while you learn a thing or two (well, a lot more), then let's get cracking!

Otherwise, bye, friend. No qualms.

## Differences to the official documentation

I find technical books that parrot the official documentation of the technology it aims to explain a waste of time.

As such, this book differs from the official documentation in a couple of ways:

- **The tone of writing**: this book adopts a non-technical documentation writing style for ease of understanding. Whether you appreciate this or not is left to your taste.

- **Doesn’t follow the Diataxis framework**: the Astro technical documentation is written following the [Diataxis](https://diataxis.fr/) framework. The framework suggests structuring content around four distinct types: tutorial, how-to-guide, explanation and reference.

  This book breaks out of this strict structure to emphasise understanding and practical learning. This book is not a reference and doesn’t aim to replace the official Astro references. In the Diataxis lingo, understanding Astro may be defined as a mix of how-to guides and a careful blend of tutorials with elaborate explanations interwoven.

- **Advanced usage**: some advanced Astro uses are tucked away in the official references - without explanations or practical examples. This is perfectly fine for a documentation site. Experienced engineers can spend time digging into these. However, this book bridges the gap.

  For example, consider building custom Astro integrations. You will not find a better (practical) resource than this book.

- **Real-world applications**: sometimes, to piece together a puzzle, it’s essential to see it at play in near real-world examples. This book explains important concepts and goes beyond that to put them to practice in comparative real-world examples.

- **Saves time**: This book will save you countless hours tinkering with references and code samples as a by-product of the above distinctions. Yes, you can spend hours digging deep into the docs or Astro source code, but I’ve spent hours (months, actually) doing so! Therefore, I can present the learnings without you doing as much of the work - don’t be fooled; you still have to do the work of reading the book.

> Consider reading (or skimming) the official documentation after reading this book or using it as a reference. This book complements the official docs, not replace them.

## How the book is structured

Every chapter in this book is one of the following:

1. A concept chapter
2. A project chapter
3. A project and concept chapter

The mix of these different chapter types will keep you engaged and make your learning effective. Remember, the goal is proper understanding.

### Concept chapters

<figure>
    <img src="images/concept@2x.png" width="70%" alt="Learn new concepts." align="center">
    <figcaption><em>Learn new concepts.</em></figcaption>
    <br><br><br>
</figure>

In concept chapters, we’ll learn the core concepts of Astro. These chapters will include code examples and throwaway applications. We will build no real-world projects in these chapters.

### Project chapters

<figure>
    <img src="images/build.png" width="70%" alt="Build real world projects." align="center">
    <figcaption><em>Build real world projects.</em></figcaption>
    <br><br><br>
</figure>

In project chapters, we’ll apply previous concepts we’ve learned towards building a near real-world project.

### Concept and project chapters

<figure>
    <img src="images/concept%20and%20build.png" width="70%" alt="Building and learning new concepts." align="center">
    <figcaption><em>Building and learning new concepts.</em></figcaption>
    <br><br><br>
</figure>

A project and concept chapter focuses on building a real-world application while introducing new concepts along the way.

## Chapters overview

Below’s a summary of the chapters of the book:

### Chapter 1: Build your first application with Astro

The book begins hands-on with a project and concept chapter.
In this chapter, we’ll learn the basics of Astro while building a feature-rich personal website.

### Chapter 2: Astro components in-depth

This is a concept chapter that goes in-depth into Astro components. We will go beyond the basics and master (arguably) the essential Astro entity.

We will start by exploring an argument to ditch the Javascript runtime overhead where appropriate. We will then study the behaviour of Astro component markup, styles and scripts, and the powerful template syntax.

### Chapter 3: Build your own component island

This project chapter moves away from Astro and considers the component island architecture in isolation.

We will consider an overview of application rendering, comprehend the island architecture from the ground up, and build our own implementation from scratch.

This chapter will solidify your fundamental knowledge of the new web performance-focused architecture pattern.

### Chapter 4: The Secret Life of Astro Component Islands

This is a concept chapter where we’ll get hands-on experience working with framework components in Astro. I’ll introduce you to responsible hydration and why it matters.

We will build many throwaway applications to explore how component islands work in Astro and why they are significant.

### Chapter 5: Oh My React! (The React Documentation Site Clone)

In this project and concept chapter, we will explore techniques for handling large amounts of content within an Astro application. Additionally, we will examine real-world use cases to provide practical examples.

This chapter will solidify the previous concepts learned and introduce some new ones while we build out a clone of the React documentation site with production best practices.

### Chapter 6: Server-side rendering (SSR) in Astro

This concept chapter will explore server-side rendering and the new features unlocked in an Astro server-side rendered application. We will explore dynamic routing, API endpoints, Server streaming, and much more.

### Chapter 7: Be Audible! (Full stack Astro Project)

This project chapter will take you beyond static sites into building fullstack applications with Astro. In this chapter, I’ll argue that if you can build the app as an MPA and leverage component islands, you can build it with Astro.

### Chapter 8: Build your own Astro integrations

This is a project and concept chapter where we’ll answer the question, what happens when you want a feature outside what Astro provides by default?

We will leverage hooks into Astro’s build process to build custom functionalities. These are called Astro integrations.

### Chapter 9: Conclusion

Here, we will step back and appreciate how far we’ve come. Then we will reiterate the features that make Astro stand out. Features you’ve already seen in practice!

This is where our journey likely ends, and your journey into the world of Astro begins.

## Prerequisites

I desperately tried to make this book “work for everyone”, but that’s incredibly difficult.

So, to make the best out of this book:

- You should already know some HTML, CSS and JS: this is not a web development beginner guide.
- You should already know the basics of Typescript: I don’t expect you to be a Typescript champion, however, surface-level understanding will prepare you for all the Typescript in the book.

I wrote this book specifically for Mid, Senior and Senior+ engineers, and the book contains chapters of varying technical difficulty. However, I’ve done my best to explain these clearly and visually to satisfy different skill levels.

## Typographic conventions

When text is written in a monospaced font, it typically represents code samples. These samples may be self-contained fragments or refer to a specific section of an application's code.

Below’s an example:

```js
---
const { author } = Astro.props;
const book = "Understanding Astro.js";
---

<h1 data-name={book}>A new book</h1>
```

Sometimes, to show the source of the code, a comment to the file path is added to the top of the code block, as shown below:

```js
{/** 📂 src/pages/index.astro **/}
---
const { author } = Astro.props;
const book = "Understanding Astro.js";
---

<h1 data-name={book}>A new book</h1>
```

With code fragments referring to changes in a nearby application code, you’ll find an ellipsis to signify no code changes in the previous code, e.g.:

```js
// ...
<h1 data-name={book}>A changed book name</h1>
```

The code above suggests the previous code block remains the same, except for the new `<h1>` with `A changed book name`.

Finally, the book uses the `npm` package manager. For example, the code to install a package will be described as shown below:

```js
npm install some-package
```

Please use the associating commands for other package managers, such as `yarn` or `pnpm`.

Phew! That’s enough housekeeping. Now, let’s dive into Astro!
