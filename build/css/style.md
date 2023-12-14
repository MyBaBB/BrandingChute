@import url('https://fonts.googleapis.com/css2?family=Aclonica&family=Black+Ops+One&family=Edu+SA+Beginner:wght@500&family=Iceberg&family=MedievalSharp&family=Metamorphous&family=Nova+Cut&family=Permanent+Marker&family=Press+Start+2P&family=Rye&family=Sansita&family=Orbitron:wght@700&family=Vast+Shadow&display=swap=Wallpoet&display=swap');

/*
! tailwindcss v3.3.5 | MIT License | https://tailwindcss.com
*/

/*
1. Prevent padding and border from affecting element width. (https://github.com/mozdevs/cssremedy/issues/4)
2. Allow adding a border to an element by just adding a border-width. (https://github.com/tailwindcss/tailwindcss/pull/116)
*/

*,
::before,
::after {
  box-sizing: border-box;
  /* 1 */
  border-width: 0;
  /* 2 */
  border-style: solid;
  /* 2 */
  border-color: #e5e7eb;
  /* 2 */
}

::before,
::after {
  --tw-content: '';
}

/*
1. Use a consistent sensible line-height in all browsers.
2. Prevent adjustments of font size after orientation changes in iOS.
3. Use a more readable tab size.
4. Use the user's configured `sans` font-family by default.
5. Use the user's configured `sans` font-feature-settings by default.
6. Use the user's configured `sans` font-variation-settings by default.
*/

html {
  line-height: 1.5;
  /* 1 */
  -webkit-text-size-adjust: 100%;
  /* 2 */
  -moz-tab-size: 4;
  /* 3 */
  -o-tab-size: 4;
     tab-size: 4;
  /* 3 */
  font-family: ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, "Noto Sans", sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
  /* 4 */
  font-feature-settings: normal;
  /* 5 */
  font-variation-settings: normal;
  /* 6 */
}

/*
1. Remove the margin in all browsers.
2. Inherit line-height from `html` so users can set them as a class directly on the `html` element.
*/

body {
  margin: 0;
  /* 1 */
  line-height: inherit;
  /* 2 */
}

/*
1. Add the correct height in Firefox.
2. Correct the inheritance of border color in Firefox. (https://bugzilla.mozilla.org/show_bug.cgi?id=190655)
3. Ensure horizontal rules are visible by default.
*/

hr {
  height: 0;
  /* 1 */
  color: inherit;
  /* 2 */
  border-top-width: 1px;
  /* 3 */
}

/*
Add the correct text decoration in Chrome, Edge, and Safari.
*/

abbr:where([title]) {
  -webkit-text-decoration: underline dotted;
          text-decoration: underline dotted;
}

/*
Remove the default font size and weight for headings.
*/

h1,
h2,
h3,
h4,
h5,
h6 {
  font-size: inherit;
  font-weight: inherit;
}

/*
Reset links to optimize for opt-in styling instead of opt-out.
*/

a {
  color: inherit;
  text-decoration: inherit;
}

/*
Add the correct font weight in Edge and Safari.
*/

b,
strong {
  font-weight: bolder;
}

/*
1. Use the user's configured `mono` font family by default.
2. Correct the odd `em` font sizing in all browsers.
*/

code,
kbd,
samp,
pre {
  font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace;
  /* 1 */
  font-size: 1em;
  /* 2 */
}

/*
Add the correct font size in all browsers.
*/

small {
  font-size: 80%;
}

/*
Prevent `sub` and `sup` elements from affecting the line height in all browsers.
*/

sub,
sup {
  font-size: 75%;
  line-height: 0;
  position: relative;
  vertical-align: baseline;
}

sub {
  bottom: -0.25em;
}

sup {
  top: -0.5em;
}

/*
1. Remove text indentation from table contents in Chrome and Safari. (https://bugs.chromium.org/p/chromium/issues/detail?id=999088, https://bugs.webkit.org/show_bug.cgi?id=201297)
2. Correct table border color inheritance in all Chrome and Safari. (https://bugs.chromium.org/p/chromium/issues/detail?id=935729, https://bugs.webkit.org/show_bug.cgi?id=195016)
3. Remove gaps between table borders by default.
*/

table {
  text-indent: 0;
  /* 1 */
  border-color: inherit;
  /* 2 */
  border-collapse: collapse;
  /* 3 */
}

/*
1. Change the font styles in all browsers.
2. Remove the margin in Firefox and Safari.
3. Remove default padding in all browsers.
*/

button,
input,
optgroup,
select,
textarea {
  font-family: inherit;
  /* 1 */
  font-feature-settings: inherit;
  /* 1 */
  font-variation-settings: inherit;
  /* 1 */
  font-size: 100%;
  /* 1 */
  font-weight: inherit;
  /* 1 */
  line-height: inherit;
  /* 1 */
  color: inherit;
  /* 1 */
  margin: 0;
  /* 2 */
  padding: 0;
  /* 3 */
}

/*
Remove the inheritance of text transform in Edge and Firefox.
*/

button,
select {
  text-transform: none;
}

/*
1. Correct the inability to style clickable types in iOS and Safari.
2. Remove default button styles.
*/

button,
[type='button'],
[type='reset'],
[type='submit'] {
  -webkit-appearance: button;
  /* 1 */
  background-color: transparent;
  /* 2 */
  background-image: none;
  /* 2 */
}

/*
Use the modern Firefox focus style for all focusable elements.
*/

:-moz-focusring {
  outline: auto;
}

/*
Remove the additional `:invalid` styles in Firefox. (https://github.com/mozilla/gecko-dev/blob/2f9eacd9d3d995c937b4251a5557d95d494c9be1/layout/style/res/forms.css#L728-L737)
*/

:-moz-ui-invalid {
  box-shadow: none;
}

/*
Add the correct vertical alignment in Chrome and Firefox.
*/

progress {
  vertical-align: baseline;
}

/*
Correct the cursor style of increment and decrement buttons in Safari.
*/

::-webkit-inner-spin-button,
::-webkit-outer-spin-button {
  height: auto;
}

/*
1. Correct the odd appearance in Chrome and Safari.
2. Correct the outline style in Safari.
*/

[type='search'] {
  -webkit-appearance: textfield;
  /* 1 */
  outline-offset: -2px;
  /* 2 */
}

/*
Remove the inner padding in Chrome and Safari on macOS.
*/

::-webkit-search-decoration {
  -webkit-appearance: none;
}

/*
1. Correct the inability to style clickable types in iOS and Safari.
2. Change font properties to `inherit` in Safari.
*/

