# Callbacks Example

This repository contains a simple example demonstrating the use of callbacks in JavaScript. The code creates an HTML document with a list of posts. Two functions, `getPost` and `createPost`, are used to simulate asynchronous operations with the help of `setTimeout`.

## Introduction

The HTML document showcases the use of callbacks in JavaScript to manage asynchronous operations. It defines an array of posts and two functions:

1. **getPost:** This function displays the list of posts after a delay of 1000 milliseconds using `setTimeout`.

2. **createPost:** This function simulates adding a new post to the array after a delay of 2000 milliseconds. It also accepts a callback function (`getPost`) to update the displayed posts.

## Usage

To run this example, follow these steps:

1. Clone the repository:

    ```bash
    git clone https://github.com/SilvaTechn/callbacks-in-JavaScript.git
    ```

2. Open the HTML file in a web browser.

    ```bash
    # Change directory to the cloned repository
    cd callbacks-in-JavaScript

    # Open the HTML file in a web browser
    ```

The posts will be displayed, and a new post will be added after a delay.
