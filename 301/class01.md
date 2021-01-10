# SMACSS and Responsive Web Design

## what I've Learned: Responsive Web Design

- Responsive web design is the practice of building a website suitable to work on every device and every screen size, no matter how large or small, mobile or desktop.
- Responsive generally means to react quickly and positively to any change, while adaptive means to be easily modified for a new purpose or situation, such as change.
- With responsive design websites continually and fluidly change based on different factors, such as viewport width, while adaptive websites are built to a group of preset factors. A combination of the two is ideal, providing the perfect formula for functional websites.
-Responsive web design is broken down into three main components, including flexible layouts, media queries, and flexible media.
- Using the flexible grid formula we can take all of the fixed units of length and turn them into relative units. In this example we’ll use percentages but em units would work equally as well.
- Taking the flexible layout concept, and formula, and reapplying it to all parts of a grid will create a completely dynamic website, scaling to every viewport size. For even more control within a flexible layout, you can also leverage the min-width, max-width, min-height, and max-height properties.
- Media queries provide the ability to specify different styles for individual browser and device circumstances, the width of the viewport or device orientation for example.
- here are a couple different ways to use media queries, using the @media rule inside of an existing style sheet, importing a new style sheet using the @import rule, or by linking to a separate style sheet from within the HTML document.
- Logical operators in media queries help build powerful expressions. There are three different logical operators available for use within media queries, including and, not, and only.
- The orientation media feature determines if a device is in the landscape or portrait orientation.
- The aspect-ratio and device-aspect-ratio features specifies the width/height pixel ratio of the targeted rendering area or output device.
- One quick way to make media scalable is by using the max-width property with a value of 100%. Doing so ensures that as the viewport gets smaller any media will scale down according to its containers width.
  
### What is “Float”?

- Float is a CSS positioning property.
- In web design, page elements with the CSS float property applied to them are just like the images in the print layout where the text flows around them. Floated elements remain a part of the flow of the web page. This is distinctly different than page elements that use absolute positioning.
- There are four valid values for the float property. Left and Right float elements those directions respectively. None (the default) ensures the element will not float and Inherit which will assume the float value from that elements parent element.
- Aside from the simple example of wrapping text around images, floats can be used to create entire web layouts.
- Float’s sister property is clear. An element that has the clear property set on it will not move up adjacent to the float like the float desires, but will move itself down past the float
- If this parent element contained nothing but floated elements, the height of it would literally collapse to nothing.
- 
  [Back to main](301/README.md)