::-webkit-file-upload-button {
  -webkit-appearance: button;
  /* 1 */
  font: inherit;
  /* 2 */
}

/*
Add the correct display in Chrome and Safari.
*/

summary {
  display: list-item;
}

/*
Removes the default spacing and border for appropriate elements.
*/

blockquote,
dl,
dd,
h1,
h2,
h3,
h4,
h5,
h6,
hr,
figure,
p,
pre {
  margin: 0;
}

fieldset {
  margin: 0;
  padding: 0;
}

legend {
  padding: 0;
}

ol,
ul,
menu {
  list-style: none;
  margin: 0;
  padding: 0;
}

/*
Reset default styling for dialogs.
*/

dialog {
  padding: 0;
}

/*
Prevent resizing textareas horizontally by default.
*/

textarea {
  resize: vertical;
}

/*
1. Reset the default placeholder opacity in Firefox. (https://github.com/tailwindlabs/tailwindcss/issues/3300)
2. Set the default placeholder color to the user's configured gray 400 color.
*/

input::-moz-placeholder, textarea::-moz-placeholder {
  opacity: 1;
  /* 1 */
  color: #9ca3af;
  /* 2 */
}

input::placeholder,
textarea::placeholder {
  opacity: 1;
  /* 1 */
  color: #9ca3af;
  /* 2 */
}

/*
Set the default cursor for buttons.
*/

button,
[role="button"] {
  cursor: pointer;
}

/*
Make sure disabled buttons don't get the pointer cursor.
*/

:disabled {
  cursor: default;
}

/*
1. Make replaced elements `display: block` by default. (https://github.com/mozdevs/cssremedy/issues/14)
2. Add `vertical-align: middle` to align replaced elements more sensibly by default. (https://github.com/jensimmons/cssremedy/issues/14#issuecomment-634934210)
   This can trigger a poorly considered lint error in some tools but is included by design.
*/

img,
svg,
video,
canvas,
audio,
iframe,
embed,
object {
  display: block;
  /* 1 */
  vertical-align: middle;
  /* 2 */
}

/*
Constrain images and videos to the parent width and preserve their intrinsic aspect ratio. (https://github.com/mozdevs/cssremedy/issues/14)
*/

img,
video {
  max-width: 100%;
  height: auto;
}

/* Make elements with the HTML hidden attribute stay hidden by default */

[hidden] {
  display: none;
}

*, ::before, ::after{
  --tw-border-spacing-x: 0;
  --tw-border-spacing-y: 0;
  --tw-translate-x: 0;
  --tw-translate-y: 0;
  --tw-rotate: 0;
  --tw-skew-x: 0;
  --tw-skew-y: 0;
  --tw-scale-x: 1;
  --tw-scale-y: 1;
  --tw-pan-x:  ;
  --tw-pan-y:  ;
  --tw-pinch-zoom:  ;
  --tw-scroll-snap-strictness: proximity;
  --tw-gradient-from-position:  ;
  --tw-gradient-via-position:  ;
  --tw-gradient-to-position:  ;
  --tw-ordinal:  ;
  --tw-slashed-zero:  ;
  --tw-numeric-figure:  ;
  --tw-numeric-spacing:  ;
  --tw-numeric-fraction:  ;
  --tw-ring-inset:  ;
  --tw-ring-offset-width: 0px;
  --tw-ring-offset-color: #fff;
  --tw-ring-color: rgb(59 130 246 / 0.5);
  --tw-ring-offset-shadow: 0 0 #0000;
  --tw-ring-shadow: 0 0 #0000;
  --tw-shadow: 0 0 #0000;
  --tw-shadow-colored: 0 0 #0000;
  --tw-blur:  ;
  --tw-brightness:  ;
  --tw-contrast:  ;
  --tw-grayscale:  ;
  --tw-hue-rotate:  ;
  --tw-invert:  ;
  --tw-saturate:  ;
  --tw-sepia:  ;
  --tw-drop-shadow:  ;
  --tw-backdrop-blur:  ;
  --tw-backdrop-brightness:  ;
  --tw-backdrop-contrast:  ;
  --tw-backdrop-grayscale:  ;
  --tw-backdrop-hue-rotate:  ;
  --tw-backdrop-invert:  ;
  --tw-backdrop-opacity:  ;
  --tw-backdrop-saturate:  ;
  --tw-backdrop-sepia:  ;
}

::backdrop{
  --tw-border-spacing-x: 0;
  --tw-border-spacing-y: 0;
  --tw-translate-x: 0;
  --tw-translate-y: 0;
  --tw-rotate: 0;
  --tw-skew-x: 0;
  --tw-skew-y: 0;
  --tw-scale-x: 1;
  --tw-scale-y: 1;
  --tw-pan-x:  ;
  --tw-pan-y:  ;
  --tw-pinch-zoom:  ;
  --tw-scroll-snap-strictness: proximity;
  --tw-gradient-from-position:  ;
  --tw-gradient-via-position:  ;
  --tw-gradient-to-position:  ;
  --tw-ordinal:  ;
  --tw-slashed-zero:  ;
  --tw-numeric-figure:  ;
  --tw-numeric-spacing:  ;
  --tw-numeric-fraction:  ;
  --tw-ring-inset:  ;
  --tw-ring-offset-width: 0px;
  --tw-ring-offset-color: #fff;
  --tw-ring-color: rgb(59 130 246 / 0.5);
  --tw-ring-offset-shadow: 0 0 #0000;
  --tw-ring-shadow: 0 0 #0000;
  --tw-shadow: 0 0 #0000;
  --tw-shadow-colored: 0 0 #0000;
  --tw-blur:  ;
  --tw-brightness:  ;
  --tw-contrast:  ;
  --tw-grayscale:  ;
  --tw-hue-rotate:  ;
  --tw-invert:  ;
  --tw-saturate:  ;
  --tw-sepia:  ;
  --tw-drop-shadow:  ;
  --tw-backdrop-blur:  ;
  --tw-backdrop-brightness:  ;
  --tw-backdrop-contrast:  ;
  --tw-backdrop-grayscale:  ;
  --tw-backdrop-hue-rotate:  ;
  --tw-backdrop-invert:  ;
  --tw-backdrop-opacity:  ;
  --tw-backdrop-saturate:  ;
  --tw-backdrop-sepia:  ;
}

.container{
  width: 100%;
}

@media (min-width: 640px){
  .container{
    max-width: 640px;
  }
}

@media (min-width: 768px){
  .container{
    max-width: 768px;
  }
}

@media (min-width: 1024px){
  .container{
    max-width: 1024px;
  }
}

@media (min-width: 1280px){
  .container{
    max-width: 1280px;
  }
}

