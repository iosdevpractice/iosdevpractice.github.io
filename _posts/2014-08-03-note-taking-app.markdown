---
layout: post
title:  "Note Taking App"
date:   2014-08-03 12:00:01
categories: practice
---

For our first practice exercise, we will build a simple note taking app from the following rough design. For double the fun, build it in both Objective-C and Swift.

Make it so.

## Basic Functionality

* users can enter and view notes
* notes have a modification date
* notes have text contents
* notes are saved between sessions

## Main Screen

* table view in navigation controller
* first line of note is used as the title
* table view cells show note title and modification date
* tapping on a cell pushes note detail screen
* new button in upper right displays detail screen as modal for adding a note
* edit button in upper left used to enter edit mode to delete and reorder notes

## Detail Screen

* show modification date
* show and edit note contents
* show done button in upper right if shown as modal
* show cancel button in upper left if shown as modal

## Wireframes

* [Main Screen](/images/note-taking-app-main.jpg)
* [Detail Screen](/images/note-taking-app-detail.jpg)
* [Adding a new note](/images/note-taking-app-new-note.jpg)

## Example Implementations

Don't cheat and look at these until you have created your own.

* [Objective-C](https://github.com/iosdevpractice/NoteTakingApp_Objective-C)
* [Swift](https://github.com/iosdevpractice/NoteTakingApp_Swift)


Discuss this exercise
[here](https://github.com/iosdevpractice/iosdevpractice_discussion/issues/1).
