# Do You Love Me? - Interactive Love Micro-Experience

<!-- MIT License -->

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](./LICENSE)

<!-- HTML & CSS -->

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)

<!-- Styling / PostCSS -->

[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?logo=tailwindcss&logoColor=white)](https://tailwindcss.com/docs/)
[![PostCSS](https://img.shields.io/badge/PostCSS-efefef?logo=postcss&logoColor=black)](https://postcss.org/)
[![daisyUI](https://img.shields.io/badge/daisyUI-5A0EF8?logo=tailwindcss&logoColor=white)](https://daisyui.com/)

<!-- Fonts & Icons -->

[![Google Fonts](https://img.shields.io/badge/Google_Fonts-4285F4?logo=google&logoColor=white)](https://fonts.google.com/)
[![Font Awesome](https://img.shields.io/badge/Font_Awesome-528DD7?logo=fontawesome&logoColor=white)](https://fontawesome.com/)

<!-- Languages & Web Standards -->

[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![ECMAScript Spec](https://img.shields.io/badge/ECMAScript-262-7A0BC0?logo=ecmascript&logoColor=white)](https://www.ecma-international.org/publications-and-standards/standards/ecma-262/)

## Plain docs links

- HTML (MDN) docs: https://developer.mozilla.org/en-US/docs/Web/HTML
- CSS (MDN) docs: https://developer.mozilla.org/en-US/docs/Web/CSS
- Tailwind CSS docs: https://tailwindcss.com/docs/
- PostCSS docs / postcss.config: https://postcss.org/ (see also Tailwind PostCSS install guide)
- daisyUI docs: https://daisyui.com/
- Google Fonts docs: https://fonts.google.com/
- Font Awesome docs: https://fontawesome.com/
- JavaScript (MDN) docs: https://developer.mozilla.org/en-US/docs/Web/JavaScript
- ECMAScript (spec, ECMA-262) docs: https://www.ecma-international.org/publications-and-standards/standards/ecma-262/

---

A small, playful interactive web micro-project that asks "Do you love me?" with evasive "No" behavior, a heart-loader animation, and a celebratory result. Ideal as a lightweight demo of DOM manipulation, CSS animations, and playful UX.

## Demo

Open [index.html](index.html) in a browser to try the demo.

## Features

- Evasive "No" button that avoids the cursor (fun interactive behavior).
- Smooth heart-loader built with pure CSS animations.
- Result view displays a looping video (`cute-love-gif.mp4`) when the user chooses "Yes".
- Lightweight: zero build tools, plain HTML/CSS/JS.

## How it works quick

- The UI is defined in [index.html](index.html).
- Interaction is implemented in [js/script.js](js/script.js) which exposes these key variables:
  - [`questionContainer`](js/script.js)
  - [`resultContainer`](js/script.js)
  - [`gifResult`](js/script.js)
  - [`heartLoader`](js/script.js)
  - [`yesBtn`](js/script.js)
  - [`noBtn`](js/script.js)

> The "No" button moves on `mouseover` to random positions inside the question container. Clicking "Yes" hides the question view, shows the heart loader for 3 seconds, then reveals the result container and plays the video.

## Project structure

- [index.html](index.html) - Entry page and layout.
- [css/styles.css](css/styles.css) - All styles and animations.
- [js/script.js](js/script.js) - Interaction logic.
- cute-love-gif.mp4 - Result video (place in project root).

## Installation and Usage

1. Clone or download this repository.
2. Ensure `cute-love-gif.mp4` is in the project root (or update the path in [index.html](index.html)).
3. Open [index.html](index.html) in any modern browser (no server required).

## Github:

1. **git clone:**

```bash
git clone https://github.com/md-abu-kayser/do-you-love-me.git

```

2. **git pages link:**

```bash
https://md-abu-kayser.github.io/do-you-love-me/

```

### Customization Ideas

- Add accessibility improvements (keyboard support and ARIA attributes).
- Make the "No" button movement constrained to visible bounds to avoid overflow.
- Replace the video with an optimized GIF or WebM for smaller size.
- Add responsive size tweaks for smaller screens.

### Contributing

- Small tweaks and UX improvements are welcome. Fork the repo, create a feature branch, and open a PR.

### License

- This project is licensed under the terms of the **[MIT License](./LICENSE)**.
- You may replace or update the license as needed for client or proprietary projects.

---

### Contact & Maintainer

- **_Project:_** _do-you-love-me_
- **_Name:_** Md Abu Kayser - Full-Stack Engineer
- **_Maintainer:_** [md-abu-kayser](https://github.com/md-abu-kayser)
- **_GitHub:_** [github.com/abu.kayser-official](https://github.com/md-abu-kayser)
- **_Email:_** [abu.kayser.official@gmail.com](mailto:abu.kayser.official@gmail.com)

If you’d like this README tailored for a specific purpose - such as **hiring managers**, **open-source contributors**, or **client deliverables** - feel free to request a custom tone or format.

---

**Thank you for reviewing this small, playful interactive web micro-project!**

---