@media (min-width: 1536px){
  .container{
    max-width: 1536px;
  }
}

.fixed{
  position: fixed;
}

.absolute{
  position: absolute;
}

.relative{
  position: relative;
}

.sticky{
  position: sticky;
}

.bottom-0{
  bottom: 0px;
}

.bottom-3{
  bottom: 0.75rem;
}

.right-10{
  right: 2.5rem;
}

.right-5{
  right: 1.25rem;
}

.top-0{
  top: 0px;
}

.top-4{
  top: 1rem;
}

.z-10{
  z-index: 10;
}

.z-30{
  z-index: 30;
}

.z-50{
  z-index: 50;
}

.m-0{
  margin: 0px;
}

.m-auto{
  margin: auto;
}

.mx-auto{
  margin-left: auto;
  margin-right: auto;
}

.my-10{
  margin-top: 2.5rem;
  margin-bottom: 2.5rem;
}

.my-12{
  margin-top: 3rem;
  margin-bottom: 3rem;
}

.my-4{
  margin-top: 1rem;
  margin-bottom: 1rem;
}

.my-8{
  margin-top: 2rem;
  margin-bottom: 2rem;
}

.-mb-2{
  margin-bottom: -0.5rem;
}

.-mt-0{
  margin-top: -0px;
}

.-mt-0\.5{
  margin-top: -0.125rem;
}

.mb-0{
  margin-bottom: 0px;
}

.mb-1{
  margin-bottom: 0.25rem;
}

.mb-10{
  margin-bottom: 2.5rem;
}

.mb-8{
  margin-bottom: 2rem;
}

.mt-14{
  margin-top: 3.5rem;
}

.mt-2{
  margin-top: 0.5rem;
}

.mt-4{
  margin-top: 1rem;
}

.block{
  display: block;
}

.inline-block{
  display: inline-block;
}

.inline{
  display: inline;
}

.flex{
  display: flex;
}

.hidden{
  display: none;
}

.h-1{
  height: 0.25rem;
}

.h-20{
  height: 5rem;
}

.h-8{
  height: 2rem;
}

.min-h-screen{
  min-height: 100vh;
}

.w-1\/2{
  width: 50%;
}

.w-10{
  width: 2.5rem;
}

.w-20{
  width: 5rem;
}

.w-8{
  width: 2rem;
}

.w-\[18rem\]{
  width: 18rem;
}

.w-fit{
  width: -moz-fit-content;
  width: fit-content;
}

.w-full{
  width: 100%;
}

.w-max{
  width: -moz-max-content;
  width: max-content;
}

.max-w-4xl{
  max-width: 56rem;
}

.max-w-md{
  max-width: 28rem;
}

.origin-top{
  transform-origin: top;
}

.transform{
  transform: translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y));
}

@keyframes bounce{
  0%, 100%{
    transform: translateY(-25%);
    animation-timing-function: cubic-bezier(0.8,0,1,1);
  }

  50%{
    transform: none;
    animation-timing-function: cubic-bezier(0,0,0.2,1);
  }
}

.animate-bounce{
  animation: bounce 1s infinite;
}

@keyframes open-menu{
  0%{
    transform: scaleY(0);
  }

  80%{
    transform: scaleY(01.2);
  }

  100%{
    transform: scaleY(1);
  }
}

.animate-open-menu{
  animation: open-menu 0.5s ease-in-out forwards;
}

@keyframes pulse{
  50%{
    opacity: .5;
  }
}

.animate-pulse{
  animation: pulse 2s cubic-bezier(0.4, 0, 0.6, 1) infinite;
}

.cursor-pointer{
  cursor: pointer;
}

.scroll-m-20{
  scroll-margin: 5rem;
}

.scroll-m-56{
  scroll-margin: 14rem;
}

.-scroll-mt-\[-7rem\]{
  scroll-margin-top: 7rem;
}

.scroll-mt-10{
  scroll-margin-top: 2.5rem;
}

.scroll-mt-20{
  scroll-margin-top: 5rem;
}

.scroll-mt-24{
  scroll-margin-top: 6rem;
}

.scroll-mt-52{
  scroll-margin-top: 13rem;
}

.scroll-mt-\[16rem\]{
  scroll-margin-top: 16rem;
}

.scroll-mt-\[7rem\]{
  scroll-margin-top: 7rem;
}

.flex-row{
  flex-direction: row;
}

.flex-col{
  flex-direction: column;
}

.content-center{
  align-content: center;
}

.items-center{
  align-items: center;
}

.justify-center{
  justify-content: center;
}

.justify-between{
  justify-content: space-between;
}

.gap-2{
  gap: 0.5rem;
}

.gap-8{
  gap: 2rem;
}

.space-x-8 > :not([hidden]) ~ :not([hidden]){
  --tw-space-x-reverse: 0;
  margin-right: calc(2rem * var(--tw-space-x-reverse));
  margin-left: calc(2rem * calc(1 - var(--tw-space-x-reverse)));
}

.self-end{
  align-self: flex-end;
}

.scroll-smooth{
  scroll-behavior: smooth;
}

.whitespace-nowrap{
  white-space: nowrap;
}

.rounded{
  border-radius: 0.25rem;
}

.rounded-3xl{
  border-radius: 1.5rem;
}

.rounded-full{
  border-radius: 9999px;
}

.rounded-lg{
  border-radius: 0.5rem;
}

.rounded-b{
  border-bottom-right-radius: 0.25rem;
  border-bottom-left-radius: 0.25rem;
}

.rounded-b-3xl{
  border-bottom-right-radius: 1.5rem;
  border-bottom-left-radius: 1.5rem;
}

.border{
  border-width: 1px;
}

.border-2{
  border-width: 2px;
}

.border-4{
  border-width: 4px;
}

.border-solid{
  border-style: solid;
}

.border-black{
  --tw-border-opacity: 1;
  border-color: rgb(0 0 0 / var(--tw-border-opacity));
}

.border-slate-900{
  --tw-border-opacity: 1;
  border-color: rgb(15 23 42 / var(--tw-border-opacity));
}

.border-transparent{
  border-color: transparent;
}

.border-varDARKWING{
  --tw-border-opacity: 1;
  border-color: rgb(60 48 46 / var(--tw-border-opacity));
}

.bg-black{
  --tw-bg-opacity: 1;
  background-color: rgb(0 0 0 / var(--tw-bg-opacity));
}

.bg-gray-700{
  --tw-bg-opacity: 1;
  background-color: rgb(55 65 81 / var(--tw-bg-opacity));
}

