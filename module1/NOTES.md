# About W3C and the Web

## Web Content Accessibility Guidelines

### Core Principles

> -   Perceivable

    - People can see the content or hear it

> -   Operable

    - Can use the computer by typing or voice

> -   Understandable

    - Get clear and simple language

> -   Robust

    - So people can use different assistive technologies

### Module 1

> # Tags
>
> -   HTML tags like `<p>`, `<h1>`, etc are not the elements themselves, rather they're the bits of text you use to tell the computer **where an element begins and ends.** When you "mark up" a document, you generally don't want those extra notes or "mark ups" that are not really part of the text to be presented to the reader. Similarly this is what tags are in HTML documents. They allow you to structure the html file on how they will be presented to the browser, or renderer of the html document. The structure of an HTML element is like this `<tag>{content}</tag>`, where `tag` is the opening tag and `</tag>` is the closing tag, and then `{content}` represents the content(a text or another html element) of that html element.

> -   Self closing tags like **`<img />`** are tags that usually represent an **element that is completely described by its attributes, and thus there is no need for other content.**

> # Markup
>
> -   [HTML](https://en.wikipedia.org/wiki/HTML) actually borrows the techniques from [SGML](https://en.wikipedia.org/wiki/Standard_Generalized_Markup_Language), to provide an easy way for a computer to determine which parts are **"MarkUp"** and which parts are the **content**.
> -   This is done by using `<` and `>` as a kind of parentheses(or delimiter in programming), HTML can indicate the beginning and end of a tag, that is, **the presence of `<` tells the browser 'this next bit is markup, pay attention'.**

# Key Understanding

> -   One **_key to understanding HTML, or any computer language_**, is to sure that you **avoid ambiguity**, because **_computers generally are not good at judgement calls_**.

> When a browser or client receives a file, it may know that it's receiving an HTML file, but it won't know which version of HTML is used(it matters). That's why **the first thing you need in any HTML file** is a **tag to tell you what type of HTML file it is**: **`<!DOCTYPE html>`**

> It may seem redundant, but the html tag tells the computer where the actual HTML code begins using **`<html>`**.
