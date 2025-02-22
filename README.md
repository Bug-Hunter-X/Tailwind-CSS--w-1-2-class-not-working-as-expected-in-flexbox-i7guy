# Tailwind CSS Flexbox Width Issue

This repository demonstrates a common issue encountered when using Tailwind CSS's width utility classes (`w-1/2`, `w-1/3`, etc.) within flexbox containers.

The problem arises because, by default, flex items only take up the space required by their content.  The `w-1/2` class doesn't force the element to occupy half the available width in a flex container.

The `bug.html` file showcases the problem, while `bugSolution.html` demonstrates a solution using the `flex-grow` utility class.

This issue is a valuable learning point when working with Tailwind CSS and flexbox layouts.  Understanding flexbox's default behavior is crucial for creating correctly sized elements within flex containers.