.bg-varDARKBEAK{
  --tw-bg-opacity: 1;
  background-color: rgb(112 24 26 / var(--tw-bg-opacity));
}

.bg-varDARKDUCKHEAD{
  --tw-bg-opacity: 1;
  background-color: rgb(30 59 40 / var(--tw-bg-opacity));
}

.bg-varDARKNECK{
  --tw-bg-opacity: 1;
  background-color: rgb(65 42 50 / var(--tw-bg-opacity));
}

.bg-varMEDBLUEFEATHER{
  --tw-bg-opacity: 1;
  background-color: rgb(42 97 161 / var(--tw-bg-opacity));
}

.bg-varMEDDUCKHEAD{
  --tw-bg-opacity: 1;
  background-color: rgb(40 79 53 / var(--tw-bg-opacity));
}

.bg-varMEDSPACE{
  --tw-bg-opacity: 1;
  background-color: rgb(27 56 84 / var(--tw-bg-opacity));
}

.bg-white{
  --tw-bg-opacity: 1;
  background-color: rgb(255 255 255 / var(--tw-bg-opacity));
}

.bg-gradient-to-b{
  background-image: linear-gradient(to bottom, var(--tw-gradient-stops));
}

.bg-gradient-to-br{
  background-image: linear-gradient(to bottom right, var(--tw-gradient-stops));
}

.from-varDARKBLUEFEATHER{
  --tw-gradient-from: #24558d var(--tw-gradient-from-position);
  --tw-gradient-to: rgb(36 85 141 / 0) var(--tw-gradient-to-position);
  --tw-gradient-stops: var(--tw-gradient-from), var(--tw-gradient-to);
}

.from-varMEDDUCKHEAD{
  --tw-gradient-from: #284f35 var(--tw-gradient-from-position);
  --tw-gradient-to: rgb(40 79 53 / 0) var(--tw-gradient-to-position);
  --tw-gradient-stops: var(--tw-gradient-from), var(--tw-gradient-to);
}

.via-varDARKDUCKHEAD{
  --tw-gradient-to: rgb(30 59 40 / 0)  var(--tw-gradient-to-position);
  --tw-gradient-stops: var(--tw-gradient-from), #1e3b28 var(--tw-gradient-via-position), var(--tw-gradient-to);
}

.to-varDARKWING{
  --tw-gradient-to: #3c302e var(--tw-gradient-to-position);
}

.to-varMEDDUCKHEAD{
  --tw-gradient-to: #284f35 var(--tw-gradient-to-position);
}

.p-0{
  padding: 0px;
}

.p-1{
  padding: 0.25rem;
}

.p-10{
  padding: 2.5rem;
}

.p-3{
  padding: 0.75rem;
}

.p-4{
  padding: 1rem;
}

.p-5{
  padding: 1.25rem;
}

.p-6{
  padding: 1.5rem;
}

.p-8{
  padding: 2rem;
}

.px-6{
  padding-left: 1.5rem;
  padding-right: 1.5rem;
}

.py-10{
  padding-top: 2.5rem;
  padding-bottom: 2.5rem;
}

.py-12{
  padding-top: 3rem;
  padding-bottom: 3rem;
}

.py-2{
  padding-top: 0.5rem;
  padding-bottom: 0.5rem;
}

.py-6{
  padding-top: 1.5rem;
  padding-bottom: 1.5rem;
}

.pr-4{
  padding-right: 1rem;
}

.pt-0{
  padding-top: 0px;
}

.pt-14{
  padding-top: 3.5rem;
}

.pt-4{
  padding-top: 1rem;
}

.text-left{
  text-align: left;
}

.text-center{
  text-align: center;
}

.text-right{
  text-align: right;
}

.font-PermanentMarker{
  font-family: Permanent Marker, cursive;
}

.font-Sansita{
  font-family: Sansita, cursive;
}

.font-blackopsone{
  font-family: Black Ops One, cursive;
}

.font-orbitron{
  font-family: Orbitron, sans-serif;
}

.font-rye{
  font-family: Rye, cursive;
}

.font-sans{
  font-family: ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, "Noto Sans", sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
}

.font-serif{
  font-family: ui-serif, Georgia, Cambria, "Times New Roman", Times, serif;
}

.text-2xl{
  font-size: 1.5rem;
  line-height: 2rem;
}

.text-3xl{
  font-size: 1.875rem;
  line-height: 2.25rem;
}

.text-4xl{
  font-size: 2.25rem;
  line-height: 2.5rem;
}

.text-5xl{
  font-size: 3rem;
  line-height: 1;
}

.text-\[\.74rem\]{
  font-size: .74rem;
}

.text-\[\.75rem\]{
  font-size: .75rem;
}

.text-\[0\.65rem\]{
  font-size: 0.65rem;
}

.text-base{
  font-size: 1rem;
  line-height: 1.5rem;
}

.text-lg{
  font-size: 1.125rem;
  line-height: 1.75rem;
}

.text-xl{
  font-size: 1.25rem;
  line-height: 1.75rem;
}

.font-bold{
  font-weight: 700;
}

.italic{
  font-style: italic;
}

.text-\[rgba\(65\2c 154\2c 255\2c 1\)\]{
  color: rgba(65,154,255,1);
}

.text-amber-600{
  --tw-text-opacity: 1;
  color: rgb(217 119 6 / var(--tw-text-opacity));
}

.text-amber-700{
  --tw-text-opacity: 1;
  color: rgb(180 83 9 / var(--tw-text-opacity));
}

.text-black{
  --tw-text-opacity: 1;
  color: rgb(0 0 0 / var(--tw-text-opacity));
}

.text-cyan-800{
  --tw-text-opacity: 1;
  color: rgb(21 94 117 / var(--tw-text-opacity));
}

.text-emerald-50{
  --tw-text-opacity: 1;
  color: rgb(236 253 245 / var(--tw-text-opacity));
}

.text-green-400{
  --tw-text-opacity: 1;
  color: rgb(74 222 128 / var(--tw-text-opacity));
}

.text-green-600{
  --tw-text-opacity: 1;
  color: rgb(22 163 74 / var(--tw-text-opacity));
}

.text-lime-600{
  --tw-text-opacity: 1;
  color: rgb(101 163 13 / var(--tw-text-opacity));
}

.text-red-300{
  --tw-text-opacity: 1;
  color: rgb(252 165 165 / var(--tw-text-opacity));
}

.text-red-500{
  --tw-text-opacity: 1;
  color: rgb(239 68 68 / var(--tw-text-opacity));
}

.text-slate-500{
  --tw-text-opacity: 1;
  color: rgb(100 116 139 / var(--tw-text-opacity));
}

