```
 ▄▄▄▄▄▄▄ ▄▄▄▄▄▄▄ ▄▄▄ ▄▄▄     ▄     ▄ ▄▄▄ ▄▄    ▄ ▄▄▄▄▄▄  
█       █       █   █   █   █ █ ▄ █ █   █  █  █ █      █ 
█▄     ▄█   ▄   █   █   █   █ ██ ██ █   █   █▄█ █  ▄    █
  █   █ █  █▄█  █   █   █   █       █   █       █ █ █   █
  █   █ █       █   █   █▄▄▄█       █   █  ▄    █ █▄█   █
  █   █ █   ▄   █   █       █   ▄   █   █ █ █   █       █
  █▄▄▄█ █▄▄█ █▄▄█▄▄▄█▄▄▄▄▄▄▄█▄▄█ █▄▄█▄▄▄█▄█  █▄▄█▄▄▄▄▄▄█ 
 ▄▄▄▄▄▄▄ ▄▄▄▄▄▄▄ ▄▄▄▄▄▄▄ 
█       █       █       █
█       █  ▄▄▄▄▄█  ▄▄▄▄▄█
█     ▄▄█ █▄▄▄▄▄█ █▄▄▄▄▄ 
█    █  █▄▄▄▄▄  █▄▄▄▄▄  █
█    █▄▄ ▄▄▄▄▄█ █▄▄▄▄▄█ █
█▄▄▄▄▄▄▄█▄▄▄▄▄▄▄█▄▄▄▄▄▄▄█
 ▄▄▄▄▄▄▄ ▄▄   ▄▄ ▄▄▄▄▄▄▄ ▄▄▄▄▄▄ ▄▄▄▄▄▄▄ ▄▄▄▄▄▄▄ ▄▄   ▄▄ ▄▄▄▄▄▄▄ ▄▄▄▄▄▄▄ ▄▄▄▄▄▄▄ 
█       █  █ █  █       █      █       █       █  █ █  █       █       █       █
█       █  █▄█  █    ▄▄▄█  ▄   █▄     ▄█  ▄▄▄▄▄█  █▄█  █    ▄▄▄█    ▄▄▄█▄     ▄█
█     ▄▄█       █   █▄▄▄█ █▄█  █ █   █ █ █▄▄▄▄▄█       █   █▄▄▄█   █▄▄▄  █   █  
█    █  █   ▄   █    ▄▄▄█      █ █   █ █▄▄▄▄▄  █   ▄   █    ▄▄▄█    ▄▄▄█ █   █  
█    █▄▄█  █ █  █   █▄▄▄█  ▄   █ █   █  ▄▄▄▄▄█ █  █ █  █   █▄▄▄█   █▄▄▄  █   █  
█▄▄▄▄▄▄▄█▄▄█ █▄▄█▄▄▄▄▄▄▄█▄█ █▄▄█ █▄▄▄█ █▄▄▄▄▄▄▄█▄▄█ █▄▄█▄▄▄▄▄▄▄█▄▄▄▄▄▄▄█ █▄▄▄█
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~v1
```
---

## 🎨 Colors
Tailwind has built-in color palettes (`50`, `100`, `200`, `...`, `900`).

```html
<!-- text colors -->
text-red-500 | text-blue-700 | text-green-400

<!-- background colors -->
bg-red-500 | bg-gray-100 | bg-blue-300

<!-- border colors -->
border-red-500 | border-blue-700
```

---

## 📏 Spacing

Tailwind spacing scale from `0` up to `96`.

```html
p-4    | padding: 1rem
pt-2   | padding-top: 0.5rem
px-4   | padding-left & right: 1rem
py-8   | padding-top & bottom: 2rem

m-4    | margin: 1rem
mt-8   | margin-top: 2rem
mx-auto| margin-left & right: auto
```

---

## 📐 Width and Height

```html
w-1/2  | width: 50%
w-full | width: 100%
w-screen | width: 100vw
w-48   | width: 12rem

h-32   | height: 8rem
h-full | height: 100%
h-screen | height: 100vh
```

---

## ✨ Typography

```html
text-xs   | font-size: 0.75rem
text-sm   | font-size: 0.875rem
text-base | font-size: 1rem
text-lg   | font-size: 1.125rem
text-xl   | font-size: 1.25rem
text-2xl  | font-size: 1.5rem
text-3xl  | font-size: 1.875rem

font-thin   | font-weight: 100
font-light  | font-weight: 300
font-normal | font-weight: 400
font-medium | font-weight: 500
font-bold   | font-weight: 700
font-black  | font-weight: 900

italic     | font-style: italic
not-italic | font-style: normal

underline  | text-decoration: underline
line-through | text-decoration: line-through

leading-loose  | line-height: 2
tracking-wide  | letter-spacing: 0.05em
```

