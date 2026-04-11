---
title: 'Markup Languages. LaTeX.'
date: 2026-04-11
---

## What is a Markup Language?

A markup language is a system for annotating text so that the computer can 
format and display it in a specific way. Unlike programming languages, markup 
languages describe the structure and presentation of content rather than 
defining logic or behavior. Common examples include HTML for web pages and 
Markdown for documentation.

## What is LaTeX?

LaTeX (pronounced "lah-tech" or "lay-tech") is a high-quality typesetting 
system widely used in academia, science, and engineering. It was created by 
Leslie Lamport in the 1980s as an extension of TeX, a typesetting system 
developed by Donald Knuth.

Unlike word processors such as Microsoft Word, LaTeX works on a 
"what you see is what you mean" principle. You write plain text with markup 
commands, and LaTeX handles all the formatting automatically.

## Why Use LaTeX?

LaTeX is the standard tool for writing academic papers, theses, and scientific 
documents for several reasons:

- **Beautiful typography**: LaTeX produces professionally typeset documents 
  that are visually superior to most word processors.
- **Math support**: it handles complex mathematical equations effortlessly, 
  which is why it is the go-to tool in mathematics, physics, and engineering.
- **Consistency**: formatting is applied automatically and consistently 
  throughout the entire document.
- **References and citations**: managing bibliographies and cross-references 
  is much easier compared to doing it manually.

## Basic Structure of a LaTeX Document

```latex
\documentclass{article}

\title{My First Document}
\author{Ivan Kabanov}
\date{\today}

\begin{document}

\maketitle

\section{Introduction}
This is my first LaTeX document. 

\section{Math Example}
The quadratic formula is:
\[ x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a} \]

\end{document}
```

## Common Commands

| Command | Purpose |
|---|---|
| `\section{}` | Create a section heading |
| `\textbf{}` | Bold text |
| `\textit{}` | Italic text |
| `\begin{itemize}` | Start a bullet list |
| `\frac{}{}` | Write a fraction |
| `\sqrt{}` | Write a square root |

## Where to Start

The easiest way to get started with LaTeX without installing anything is 
[Overleaf](https://www.overleaf.com), a free online LaTeX editor that 
compiles your document in real time right in the browser. It is perfect 
for students writing reports, assignments, or theses.

LaTeX has a bit of a learning curve at first, but once you get the hang of 
it, you will never want to go back to a regular word processor for academic 
writing!