.text-transparent{
  color: transparent;
}

.text-varBoneWhite{
  --tw-text-opacity: 1;
  color: rgb(255 249 215 / var(--tw-text-opacity));
}

.text-varDARKBEAK{
  --tw-text-opacity: 1;
  color: rgb(112 24 26 / var(--tw-text-opacity));
}

.text-varLIGHTBEAK{
  --tw-text-opacity: 1;
  color: rgb(215 45 50 / var(--tw-text-opacity));
}

.text-varLIGHTBEAKTOP{
  --tw-text-opacity: 1;
  color: rgb(252 168 2 / var(--tw-text-opacity));
}

.text-varLIGHTBLUEFEATHER{
  --tw-text-opacity: 1;
  color: rgb(65 154 255 / var(--tw-text-opacity));
}

.text-white{
  --tw-text-opacity: 1;
  color: rgb(255 255 255 / var(--tw-text-opacity));
}

.transition-all{
  transition-property: all;
  transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
  transition-duration: 150ms;
}

.duration-500{
  transition-duration: 500ms;
}

/*  a[data-tool-tip] {
  position: relative;
  } */

.getBrandedCushion2:hover::before, 
  .getBrandedCushion2:hover::after {
  --scale: 1;
}

.getBrandedCushion2::before {
  content:'';
  background-color:#419aff;
  width:-moz-max-content;
  width:max-content;
  position: absolute;
  content: attr(data-tool-tip);
  padding:  .1em .1em .2em .1em;
  left: 30%;
  transform: translateX(-40%)
  translateY(-3.5rem) scale(var(--scale));
  transform-origin:bottom center;
  transition: ease-in .35s;
  border: 0.3px solid #fff9d7;
  border-radius: 10px;
  color:#fff9d7;
  padding-left: 2rem;
  padding-right: 2rem;
  --scale: 0;
  z-index: 3;
}

.getBrandedCushion2::after {
  content:'';
  width: 25px;
  height: 25px;
  position: absolute;
  padding:  .3em .0em .2em .1em;
  left: 30%;
  transform: translateX(20px)
  translateY(-1.65rem) scale(var(--scale));
  transform-origin:top center;
  transition:  ease-in .35s;
  border: 15px solid transparent;
  border-top:#419aff 25px solid;
  color:#fff9d7;
  --scale: 0;
  z-index: 1;
  margin:auto;
}

.spanContainerDiv {
  position: relative;
}

.getBrandedCushion:hover::before, 
  .getBrandedCushion:hover::after {
  --scale: 1;
}

.getBrandedCushion::before {
  content:'';
  background-color:#419aff;
  width:-moz-max-content;
  width:max-content;
  position: absolute;
  content: attr(data-tool-tip);
  padding:  .1em .1em .2em .1em;
  left: 50%;
  transform: translateX(-50%)
  translateY(-4rem) scale(var(--scale));
  transform-origin:bottom center;
  transition: ease-in .35s;
  border: 0.3px solid #fff9d7;
  border-radius: 10px;
  color:#fff9d7;
  padding-left: 2rem;
  padding-right: 2rem;
  --scale: 0;
  z-index: 3;
  font-size: smaller;
}

.crabCushion:hover::before, 
  .crabCushion:hover::after {
  --scale: 1;
}

.crabCushion::before {
  content:'';
  background-color:#419aff;
  width:-moz-max-content;
  width:max-content;
  position: absolute;
  content: attr(data-tool-tip);
  padding:  .1em .1em .2em .1em;
  left: 50%;
  transform: translateX(-50%) scale(var(--scale));
  transform-origin:bottom center;
  transition: ease-in .35s;
  bottom:2.30rem;
  border: 0.3px solid #fff9d7;
  border-radius: 10px;
  color:#fff9d7;
  padding-left: 2rem;
  padding-right: 2rem;
  --scale: 0;
  z-index: 3;
}

.crabCushion::after {
  content:'';
  width: 15px;
  height: 15px;
  position: absolute;
  padding:  .1em .1em .2em .1em;
  left: 50%;
  transform: translateX(-50%) scale(var(--scale));
  transform-origin:top center;
  transition:.35s ;
  top:-.15rem;
  border: 15px solid transparent;
  border-top:#cfa69d 10px solid;
  color:#fff9d7;
  --scale: 0;
  z-index: 2;
}

.whoopieCushion1:hover::before, 
  .whoopieCushion1:hover::after {
  --scale: 1;
}

.whoopieCushion1::before {
  content:'';
  background-color:#412a32;
  width:-moz-max-content;
  width:max-content;
  position: absolute;
  content: attr(data-tool-tip);
  padding:  .1em .1em .2em .1em;
  left: 50%;
  transform: translateX(-50%) scale(var(--scale));
  transform-origin: top left;
  transition: ease-in .25s;
  bottom:-2.75rem;
  border: 0.3px solid #fff9d7;
  border-radius: 10px;
  color:fff9d7;
  padding-left: 2rem;
  padding-right: 2rem;
  --scale: 0;
  z-index: 3;
  left:14rem;
}

.whoopieCushion1::after {
  content:'';
  top: .4rem;
  width: 15px;
  height: 15px;
  position: absolute;
  padding:  .1em .1em .2em .1em;
  left: 50%;
  transform: translateX(-50%) scale(var(--scale));
  transform-origin:bottom center;
  transition:.35s ;
  bottom:-1.75rem;
  border: 15px solid transparent;
  border-bottom:#cfa69d 10px solid;
  color: #fff9d7;
  --scale: 0;
  z-index: 2;
}

.whoopieCushion2:hover::before, 
  .whoopieCushion2:hover::after {
  --scale: 1;
}

.whoopieCushion2::before {
  content:'';
  background-color:#412a32;
  width:-moz-max-content;
  width:max-content;
  position: absolute;
  content: attr(data-tool-tip);
  padding:  .1em .1em .2em .1em;
  left: 50%;
  transform: translateX(-50%) scale(var(--scale));
  transform-origin: top center;
  transition: ease-in .25s;
  bottom:-2.75rem;
  border: 0.3px solid #fff9d7;
  border-radius: 10px;
  color:fff9d7;
  padding-left: 2rem;
  padding-right: 2rem;
  --scale: 0;
  z-index: 3;
}

.whoopieCushion2::after {
  content:'';
  top: .4rem;
  width: 15px;
  height: 15px;
  position: absolute;
  padding:  .1em .1em .2em .1em;
  left: 50%;
  transform: translateX(-10%) scale(var(--scale));
  transform-origin:bottom center;
  transition:.35s;
  bottom:-1.75rem;
  border: 15px solid transparent;
  border-bottom:#cfa69d 10px solid;
  color: #fff9d7;
  --scale: 0;
  z-index: 2;
}

