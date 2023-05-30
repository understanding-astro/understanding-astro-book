<h1 align="center">
  <a target="_blank" href="http://ohans.me/understanding-astro">
    <img src="images/book-cover-transparent.png" alt="Understanding Astro book cover" title="Understanding Astro" width="75%">
  </a>
</h1>

<br />

> Welcome to Understanding Astro!

This book is the ultimate guide to Astro. It represents months of work digging into Astro and conveying that to you in a practical and easy to understand fashion.

If you want to understand Astro, you've come to the right source.

## Want to download the ebooks? Click here

<br />

# ✨ Table of contents ✨

The following is a detailed table of contents for Understanding Astro.

<figure>
    <br>
    <img src="images/intro.png" alt="Introduction">
</figure>

## Introduction

- ### [Don't be displeased](https://github.com/understanding-astro/understanding-astro-book/blob/master/preface.md#dont-be-displeased)
- ### [Differences to the official documentation](https://github.com/understanding-astro/understanding-astro-book/blob/master/preface.md#differences-to-the-official-documentation)

- ### [How the book is structured](https://github.com/understanding-astro/understanding-astro-book/blob/master/preface.md#how-the-book-is-structured)
- ### [Chapters overview](https://github.com/understanding-astro/understanding-astro-book/blob/master/preface.md#chapter-overview)

- ### [Typographic conventions](https://github.com/understanding-astro/understanding-astro-book/blob/master/preface.md#typographic-conventions)

<figure>
    <br>
    <img src="images/ch-1.png" alt="Chapter 1: Build your first Astro Application">
</figure>

## [Chapter 1: Build your first Astro Application](#chapter-1-build-your-first-astro-application)

- ### [What you’ll learn](#what-youll-learn)
- ### [Project Overview](#project-overview)
- ### [Getting started](#getting-started)
  - #### [Install Node.js](#install-nodejs)
  - #### [Setting up your code editor](#setting-up-your-code-editor)
- ### [Project structure](#project-structure)
  - #### [tsconfig.json](#tsconfigjson)
  - #### [package.json](#packagejson)
  - #### [package-lock.json](#package-lockjson)
  - #### [astro.config.mjs](#astroconfigmjs)
  - #### [src/env.d.ts](#srcenvdts)
  - #### [src/pages/index.astro](#srcpagesindexastro)
- ### [Introduction to Astro pages](#introduction-to-astro-pages)
- ### [Anatomy of an Astro component](#anatomy-of-an-astro-component)
- ### [Component styles](#component-styles)
- ### [Page layouts](#page-layouts)
- ### [Rendering components and slots](#rendering-components-and-slots)
- ### [Capitalising component names](#capitalising-component-names)
- ### [The global style directive](#the-global-style-directive)
- ### [Custom fonts and global CSS](#custom-fonts-and-global-css)
- ### [Independent Astro components](#independent-astro-components)
- ### [Adding interactive scripts](#adding-interactive-scripts)
- ### [Interactive theme toggle](#interactive-theme-toggle)
- ### [The :global() selector](#the-global-selector)
- ### [Event Handling](#event-handling)
- ### [Theming via CSS variables](#theming-via-css-variables)
- ### [Accessing global client objects](#accessing-global-client-objects)
- ### [The magic of scripts](#the-magic-of-scripts)
- ### [Leveraging inline scripts](#leveraging-inline-scripts)
- ### [Global selectors in scripts](#global-selectors-in-scripts)
- ### [Markdown pages](#markdown-pages)
- ### [Navigating between pages](#navigating-between-pages)
- ### [Markdown layouts](#markdown-layouts)
- ### [Composing layouts](#composing-layouts)
- ### [Component props](#component-props)
- ### [Leveraging markdown frontmatter properties](#leveraging-markdown-frontmatter-properties)
- ### [Interactive navigation state](#interactive-navigation-state)
- ### [Component composition](#component-composition)
- ### [The template flow of data](#the-template-flow-of-data)
- ### [The dark side of define:vars](#the-dark-side-of-definevars)
- ### [Loading multiple local files](#loading-multiple-local-files)
- ### [Deploying a static Astro site](#deploying-a-static-astro-site)

  - #### [1. Create static production assets](#1-create-static-production-assets)
  - #### [2. Serve the static assets via a static web server](#2-serve-the-static-assets-via-a-static-web-server)
  - #### [The problem with manual deployments](#the-problem-with-manual-deployments)
  - #### [Automating the deployment of a static website](#automating-the-deployment-of-a-static-website)

- ### [How fast is our Astro website?](#how-fast-is-our-astro-website)
- ### [Conclusion](#conclusion)

<figure>
    <br>
    <img src="images/ch-2.png" alt="Chapter 1: Build your first Astro Application">
</figure>

## Chapter 2: Astro Components In-depth

