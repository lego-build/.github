# Lego Build

![Logo](https://honeysuckle-seat-ff8.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F52c65f85-50f8-41c0-a2b9-5395121cd471%2FNotionIcon.png?table=block&id=c70fed83-ed58-441c-8e20-1e59f04d0578&spaceId=4d429720-3a01-4110-bdd0-27238aaec84d&width=250&userId=&cache=v2)

### Overview (vision) 

lego-build aims to make development fun again by automating routine tasks, like creating special files and folders that have the same boilerplate code or pattern. It also aims to be extremely flexible and extendable. The idea is that the power lies in the hands of the developer.

## The Problem

Building large react applications is **hard**. There’s a lot of boilerplate code that goes into it. Want to create just a small component? You have to create about 3 or 4 files — the component file, a CSS file, an index file, and in some cases a test file. Now imagine doing this about 10 different times for a React project with 10 components (which could even be considered a small project!). It’s worse when you begin adding extra libraries like Redux. Need a new state? Create a new file (reducer) or even two! (plus an action). To someone just starting out with React, this problem may seem trivial, but someone who has built several React apps understands how repetitive, boring and time consuming creating all these files and boilerplate code can be. The solution? Us!

## The Solution

Imagine a tool that allows you create all 3 or 4 files needed to make your react component — in just one line! Need a new redux reducer? Run the command easily in your terminal and have the file plus the boilerplate already written for you. What if the tool also allowed you have your own commands for your own ‘special’ files or folders? For example, say you’re following the atomic model in designing, what if you could extend the tool easily, in a way that you can easily create an atom, molecule, or organism in just one line? We are this tool! **A tool that could be bent to the will of the developer** and can adapt to whatever project structure you need.

## The Philosophy

React is unopinionated. You’ve probably heard this a million times. The implication is that while every developer tries to maintain some structure while working, each structure is different, so a tool to create React ‘special’ files and folders needs to be flexible. Though react is unopinionated, there’s something common to all React projects, it’s these ‘special’ files and folders that bring the app to life. It could be a component folder, a component file, a page folder, an atom, a molecule, a reducer, a hook etc. We call these ‘special’ structures building blocks, or just blocks for short. Every React project is made up of them, without them, the app doesn’t exist. So lego-build is a tool that helps you easily make such blocks, or mould them.

## The Features

- A flexible, easy to use tool that can be used to mould react blocks.
- Start with as little configuration as possible.
- Easy to understand docs.
- Rename blocks easily.
- A platform that allows people share templates to support different folder structures.
- An aesthetic and user friendly CLI