.whoopieCushion3:hover::before, 
  .whoopieCushion3:hover::after {
  --scale: 1;
}

.whoopieCushion3::before {
  content:'';
  background-color:#412a32;
  width:-moz-max-content;
  width:max-content;
  position: absolute;
  content: attr(data-tool-tip);
  padding:  .1em .1em .2em .1em;
  left: 50%;
  transform: translateX(-50%) scale(var(--scale));
  transform-origin: top right;
  transition: ease-in .25s;
  bottom:-2.75rem;
  border: 0.3px solid #fff9d7;
  border-radius: 10px;
  color:fff9d7;
  padding-left: 2rem;
  padding-right: 2rem;
  --scale: 0;
  z-index: 3;
  left: -4rem;
}

.whoopieCushion3::after {
  content:'';
  top: .4rem;
  width: 15px;
  height: 15px;
  position: absolute;
  padding:  .1em .1em .2em .1em;
  left: 50%;
  transform: translateX(-10%) scale(var(--scale));
  transform-origin:bottom center;
  transition:.35s ;
  bottom:-1.75rem;
  border: 15px solid transparent;
  border-bottom:#cfa69d 10px solid;
  color: #fff9d7;
  --scale: 0;
  z-index: 2;
}

/* xxxxxxxxxxxxxxxxxxxxxxxxxxxx */

.secretPassword:hover::before, 
.secretPassword:hover::after {
  --scale: 1;
}

.secretPassword::before {
  content:'';
  background-color: #419aff;
  width:-moz-max-content;
  width:max-content;
  position: absolute;
  content: attr(data-tool-tip);
  padding:  .1em .1em .2em .1em;
  left: 50%;
  transform: translateX(-117px) translateY(-85px) scale(var(--scale));
  transform-origin: bottom center;
  transition: 800ms;
  border-radius: 10px;
  border: 2px solid wheat;
  color:wheat;
  padding-left: 2rem;
  padding-right: 2rem;
  --scale: 0;
  z-index: 3;
  font-size:medium
}

.secretPassword::after {
  content:'';
  width: 25px;
  height: 25px;
  position: absolute;
  left: 50%;
  transform: translateX(-23px) translateY(-134px) scale(var(--scale));
  transform-origin:top center;
  transition:1s;
  border: 25px solid transparent;
  border-top:wheat  15px solid;
  color:wheat;
  --scale: 0;
  z-index: 2;
}

#logoBody{
  font-size: 2rem;
  background: linear-gradient(to bottom, #002244, #8c8b8a, #ffffff);
  font-family: noto serif;
}

#body2 {
  font-size: 2rem;
  background: linear-gradient(to bottom, #002244, #8c8b8a, #ffffff);
  font-family: noto serif;
}

#headersection{
  border: 2px solid #000000;
  border-radius: 20px;
  box-shadow: 2px 2px 4px rgba(0, 0, 0, 0.4);
  z-index: 50;
}

#logoBody{
  font-size: 2rem;
  background: linear-gradient(to bottom, #002244, #8c8b8a, #ffffff);
  font-family: noto serif;
}

#header {
  z-index: 5400;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1), 0 1px 3px rgba(0, 0, 0, 0.08), 0 2px 4px rgba(0, 0, 0, 0.12);
}

input {
  color: #419aff;
  background-color: #33485d;
  width: 80%;
  border-radius:  10px ;
  border: solid 2px #000000;
  box-shadow: 0 0 0 0.2rem #000000;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.5), 0 0 20px rgba(0, 0, 0, 0.3), 0 0 30px rgba(0, 0, 0, 0.2), 0 0 40px rgba(0, 0, 0, 0.1);
  margin: 0 auto;
  display: block;
}

textarea{
  color: #419aff;
  background-color: #33485d;
  width: 80%;
  border-radius: 10px;
  border: solid 2px #000000;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.5), 0 0 20px rgba(0, 0, 0, 0.3), 0 0 30px rgba(0, 0, 0, 0.2), 0 0 40px rgba(0, 0, 0, 0.1);
  margin: 0 auto;
  display: block;
}

label{
  font-size: 2rem;
  color: #ffffff;
  font-family: noto serif;
}

#container {
  width: 100%;
  margin-left: auto;
  margin-right: auto;
  padding-left: 0.5rem;
  padding-right: 0.5rem;
  border: 3px solid #000000;
}

.bgImagediv {
  display: flex;
  justify-content: center;
  align-items: center;
  z-index: 5;
  width: 630px;
  height: 500px;
}

.loader{
  display: flex;
  justify-content: center;
  align-items: center;
  position: fixed;
  top: 0;
  left:0;
  width: 45vw;
  height: 45vh;
  background-color: #cfa69d;
  transition: opacity 0.75s, visibility 0.75s;
}

.loader-hidden{
  opacity: 0;
  visibility: hidden;
}

.loader::after {
  content: '';
  width: 75px;
  height: 75px;
  border: 15px solid #dddddd;
  border-top-color: #744888;
  border-radius: 50%;
  animation:loading 0.75s ease infinite;
}

@keyframes loading {
  from {
    transform: rotate(0turn);
  }

  to {
    transform: rotate(1turn);
  }
}

.hoverdiv {
  display: flex;
  position: relative;
  align-items: center;
  justify-content: center;
  padding-left: 10px;
  padding-right: 10px;
  width: 100%;
  margin-left: auto;
  margin-right: auto;
}

.eyeballdiv3 {
  display: flex;
  justify-content: center;
  align-items: center;
  z-index: 12;
  width: 192px;
  height:  192px;
  border: 28px solid #1c4b81;
  border-radius: 100%;
  position:absolute;
}

.eyeballdiv2 {
  display: flex;
  justify-content: center;
  align-items: center;
  z-index: 13;
  width: 192px;
  height:  192px;
  border: 20px solid #173c67;
  border-radius: 100%;
  position:absolute;
}

.eyeballdiv {
  display: flex;
  justify-content: center;
  align-items: center;
  z-index: 15;
  width: 192px;
  height:  192px;
  border: 10px solid #0d2d52;
  border-radius: 100%;
  position:absolute;
}

@media (hover : none) {
  .hoverdiv:hover .expandingIris {
    width: 30px;
    height: 30px;
    animation: expand 0.5s forwards;
    border: 2px solid;
    border-color: #419aff;
  }
}

.expandingIris {
  position:absolute;
  width: 4px;
  height:4px;
  background: rgb(0, 0, 0);
  border-radius: 50%;
  z-index: 3;
  transform: translate(-1px , 2px);
  transition: all .5s ease-in-out;
}

