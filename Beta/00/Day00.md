Piscine Swift - Day 00

# Welcome to Swift, Drink Up!

#### Michael BRAVE [mbrave@student.42.us.org](mailto:mbrave@student.42.us.org)

#### 42 Staff [pedago@42.fr](mailto:pedago@42.fr)

_Summary: This document contains the subject for Day 00 for the "Piscine Swift" from 42_
\pagebreak

# Contents

### I Foreword

### II General Instructions

### III Introduction

### IV Exercise 00: The Basics

### V Exercise 01: You Are Awesome ("Hello World")

### VI Exercise 02: Buttons That Do Things

### VII Exercise 03: Stay Hydrated App

### VIII Bonus: Adding Animations & Graphics

\pagebreak

# Chapter I

# Foreword

**Why Swift?**

It’s hard for me to explain what swift as a language is, harder still to separate out where the language ends and xcode begins. But if I was to give it a go I would say "Swift is what happens when someone decides to rewrite C++ from the ground up while implementing best use cases from other languages". As for where it fits in our modern ecosystem It’s easiest to compare it to Rust, as it’s a safer, but lowish level language, but it’s significantly more usable and human friendly than Rust. So what we have is something that is C like, heavily inspired by and plays well with Objective-C, has memory safety features built in as default (but can be overridden when needed), a higher level inspired syntax that is comparable in speed to C++/Rust and it’s open source while still being significantly contributed to by Apple. There are also the added functionality of being able to compile into .o files so it is compatible with C/Objective-C libraries (C++ works using an objective-C wrapper, but should work more natively in the future). Later due to google’s work in using it in tensorflow(tensorswift or “Swift for Tensorflow”) there are also the added capabilities of using python libraries too. I feel the language strikes the right balance of usability/speed/adaptability and being able to build on the current toolsets available. So far it’s a language that is mostly used for IOS development (though some mention of server side swift is warranted) which is why this training focuses on IOS development. I believe that someday Swift will be used more as a common general purpose language, and I think the world will be a happier place for it.

For me Swift has been a joy to learn and to use and I hope you enjoy learning this language as I have. Let’s make some apps.

-Mike Brave
\pagebreak

# Chapter II

# General Instructions

- Only this document will serve as reference. Do not trust rumors.

- Read carefully the whole subject before beginning.

- Watch out! This document could potentially change up to an hour before submission.

- This project will be corrected by humans only.

- This course is designed to build on previous days’ concepts, try your hardest to finish everyday.

- Each day culminates in a portfolio piece, if you finish the day this is something you can use to get hired.

- Unless otherwise stated we are creating single page apps using xcode.

- When submitting, submit the folder of the Xcode project.

- Only the work submitted on the repository will be accounted for during peer-2-peer correction.

- Warning: you can only make 10 apps to test on a physical phone every 7 days