- ### What you'll learn
- ### Introduction
- ### The backbone of Astro
  - #### The Javascript runtime fatigue
  - #### Ditching the runtime
- ### What is an Astro component?

  - #### An astro component is a .astro file capable of rendering any valid HTML
  - #### Astro components can be composed to make complex pages
    - Styles are local by default
    - The HTML element will always be present
    - Styles and Scripts are Hoisted
    - The `<head>` element and its children will not be hoisted
  - #### Astro components can leverage a powerful templating syntax

    - Consuming variables
    - Create dynamic attributes
    - Dynamic HTML
    - Dynamic Tags
    - Revisiting Slots
    - Not quite JSX

- ### Conclusion

## Chapter 3: Build your own Component Island

- ### What you’ll learn
- ### A brief history of how we got here
  - #### Where it all begins
  - #### Client-side rendering (CSR)
    - The pros of client-side rendering (CSR)
    - The cons of client-side rendering
  - #### Server-side rendering
    - The pros of server-side rendering
    - The cons of server-side rendering
  - #### Partial hydration for the win
    - The pros of partial hydration
    - The cons of partial hydration
  - #### Where does the island architecture come from?
- ### A partial hydration islands architecture implementation
  - #### Objectives
  - #### Installation
  - #### API design

## Chapter 4: The Secret Life of Astro Component Islands

## Chapter 5: Oh my React!

## Chapter 6: Server-side Rendering (SSR) in Astro

<figure>
    <br>
    <img src="images/ch-7.png" alt="Chapter 1: Build your first Astro Application">
</figure>

## [Chapter 7: Be Audible! (Fullstack Astro Project)](https://github.com/understanding-astro/understanding-astro-book/blob/master/ch7.md)

- ## [What you’ll learn](https://github.com/understanding-astro/understanding-astro-book/blob/master/ch7.md#what-youll-learn)

- ## [Project setup](https://github.com/understanding-astro/understanding-astro-book/blob/master/ch7.md#project-setup)

- ## [Project overview](https://github.com/understanding-astro/understanding-astro-book/blob/master/ch7.md#project-overview)

  - ### [The homepage](https://github.com/understanding-astro/understanding-astro-book/blob/master/ch7.md#the-homepage)
  - ### [The record page](https://github.com/understanding-astro/understanding-astro-book/blob/master/ch7.md#the-record-page)
  - ### [The signup page](https://github.com/understanding-astro/understanding-astro-book/blob/master/ch7.md#the-signup-page)
  - ### [The sign-in page](https://github.com/understanding-astro/understanding-astro-book/blob/master/ch7.md#the-sign-in-page)
  - ### [Helper components and utilities](https://github.com/understanding-astro/understanding-astro-book/blob/master/ch7.md#helper-components-and-utilities)

- ## [Technology choices](https://github.com/understanding-astro/understanding-astro-book/blob/master/ch7.md#technology-choices)

- ## [Backend setup](https://github.com/understanding-astro/understanding-astro-book/blob/master/ch7.md#backend-setup)

- ## [Handling authentication](https://github.com/understanding-astro/understanding-astro-book/blob/master/ch7.md#handling-authentication)

  - ### [Initialising firebase on the client](https://github.com/understanding-astro/understanding-astro-book/blob/master/ch7.md#initialising-firebase-on-the-client)
  - ### [Using the Firebase emulators](https://github.com/understanding-astro/understanding-astro-book/blob/master/ch7.md#using-the-firebase-emulators)
  - ### [Handling user signups](https://github.com/understanding-astro/understanding-astro-book/blob/master/ch7.md#handling-user-signups)
  - ### [Handling user sign in](https://github.com/understanding-astro/understanding-astro-book/blob/master/ch7.md#handling-user-sign-in)

- ### [Implementing protected pages](https://github.com/understanding-astro/understanding-astro-book/blob/master/ch7.md#implementing-protected-pages)

  - ### [Initialising Firebase on the server](https://github.com/understanding-astro/understanding-astro-book/blob/master/ch7.md#initialising-firebase-on-the-server)
  - ### [Protecting the home page route](https://github.com/understanding-astro/understanding-astro-book/blob/master/ch7.md#protecting-the-home-page-route)
  - ### [Updating the redirect URL](https://github.com/understanding-astro/understanding-astro-book/blob/master/ch7.md#updating-the-redirect-url)
  - ### [Log out a user from the protected page](https://github.com/understanding-astro/understanding-astro-book/blob/master/ch7.md#log-out-a-user-from-the-protected-page)

- ## [Cloud storage setup](https://github.com/understanding-astro/understanding-astro-book/blob/master/ch7.md#cloud-storage-setup)

