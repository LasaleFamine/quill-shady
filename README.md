# [Quill](https://github.com/quilljs/quill) Rich Editor for ShadyDOM

> Wrapper of the 1.2.3 version of Quill with some fixes.

## Why

Working with Polymer 3 and ShadowDOM I have found some problems implementing Quill. I found a solution for getting a working editor: **ShadyDOM** & **Quill#1.2.3**.

But I had also problems with the **insert link** feature, I think also related to the **ShadyDOM** and the **Quill incompatibility** with it.

## What

This is a simple copy/paste of the **build** version of Quill, downloaded from **NPM**. I have fixed the two piece of code that were causing me the **insert link** problem.

## Install

    $ yarn add LasaleFamine/quill-shady

## Usage

Just the same as [Quill](https://github.com/quilljs/quill).