- Here it is the [official manual of Swift](https://docs.swift.org/swift-book/) and the [Swift Standard Library](https://developer.apple.com/documentation/swift/swift_standard_library)

- It is forbidden to use other libraries, packages, pods, etc. Unless otherwise stated in the project.

- Got a question? Ask your peer on the right. Otherwise, try your peer on the left.

- You can discuss on the Piscine forum of your Intra!

- By Odin, by Thor! Use your brain!!!
  \pagebreak

# Chapter III

# Introduction

First we will be learning how to use Xcode, although building things in swift without Xcode is possible since it’s open source and works in linux, for the purposes of building IOS, OSX and other Apple related apps it’s not recommended as a viable solution at this time.

We will build some simple applications today learning how to use Xcode’s Auto-layout and the swift language itself.

Each assignment was designed to build on the previous assignments knowledge and culminate in a portfolio piece. Those who complete the day’s assignments will have a portfolio piece that reminds the user to drink enough water everyday and keep track of how much we’ve consumed.
\pagebreak

# Chapter IV

# Exercise 00 : The Basics

<table>
  <tr>
    <td>Exercise : 00</td>
  </tr>
  <tr>
    <td>The Basics</td>
  </tr>
  <tr>
    <td>Files to turn in: .xcodeproj and all necessary files</td>
  </tr>
  <tr>
    <td>Allowed functions : Swift Standard Library, UIKit</td>
  </tr>
  <tr>
    <td>Notes : n/a</td>
  </tr>
</table>

For this first exercise we are going to create a new playground and learn some of the core concepts of swift.

Playgrounds can function much like scratch paper for programming out concepts. We will not use them later but felt there should be at least an introduction to them. This is also a great chance to play with the language before getting bogged down in the nuances of xcode.

In the playground we are going to create and use a class that will include 2 variables, a constant and a function (think of the class filling a similar role to a struct). We will set the values to the variables after but for now set them to be string type. Then at the end call the function which will display something along the lines of "Hi my name is (student) I go to school at (school) and I am level (level)".
\pagebreak

# Chapter V

# Exercise 01 : You Are Awesome ("Hello World")

<table>
  <tr>
    <td>Exercise : 01</td>
  </tr>
  <tr>
    <td>You Are Awesome</td>
  </tr>
  <tr>
    <td>Files to turn in: .xcodeproj and all necessary files</td>
  </tr>
  <tr>
    <td>Allowed functions : Swift Standard Library, UIKit</td>
  </tr>
  <tr>
    <td>Notes : n/a</td>
  </tr>
</table>

For this first exercise we are learning to create a project (a single view app), how to display text to the screen and how to make a functional button. The trick of this assignment is learning how to navigate Xcode.

Create a new iOS app with a UIButton in the main view. When the button is clicked, a message will be displayed in Xcode’s debug console and in a UILabel.

The message can say whatever you like, I recommend telling yourself how awesome you are.
\pagebreak

# Chapter VI

# Exercise 02 : Buttons That Do Things

<table>
  <tr>
    <td>Exercise : 02</td>
  </tr>
  <tr>
    <td>Buttons That Do Things</td>
  </tr>
  <tr>
    <td>Files to turn in: .xcodeproj and all necessary files</td>
  </tr>
  <tr>
    <td>Allowed functions : Swift Standard Library, UIKit</td>
  </tr>
  <tr>
    <td>Notes : n/a</td>
  </tr>
</table>

Now it’s not enough to have just one button, we need four. Also Apps should work in both landscape and portrait mode. Lucky for us swift/Xcode has tools like autolayout to help us.

Our app should have as follows:

1. Four buttons side by side and on top of one another that adapt to the rotation of the screen and change size relationally to the other elements of the page.

2. A UILabel with text inside of it, that changes fonts depending on which button was pressed.

Pro Tip: Look up StackView, and see if you want to use it with autolayout.
\pagebreak

# Chapter VII

# Exercise 03: Stay Hydrated App

<table>
  <tr>
    <td>Exercise : 03</td>
  </tr>
  <tr>
    <td>Stay Hydrated App</td>
  </tr>
  <tr>
    <td>Files to turn in: .xcodeproj and all necessary files</td>
  </tr>
  <tr>
    <td>Allowed functions : Swift Standard Library, UIKit (CAEmitterLayer / CAEmitterCell), SpriteKit</td>
  </tr>
  <tr>
    <td>Notes : n/a</td>
  </tr>
</table>

Staying hydrated is important.

This assignment is to build an app that uses everything we’ve learned up until this point and also use notifications and timers.

Our App Should:

- Keep track of how much water has already been drunk that day.

- Visually represent how much water in reference to the daily goal (8 cups).

- Reset the amount at the end of the day

- Use notifications to remind you to drink more water (on a schedule).
  \pagebreak

# Chapter VIII

# Bonus : Adding Animations & Graphics

<table>
  <tr>
    <td>Bonus</td>
  </tr>
  <tr>
    <td>Adding Animations & Graphics</td>
  </tr>
  <tr>
    <td>Files to turn in: .xcodeproj and all necessary files</td>
  </tr>
  <tr>
    <td>Allowed functions : Swift Standard Library, UIKit, Spritkit, Anything You feel is appropriate</td>
  </tr>
  <tr>
    <td>Notes : n/a</td>
  </tr>
</table>

Your stay hydrated app is your first IOS portfolio piece, make it look nice, give it the bells and whistles you wish it had, add some neat animations. Make it shine.
\pagebreak
