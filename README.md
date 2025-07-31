# Solutions to *The Rising Sea*

This repository contains my detailed solutions, annotations, and expanded commentary on  
**_The Rising Sea: Foundations of Algebraic Geometry_** by Ravi Vakil.

## 📘 Overview

The goal of this project is to:
- Write complete, rigorous solutions to exercises throughout the text
- Clarify and expand upon remarks, examples, and key constructions
- Provide structured, navigable LaTeX notes for long-term reference and revision

## 🗂 Structure

This project is organized by chapter:

- `All Chapters.tex` – Main file that compiles all content
- `Chapter 1.tex` – Solutions to Chapter 1: Category Theory
- `Chapter 2.tex` – Solutions to Chapter 2: Sheaves
- `Chapter 3.tex` – Solutions to Chapter 3: Schemes
- `Chapter 4.tex` – Solutions to Chapter 4: Morphisms of Schemes
- `topmatter.tex` – Title, formatting, and preamble setup
- `references.bib` – Bibliography file (for citations)

## 🛠 Build Instructions

To compile:

```bash
pdflatex "All Chapters.tex"
bibtex "All Chapters"
pdflatex "All Chapters.tex"
pdflatex "All Chapters.tex"
