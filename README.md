# 💬 Whispering MICROWAVE Blog Post Template

This repository contains the files for a simple, visually engaging blog post template based on the humorous story "Whispering MICROWAVE."

## 🚀 Overview

This template is built using basic HTML and CSS, designed to be a standalone, single-page blog post with custom typography and a distinct color scheme (purples and complementary yellow).

## 📁 Files in This Repository

| File Name | Description |
| :--- | :--- |
| `index.html` | The main HTML structure of the blog post. |
| `style.css` | The CSS file defining the layout, styling, and typography. |
| `logo.png` | The favicon image (a purple "beta" symbol). |
| `image-1.jpg` | A background image with abstract purple shapes, used in the header (`.image-1`). |
| `image-2.jpg` | The main illustrative image showing a microwave with a Bluetooth speaker on top, central to the story. |
| `fonts/` | (Assumed directory) Contains the custom font files (`boorush.ttf`, `floren.otf`, `nunito.ttf`) used for styling. |
| `README.md` | This file. |

## 🎨 Key Design Features

* **Custom Typography:** Utilizes custom fonts (`Boorush`, `Floren`, `Nunito`) for distinct titles and body text.
* **Color Palette:** Dominated by a vivid purple (`rgb(134, 43, 226)` / `rgb(191, 57, 239)`) contrasting with a creamy background and hints of yellow (`rgb(239, 203, 57)`).
* **Absolute Positioning:** Many elements are positioned using `position: absolute` and explicit `top`/`left` coordinates, which may require careful adjustment for different screen sizes (though `vw` and `vh` units are used to provide some responsiveness).
* **Stylized Sections:** Features a distinct footer section (`.last-block`) with checkmark bullet points.

## 📝 Customization
* **Content:** Edit the text within the <p> tags in index.html.
* **Styling:** Modify colors, fonts, and layout properties in style.css. Pay attention to the absolute positioning used in the main content areas.
* **Images:** Replace image-2.jpg with your own assets, updating the file names in index.html and style.css as necessary. But I do not recommend changing image-1.png and logo.png, they are what keep the page organized!
