
# HTML
  * [Semantic Elements (main, nav, footer, etc)](https://caniuse.com/html5semantic)
  * [Custom](https://developer.mozilla.org/en-US/docs/Web/Web_Components/Using_custom_elements) Elements / [Extended](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/is) Elements ([polyfill](https://github.com/ungap/custom-elements#readme) for safari)
  * [Email, URL](https://caniuse.com/input-email-tel-url), [Range](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/range), [Date](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/date), [Search](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/search) inputs
  * [Form validation](https://caniuse.com/form-validation)
  * Input [Minimum](https://caniuse.com/input-minlength) / [Pattern](https://caniuse.com/input-pattern) / [Suggestions ](https://caniuse.com/datalist)
  * [Button type](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/button#attr-type) (not all form buttons submit)
  * [Dialog](https://caniuse.com/dialog)
  * [&amp;shy;](https://caniuse.com/css-hyphens) page-break hyphen hint
  * [Picture](https://caniuse.com/picture) Element
  * [SVG](https://caniuse.com/svg) & [WebP](https://caniuse.com/webp) (supports anim and alpha)
  * [MP3](https://caniuse.com/mp3) or [Opus](https://caniuse.com/?search=opus) audio codecs
  * [Template](https://caniuse.com/template) & [Slot](https://caniuse.com/mdn-html_elements_slot) Element
  * [Summary & Details](https://caniuse.com/details) Elements
  * [(Date) Time](https://caniuse.com/mdn-html_elements_time) Element
  * Script [module](https://caniuse.com/es6-module) type

# CSS
  * [Feature Support](https://caniuse.com/css-supports-api) Queries
  * [Media Queries](https://caniuse.com/css-mediaqueries)
    * Size Breakpoints (no vars)
    * Print
    * Prefers… [dark mode](https://developer.mozilla.org/en-US/docs/Web/CSS/@media/prefers-color-scheme), [reduced motion](https://developer.mozilla.org/en-US/docs/Web/CSS/@media/prefers-reduced-motion), [contrast](https://developer.mozilla.org/en-US/docs/Web/CSS/@media/prefers-contrast)
  * [Import](https://caniuse.com/mdn-css_at-rules_import) (great combined with queries)
  * [Nesting](https://caniuse.com/css-nesting) (newest browsers)
  * [Grid](https://caniuse.com/css-grid), [Flexbox](https://caniuse.com/flexbox), [Columns](https://caniuse.com/mdn-css_properties_columns)
  * [:is() & :where() selectors ](https://developer.mozilla.org/en-US/docs/Web/CSS/:where)
  * [Animation](https://caniuse.com/css-animation) & [transition](https://caniuse.com/mdn-css_properties_transition)
  * [Transform](https://caniuse.com/transforms2d)
  * [Viewport Units](https://caniuse.com/viewport-units): vh, vw
  * [hsla](https://caniuse.com/css3-colors) color values
  * [calc](https://caniuse.com/calc) & [var](https://caniuse.com/css-variables) (great for colors, font sizes)
  * [math min(), max() and clamp()](https://caniuse.com/css-math-functions)
  * [border](https://caniuse.com/border-image) [images](https://css-tricks.com/almanac/properties/b/border-image/) (9-slice borders)
  * [object- fit/position](https://caniuse.com/object-fit)
  * [WOFF](https://caniuse.com/woff) & [WOFF2](https://caniuse.com/woff2) web font format
  * [system-ui](https://caniuse.com/font-family-system-ui) font family (with [fallbacks](https://furbo.org/2018/03/28/system-fonts-in-css/))
  * [CSS Snap Points](https://caniuse.com/css-snappoints) ([tutorial](https://css-tricks.com/practical-css-scroll-snapping/))
  * [Resizable](https://caniuse.com/css-resize)
  * [aspect-ratio](https://developer.mozilla.org/en-US/docs/Web/CSS/aspect-ratio)
  * Input [in-/out-of-range](https://caniuse.com/css-in-out-of-range)

# JavaScript (ECMAScript)
  * [const](https://caniuse.com/const) and [let](https://caniuse.com/let) (var alternatives)
  * Array [includes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/includes), [some](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/some) and [every](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/every)
  * String [includes](https://caniuse.com/es6-string-includes), [padStart/padEnd](https://caniuse.com/pad-start-end)
  * [Nullish Coalescence](https://caniuse.com/mdn-javascript_operators_nullish_coalescing) (“??”)
  * [Optional Chaining](https://caniuse.com/mdn-javascript_operators_optional_chaining) (“?.”)
  * Event Listener [once](https://developer.mozilla.org/en-US/docs/Web/API/EventTarget/addEventListener#once) option
  * [Modules](https://caniuse.com/#feat=es6-module) (include) & [Classes](https://caniuse.com/#feat=es6-class)
  * [Exponentiation operator](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Exponentiation)
  * [Object literal property shorthand](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Object_initializer)
  * [Arrow Functions](https://caniuse.com/arrow-functions) (lambda equivalent)
  * [Template literals](https://caniuse.com/template-literals) (better string building)
  * Args: [Default](https://caniuse.com/mdn-javascript_functions_default_parameters), [Rest](https://caniuse.com/rest-parameters) & [Spread](https://caniuse.com/mdn-javascript_operators_spread_spread_in_function_calls)
  * [Intl.ListFormat](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl/ListFormat) ([polyfill](https://github.com/wessberg/intl-list-format) required)
  * [Web Animations API](https://caniuse.com/web-animation) (partial)
  * [Drag and Drop](https://caniuse.com/dragndrop)
  * [Promises](https://caniuse.com/promises) async, await, for… on
  * [Generators](https://caniuse.com/es6-generators) yield, for…of
  * [Map, Set, WeakMap, WeakSet](https://medium.com/ecmascript-2015/es6-set-map-weak-a2aeb7e2d384)
  * [Fetch](https://caniuse.com/fetch) & [URLSearchParams](https://caniuse.com/urlsearchparams)
  * [Websockets](https://caniuse.com/websockets)
  * [Web Workers](https://caniuse.com/webworkers)
  * [Service Worker](https://caniuse.com/serviceworkers) (push & cache)
  * [Web Storage](https://caniuse.com/namevalue-storage) ([session|local]Storage)
  * [IndexedDB (2.0)](https://caniuse.com/indexeddb2) (bigger storage)
  * [WebRTC](https://caniuse.com/rtcpeerconnection)
  * Speech [Synthesis](https://caniuse.com/speech-synthesis) & [Recognition](https://caniuse.com/speech-recognition)
  * [Canvas](https://caniuse.com/canvas) [2d, [webGL](https://caniuse.com/webgl)]
  * [Web Cryptography](https://caniuse.com/cryptography)
  * [Web Payments](https://web.dev/payments/)
  * [JSDoc](https://jsdoc.app/) - Documentation and Typing
  * [Standard Style](https://standardjs.com/rules) - the new style rules

# Other
  * [Web App Manifest](https://web.dev/add-manifest/) (PWA)
  * [Add to Homescreen Prompt](https://web.dev/customize-install/)
  * [Service Worker](https://developer.chrome.com/docs/workbox/service-worker-overview/) (caching and more)
  * [WebAssembly](https://caniuse.com/wasm) (higher-performance, compiled code)

# Linters
  * HTML: [LintHTML](https://linthtml.vercel.app/)
  * CSS: [StyleLint](https://stylelint.io/)
  * Javascript: [ESLint](https://eslint.org/)
