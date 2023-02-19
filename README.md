# About *jbook*

jbook is a project that follows Stephen Grider's "React and TypeScript: Build a Portfolio Project" video course on Udemy.

## Features

The application that the jbook project resembles is an interactive notebook that accepts both text and code from the user. So, there are cells that can be added, deleted or moved up/down. 

Each text cell has a text editor and is based on Markdown syntax behind the scenes. Then the text renders according to Markdown styling user adds when they click outside the cell. 

Each code cell consists of an input and a preview pane. The user writes their JavaScript code inside the input pane, and then after a second, the code is executed automatically on the preview pane. 

The main purpose of this project is to create an interactive documentation on any JavaScript topic. But it can simply be used as a diary as well.

## Project scope

This repository follows the course until Section 21, in which the directory layout is radically changed. To keep the repository away from this radical change and make it reflect only the incremential changes throughout the course, I decided to stop committing here. As a result, the app holds the data until the page is refreshed or closed. There is no way to save the notebook created by using this app.

Section 21 and onwards solves this problem. If you are interested in the topic, I would recommend buying the course and follow the last five sections to complete the app.