.irisHighlight {
  position:absolute;
  width: 14px;
  height:10px;
  background: rgba(236, 244, 235, .25);
  border-radius: 50%;
  z-index: 4;
  transform: translate(9px , -6px);
}

.hoverdiv:hover .expandingIris  {
  width: 30px;
  height: 30px;
  animation: expand 0.5s forwards;
  border:  2px solid;
  border-color: #419aff;
  z-index: 2;
}

.hoverAll:hover .redOnLight  {
  width: 8px;
  height: 8px;
  animation: expand 0.5s forwards;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(55px, -62.1px);
  border-radius: 50%;
  background-color: #e90f0f;
  z-index: 15;
  box-shadow: 0 0 10px rgba(87, 22, 22,1);
}

.myBabbPortal {
  position:absolute;
  color:#419aff;
  text-align: center;
  font-size: 1.75rem;
  z-index: 5;
  bottom: 0rem;
  text-shadow: 2px 2px 3px #1c0303
}

#stopButton{
  position: relative;
  margin: 0 auto;
  align-items: center;
  display: flex;
  justify-content: center;
  width: 80px;
  height: 80px;
  border-radius: 50%;
  box-shadow: 0px 0px 10px rgba(0, 0, 0, 1),
        inset 0px 0px 10px rgba(0, 0, 0, 0.5);
}

/*  xxxxxxxxxxxxxxxxxxxxxxxx */

/* xxxxxxxxxxxxxxxxxxxxxxx */

.toggle-btn>div::after{
  --tw-translate-y: 0px;
  --tw-rotate: -45deg;
  transform: translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y));
}

.toggle-btn>div::before{
  --tw-translate-y: 0px;
  --tw-rotate: 45deg;
  transform: translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y));
}

.toggle-btn>div{
  --tw-rotate: 720deg;
  transform: translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y));
  background-color: transparent;
}

@keyframes rotateX {
  0% {
    transform: rotateY(0deg);
  }

  100% {
    transform: rotateY(360deg);
  }
}

.rotate {
  animation: rotateX 25s linear infinite alternate;
  display: inline-block;
}

@keyframes rotateX {
  0% {
    transform: rotatey(0deg);
  }

  50% {
    transform: rotatey(360deg);
  }

  100% {
    transform: rotatey(0deg);
  }
}

@media only screen and (orientation: landscape) {
  #mobile-menu2 {
    display: none;
  }

  #header {
    font-size: 20px;
  }
}

@media only screen and (max-width: 319px) {
  #Hamburger-Menu{
    font: xx-small;
  }

  @media only screen and (min-width: 320px) and (max-width: 412px){
    #mobile-menu{
      font-size: 28px;
    }

    @media only screen and (min-width: 640px) {
      #hamburger-menu{
        display: none;
      }
    }

    @media (min-width: 350px) {
      #headersection {
        max-width: 350px;
      }
    }

    /* xxs */

    @media (min-width: 400px) {
      #headersection {
        max-width: 400px;
      }
    }

    /* xs */

    @media (min-width: 500px) {
      #headersection {
        max-width: 500px;
      }
    }

    /* s */

    @media (min-width: 640px) {
      #headersection {
        max-width: 640px;
      }
    }

    /* md */

    @media (min-width: 768px) {
      #headersection {
        max-width: 768px;
      }
    }

    /* lg */

    @media (min-width: 1024px) {
      #headersection {
        max-width: 1024px;
      }
    }

    /* xl */

    @media (min-width: 1280px) {
      #headersection {
        max-width: 1280px;
      }
    }

    /* 2xl */

    @media (min-width: 1536px) {
      #headersection {
        max-width: 1536px;
      }
    }
  }
}

.before\:absolute::before{
  content: var(--tw-content);
  position: absolute;
}

.before\:left-0::before{
  content: var(--tw-content);
  left: 0px;
}

.before\:h-1::before{
  content: var(--tw-content);
  height: 0.25rem;
}

.before\:w-8::before{
  content: var(--tw-content);
  width: 2rem;
}

.before\:-translate-x-0::before{
  content: var(--tw-content);
  --tw-translate-x: -0px;
  transform: translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y));
}

.before\:-translate-y-3::before{
  content: var(--tw-content);
  --tw-translate-y: -0.75rem;
  transform: translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y));
}

.before\:translate-x-2::before{
  content: var(--tw-content);
  --tw-translate-x: 0.5rem;
  transform: translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y));
}

.before\:translate-y-2::before{
  content: var(--tw-content);
  --tw-translate-y: 0.5rem;
  transform: translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y));
}

.before\:transform::before{
  content: var(--tw-content);
  transform: translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y));
}

.before\:rounded::before{
  content: var(--tw-content);
  border-radius: 0.25rem;
}

.before\:bg-varLIGHTBEAK::before{
  content: var(--tw-content);
  --tw-bg-opacity: 1;
  background-color: rgb(215 45 50 / var(--tw-bg-opacity));
}

.before\:font-serif::before{
  content: var(--tw-content);
  font-family: ui-serif, Georgia, Cambria, "Times New Roman", Times, serif;
}

.before\:text-9xl::before{
  content: var(--tw-content);
  font-size: 8rem;
  line-height: 1;
}

.before\:text-varLIGHTBLUEFEATHER::before{
  content: var(--tw-content);
  --tw-text-opacity: 1;
  color: rgb(65 154 255 / var(--tw-text-opacity));
}

.before\:opacity-25::before{
  content: var(--tw-content);
  opacity: 0.25;
}

.before\:transition-all::before{
  content: var(--tw-content);
  transition-property: all;
  transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
  transition-duration: 150ms;
}

.before\:duration-500::before{
  content: var(--tw-content);
  transition-duration: 500ms;
}

.before\:content-\[\'\'\]::before{
  --tw-content: '';
  content: var(--tw-content);
}

.before\:content-\[\'\\201C\'\]::before{
  --tw-content: '\201C';
  content: var(--tw-content);
}

.after\:absolute::after{
  content: var(--tw-content);
  position: absolute;
}

.after\:-bottom-20::after{
  content: var(--tw-content);
  bottom: -5rem;
}

.after\:right-0::after{
  content: var(--tw-content);
  right: 0px;
}

.after\:h-1::after{
  content: var(--tw-content);
  height: 0.25rem;
}

.after\:w-8::after{
  content: var(--tw-content);
  width: 2rem;
}

.after\:-translate-x-0::after{
  content: var(--tw-content);
  --tw-translate-x: -0px;
  transform: translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y));
}

