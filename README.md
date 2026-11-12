# Task 9 – Laundry Services Hero Animation

A responsive laundry-service landing page with an animated hero image.

## Task requirements covered

- The hero image moves along a gentle oval/orbit path.
- The image rotates while moving.
- The image is squeezed and stretched at different points in the animation.
- The existing CTA button hover animation is retained.
- The page remains responsive on desktop, tablet, and mobile.
- Reduced-motion preferences are respected for accessibility.

## Project files

```text
task9-main/
├── index.html
├── style.css
└── README.md
```

## How to run

1. Extract the ZIP file.
2. Keep `index.html`, `style.css`, and `README.md` in the same folder.
3. Open `index.html` in a browser, or use VS Code Live Server.
4. Confirm that the washing-machine image loads (internet connection is needed for the external image).
5. Watch the hero image complete its orbit-and-squeeze animation.

## Animation details

The `@keyframes orbitSqueeze` rule in `style.css` combines `translate()`, `rotate()`, and `scale()` transforms. The scale values change in both the horizontal and vertical directions to create the squeeze/stretch effect. The animation repeats every 7 seconds.

## Technologies

- HTML5
- CSS3
- JavaScript (mobile navigation toggle)

## Note

The external washing-machine illustration requires an internet connection. You may replace its image URL in `index.html` with another image if needed.