---

## 🖼 Backgrounds

```html
bg-fixed      | background-attachment: fixed
bg-cover      | background-size: cover
bg-contain    | background-size: contain
bg-center     | background-position: center
bg-repeat     | background-repeat: repeat
bg-no-repeat  | background-repeat: no-repeat
```

---

## 📦 Borders

```html
border          | border: 1px solid
border-2        | border-width: 2px
border-4        | border-width: 4px
border-0        | border-width: 0

border-t-4      | border-top-width: 4px
border-r-4      | border-right-width: 4px

rounded         | border-radius: 0.25rem
rounded-lg      | border-radius: 0.5rem
rounded-full    | border-radius: 9999px
rounded-none    | border-radius: 0
```

---

## 🌀 Flexbox & Grid

### Flexbox
```html
flex            | display: flex
inline-flex     | display: inline-flex

flex-row        | flex-direction: row
flex-col        | flex-direction: column

justify-center  | justify-content: center
justify-between | justify-content: space-between

items-center    | align-items: center
items-start     | align-items: flex-start

flex-wrap       | flex-wrap: wrap
```

### Grid
```html
grid            | display: grid
grid-cols-3     | grid-template-columns: repeat(3, 1fr)
col-span-2      | grid-column: span 2
row-span-3      | grid-row: span 3
gap-4           | gap: 1rem
```

---

## 🎭 Positioning

```html
static      | position: static
fixed       | position: fixed
absolute    | position: absolute
relative    | position: relative
sticky      | position: sticky

top-0       | top: 0
bottom-0    | bottom: 0
left-0      | left: 0
right-0     | right: 0
```

---

## 📌 Z-Index

```html
z-0     | z-index: 0
z-10    | z-index: 10
z-50    | z-index: 50
z-auto  | z-index: auto
```

---

## 📖 Display

```html
block           | display: block
inline-block    | display: inline-block
inline          | display: inline
hidden          | display: none
```

---

## 🌫 Opacity

```html
opacity-0       | opacity: 0
opacity-50      | opacity: 0.5
opacity-100     | opacity: 1
```

---

## 🕸 Shadow

```html
shadow-sm       | box-shadow: small
shadow          | default shadow
shadow-lg       | large shadow
shadow-inner    | inset shadow
shadow-none     | no shadow
```

---

## 🌍 Responsive (Breakpoints)

```html
sm:text-left    | ≥ 640px
md:text-center  | ≥ 768px
lg:text-right   | ≥ 1024px
xl:text-justify | ≥ 1280px
2xl:text-left   | ≥ 1536px
```

---

## 🖱 Hover, Focus, Active

```html
hover:bg-blue-500   | Hover state
focus:ring          | Focus state
active:bg-gray-300  | Active state
```

---

## ⚡ Transitions & Animations

```html
transition          | transition-property: all
duration-200        | transition-duration: 200ms
ease-in-out         | transition-timing-function

animate-spin        | infinite rotation
animate-ping        | pulse animation
animate-pulse       | subtle pulse animation
animate-bounce      | bounce animation
```

---

## 🌓 Dark Mode

```html
dark:bg-gray-900
dark:text-white
```

---

## 📥 Overflow & Scrolling

```html
overflow-hidden | overflow: hidden
overflow-scroll | overflow: scroll
overflow-auto   | overflow: auto
```

---

## 🎯 Interactivity & Cursor

```html
cursor-pointer  | cursor: pointer
cursor-default  | cursor: default
pointer-events-none | pointer-events: none
select-none     | user-select: none
```

---

## 🛠 Accessibility (Screen Reader)

```html
sr-only        | visually hidden, but available to screen readers
not-sr-only    | reverses sr-only
```

---

## ⚙️ Misc Utilities

```html
object-cover    | object-fit: cover
object-contain  | object-fit: contain
```

---

## 🧑‍💻 Useful Commands

**Install via NPM:**
```bash
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init
```

**Build CSS:**
```bash
npx tailwindcss -i input.css -o output.css --watch
```

**Example Tailwind Config (`tailwind.config.js`):**
```js
module.exports = {
  darkMode: 'class',
  content: ['./src/**/*.{html,js,jsx,ts,tsx}'],
  theme: {
    extend: {},
  },
  plugins: [],
}
```

---

## 📚 References & Documentation
- Official Docs: [tailwindcss.com](https://tailwindcss.com/)
- Tailwind Play: [play.tailwindcss.com](https://play.tailwindcss.com/)