.after\:-translate-x-2::after{
  content: var(--tw-content);
  --tw-translate-x: -0.5rem;
  transform: translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y));
}

.after\:-translate-y-2::after{
  content: var(--tw-content);
  --tw-translate-y: -0.5rem;
  transform: translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y));
}

.after\:translate-y-3::after{
  content: var(--tw-content);
  --tw-translate-y: 0.75rem;
  transform: translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y));
}

.after\:transform::after{
  content: var(--tw-content);
  transform: translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y));
}

.after\:rounded::after{
  content: var(--tw-content);
  border-radius: 0.25rem;
}

.after\:bg-varLIGHTBLUEFEATHER::after{
  content: var(--tw-content);
  --tw-bg-opacity: 1;
  background-color: rgb(65 154 255 / var(--tw-bg-opacity));
}

.after\:font-serif::after{
  content: var(--tw-content);
  font-family: ui-serif, Georgia, Cambria, "Times New Roman", Times, serif;
}

.after\:text-9xl::after{
  content: var(--tw-content);
  font-size: 8rem;
  line-height: 1;
}

.after\:text-varLIGHTBLUEFEATHER::after{
  content: var(--tw-content);
  --tw-text-opacity: 1;
  color: rgb(65 154 255 / var(--tw-text-opacity));
}

.after\:opacity-25::after{
  content: var(--tw-content);
  opacity: 0.25;
}

.after\:transition-all::after{
  content: var(--tw-content);
  transition-property: all;
  transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
  transition-duration: 150ms;
}

.after\:duration-500::after{
  content: var(--tw-content);
  transition-duration: 500ms;
}

.after\:content-\[\'\'\]::after{
  --tw-content: '';
  content: var(--tw-content);
}

.after\:content-\[\'\\201D\'\]::after{
  --tw-content: '\201D';
  content: var(--tw-content);
}

.visited\:text-varDARKBEAK:visited{
  color: rgb(112 24 26 );
}

.visited\:text-varMEDBEAK:visited{
  color: rgb(150 32 35 );
}

.hover\:bg-varLIGHTBEAKTOP:hover{
  --tw-bg-opacity: 1;
  background-color: rgb(252 168 2 / var(--tw-bg-opacity));
}

.hover\:bg-varMEDBEAKTOP:hover{
  --tw-bg-opacity: 1;
  background-color: rgb(182 121 2 / var(--tw-bg-opacity));
}

.hover\:text-red-600:hover{
  --tw-text-opacity: 1;
  color: rgb(220 38 38 / var(--tw-text-opacity));
}

.hover\:text-varLIGHTBEAK:hover{
  --tw-text-opacity: 1;
  color: rgb(215 45 50 / var(--tw-text-opacity));
}

.hover\:text-varLIGHTBEAKTOP:hover{
  --tw-text-opacity: 1;
  color: rgb(252 168 2 / var(--tw-text-opacity));
}

.hover\:text-varLIGHTBLUEFEATHER:hover{
  --tw-text-opacity: 1;
  color: rgb(65 154 255 / var(--tw-text-opacity));
}

.hover\:text-varLIGHTWING:hover{
  --tw-text-opacity: 1;
  color: rgb(207 166 157 / var(--tw-text-opacity));
}

.hover\:text-varMEDBEAK:hover{
  --tw-text-opacity: 1;
  color: rgb(150 32 35 / var(--tw-text-opacity));
}

.hover\:text-varMEDBEAKTOP:hover{
  --tw-text-opacity: 1;
  color: rgb(182 121 2 / var(--tw-text-opacity));
}

.active\:bg-varLIGHTBLUEFEATHER:active{
  --tw-bg-opacity: 1;
  background-color: rgb(65 154 255 / var(--tw-bg-opacity));
}

.active\:text-varDARKBEAK:active{
  --tw-text-opacity: 1;
  color: rgb(112 24 26 / var(--tw-text-opacity));
}

.active\:text-varLIGHTBEAK:active{
  --tw-text-opacity: 1;
  color: rgb(215 45 50 / var(--tw-text-opacity));
}

.active\:text-varLIGHTBLUEFEATHER:active{
  --tw-text-opacity: 1;
  color: rgb(65 154 255 / var(--tw-text-opacity));
}

@media (prefers-color-scheme: dark){
  .dark\:border-none{
    border-style: none;
  }

  .dark\:bg-black{
    --tw-bg-opacity: 1;
    background-color: rgb(0 0 0 / var(--tw-bg-opacity));
  }

  .dark\:bg-white{
    --tw-bg-opacity: 1;
    background-color: rgb(255 255 255 / var(--tw-bg-opacity));
  }

  .dark\:text-slate-400{
    --tw-text-opacity: 1;
    color: rgb(148 163 184 / var(--tw-text-opacity));
  }

  .dark\:text-varLIGHTWING{
    --tw-text-opacity: 1;
    color: rgb(207 166 157 / var(--tw-text-opacity));
  }

  .dark\:text-white{
    --tw-text-opacity: 1;
    color: rgb(255 255 255 / var(--tw-text-opacity));
  }
}

@media (min-width: 640px){
  .sm\:block{
    display: block;
  }

  .sm\:hidden{
    display: none;
  }

  .sm\:flex-row{
    flex-direction: row;
  }

  .sm\:p-4{
    padding: 1rem;
  }

  .sm\:pt-0{
    padding-top: 0px;
  }

  .sm\:text-2xl{
    font-size: 1.5rem;
    line-height: 2rem;
  }

  .sm\:text-3xl{
    font-size: 1.875rem;
    line-height: 2.25rem;
  }

  .sm\:text-4xl{
    font-size: 2.25rem;
    line-height: 2.5rem;
  }

  .sm\:text-6xl{
    font-size: 3.75rem;
    line-height: 1;
  }

  .sm\:text-8xl{
    font-size: 6rem;
    line-height: 1;
  }

  .sm\:text-\[1\.74rem\]{
    font-size: 1.74rem;
  }

  .sm\:text-lg{
    font-size: 1.125rem;
    line-height: 1.75rem;
  }
}

@media (min-width: 768px){
  .md\:text-2xl{
    font-size: 1.5rem;
    line-height: 2rem;
  }
}

@media (min-aspect-ratio: 3/2){
  .widescreen\:section-min-height {
    min-height: calc(100vh - 68px)
  }
}

@media (max-aspect-ratio: 13/20){
  .tallscreen\:section-min-height {
    min-height: calc(100vh - 68px)
  }
}

@media (orientation: landscape){
  .landscape\:text-center{
    text-align: center;
  }
}