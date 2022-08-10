# traversy-tailwind-course-project-4

This project is basic a testimonial website page built with TailwindCSS framework using GRID positioning from Brad Traversy`s Tailwind Course on Udemy.

## TailwindCSS Line Clamp

This project has an extra, it uses a **Tailwind** plugin called **Line Clamp** which reduces the number of lines in a testimonial box adding a **...** for read more. Its wraps the text in lines that goes from 1 to 5.

### Installing a TailwindCSS Plugin

To write this as an example we are using **Line Clamp**`s plugin install method.
- First we need to install the plugin, using the following command:
> $ npm install -D @tailwindcss/line-clamp

It will be installed and showed at our **package.json** file.

- Second we need to register the plugin into **tailwind.config.js** in the plugins section as the example bellow.

plugins: [require('@tailwindcss/line-clamp')],

Once we do that we can call **Line Clamps** by adding *line-clamp-(value from 1 to 5)*