- ## [Uploading audio recordings](https://github.com/understanding-astro/understanding-astro-book/blob/master/ch7.md#uploading-audio-recordings)

  - ### [Handling uploads via an API route](https://github.com/understanding-astro/understanding-astro-book/blob/master/ch7.md#handling-uploads-via-an-api-route)
  - ### [Uploading recordings from the client](https://github.com/understanding-astro/understanding-astro-book/blob/master/ch7.md#uploading-recordings-from-the-client)
  - ### [Reacting to UI changes in framework components](https://github.com/understanding-astro/understanding-astro-book/blob/master/ch7.md#reacting-to-ui-changes-in-framework-components)

- ## [Fetching data from the server](https://github.com/understanding-astro/understanding-astro-book/blob/master/ch7.md#fetching-data-from-the-server)

- ## [Submitting HTML forms](https://github.com/understanding-astro/understanding-astro-book/blob/master/ch7.md#submitting-html-forms)

- ## [Conclusion](https://github.com/understanding-astro/understanding-astro-book/blob/master/ch7.md#conclusion)

<figure>
    <br>
    <img src="images/ch-8.png" alt="Chapter 1: Build your first Astro Application">
</figure>

- ## [Chapter 8: Build Your Own Astro Integrations](https://github.com/understanding-astro/understanding-astro-book/blob/master/ch8.md#chapter-8-build-your-own-astro-integrations)

- ## [What you’ll learn](https://github.com/understanding-astro/understanding-astro-book/blob/master/ch8.md#what-youll-learn)

- ## [Astro and Vite](https://github.com/understanding-astro/understanding-astro-book/blob/master/ch8.md#astro-and-vite)

- ## [What are Astro integrations](https://github.com/understanding-astro/understanding-astro-book/blob/master/ch8.md#what-are-astro-integrations)

- ## [Hello world. Sorry, Hello, Integration](https://github.com/understanding-astro/understanding-astro-book/blob/master/ch8.md#hello-world-sorry-hello-integration)

  - ### [Project objective](https://github.com/understanding-astro/understanding-astro-book/blob/master/ch8.md#project-objective)
  - ### [Your first custom integration](https://github.com/understanding-astro/understanding-astro-book/blob/master/ch8.md#your-first-custom-integration)
  - ### [Printing a message to the server console](https://github.com/understanding-astro/understanding-astro-book/blob/master/ch8.md#printing-a-message-to-the-server-console)
  - ### [Custom integrations as factory functions](https://github.com/understanding-astro/understanding-astro-book/blob/master/ch8.md#custom-integrations-as-factory-functions)

- ## [The Astro hooks lifecycle](https://github.com/understanding-astro/understanding-astro-book/blob/master/ch8.md#the-astro-hooks-lifecycle)

  - ### [The when and why of hooks](https://github.com/understanding-astro/understanding-astro-book/blob/master/ch8.md#the-when-and-why-of-hooks)
  - ### [Examining the hooks evaluation order](https://github.com/understanding-astro/understanding-astro-book/blob/master/ch8.md#examining-the-hooks-evaluation-order)

- ## [Build a default prerender integration](https://github.com/understanding-astro/understanding-astro-book/blob/master/ch8.md#build-a-default-prerender-integration)

  - ### [Project objective](https://github.com/understanding-astro/understanding-astro-book/blob/master/ch8.md#project-objective-1)
  - ### [Integration API](https://github.com/understanding-astro/understanding-astro-book/blob/master/ch8.md#integration-api)
  - ### [Technical solution overview](https://github.com/understanding-astro/understanding-astro-book/blob/master/ch8.md#technical-solution-overview)
  - ### [Initialising projects via CLI flags](https://github.com/understanding-astro/understanding-astro-book/blob/master/ch8.md#initialising-projects-via-cli-flags)
  - ### [Setting up the integration](https://github.com/understanding-astro/understanding-astro-book/blob/master/ch8.md#setting-up-the-integration)
  - ### [Validating a resolved Astro configuration](https://github.com/understanding-astro/understanding-astro-book/blob/master/ch8.md#validating-a-resolved-astro-configuration)
  - ### [Applying Vite plugins in custom integrations](https://github.com/understanding-astro/understanding-astro-book/blob/master/ch8.md#applying-vite-plugins-in-custom-integrations)
  - ### [Writing Vite plugins for Astro](https://github.com/understanding-astro/understanding-astro-book/blob/master/ch8.md#writing-vite-plugins-for-astro)
  - ### [Parsing and transforming ASTs](https://github.com/understanding-astro/understanding-astro-book/blob/master/ch8.md#parsing-and-transforming-asts)
  - ### [Manual testing](https://github.com/understanding-astro/understanding-astro-book/blob/master/ch8.md#manual-testing)

- ## [Building renderers and library Integrations](https://github.com/understanding-astro/understanding-astro-book/blob/master/ch8.md#building-renderers-and-library-integrations)

- ## [Conclusion](https://github.com/understanding-astro/understanding-astro-book/blob/master/ch8.md#conclusion)

## Conclusion
