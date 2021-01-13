# MUSTACHE and FLEXBOX

## What ive learned

- Javascript templating is a fast and efficient technique to render client-side view templates with Javascript by using a JSON data source
- Mustache is a logic-less template syntax. It can be used for HTML, config files, source code — anything. It works by expanding tags in a template using values provided in a hash or object.
It is often referred to as “logic-less” because there are no if statements, else clauses, or for loops. Instead, there are only tags. Some tags are replaced with a value, some nothing, and others a series of values.
- Mustache.render(“Hello, {{name}}”, { name: “Sherlynn” });
// returns: Hello, Sherlynn
-In the above, we see two braces around {{ name }}. This is Mustache syntax to show that it is a placeholder.
- Mustache is a specification for a templating language.
- If you intend you use mustache with Node and Express, you can use mustache-express.
![mustache example](https://miro.medium.com/max/700/1*FRcL9NQHI7Cvi2ELLmzJGQ.png)

### flex-box code 

- row (default): left to right in ltr; right to left in rtl
- row-reverse: right to left in ltr; left to right in rtl
- column: same as row but top to bottom
- column-reverse: same as row-reverse but bottom to top
- flex-wrap two rows of boxes, the first wrapping down onto the second By default, flex items will all try to fit onto one line. You can change that and allow the items to wrap as needed with this property.
- flex-flow This is a shorthand for the flex-direction and flex-wrap properties, which together define the flex container’s main and cross axes. The default value is row nowrap.
  
### align-items

- stretch (default): stretch to fill the container (still respect min-width/max-width)
- flex-start / start / self-start: items are placed at the start of the cross axis. The difference between these is subtle, and is about respecting the - flex-direction rules or the writing-mode rules.
- flex-end / end / self-end: items are placed at the end of the cross axis. The difference again is subtle and is about respecting flex-direction rules vs. writing-mode rules.
- center: items are centered in the cross-axis
- baseline: items are aligned such as their baselines align
  
  [Back to main](README.md)