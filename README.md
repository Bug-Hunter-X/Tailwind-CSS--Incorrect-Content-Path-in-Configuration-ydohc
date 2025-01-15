# Tailwind CSS Configuration Error: Incorrect Content Path

This repository demonstrates a common error encountered when configuring Tailwind CSS: specifying an incorrect path in the `content` option of your `tailwind.config.js` file. This leads to Tailwind not processing your HTML files correctly, resulting in styles not being applied.  The solution involves verifying and correcting the file path to point accurately to the location of your HTML and component files.

## Bug

The `bug.js` file contains a Tailwind configuration with an incorrect path in the `content` option.  This will prevent Tailwind from picking up the necessary HTML and component files for styling.

## Solution

The `bugSolution.js` file shows the corrected configuration with the correct path. Make sure the paths are relative to your `tailwind.config.js` file.

## Setup

1. Clone this repository.
2. Run `npm install` to install necessary dependencies.
3. Run your build process. Compare the output of both the `bug` and `bugSolution` configurations to see the difference.