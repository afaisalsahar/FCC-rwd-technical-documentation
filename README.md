
# FreeCodeCamp Technical Documentation

This project is developed as part of FreeCodeCamp's responsive web design certification, leveraging HTML, CSS, TailwindCSS and component thinking.
BEM methodology is used for class names and Display/Position properties to create a responsive layout. The design is inspired by TailwindCSS documentation page. 

![Mockup](https://raw.githubusercontent.com/afaisalsahar/FCC-rwd-technical-documentation/main/assets/fcc-rwd-td-mockup.png)

## User Stories:

- You can see a `main` element with a corresponding `id="main-doc"`, which contains the page's main content (technical documentation)
- Within the `#main-doc` element, you can see several `section` elements, each with a class of main-section. There should be a minimum of five
- The first element within each `.main-section` should be a header element, which contains text that describes the topic of that section.
- Each `section` element with the class of `main-section` should also have an `id` that corresponds with the text of each `header` contained within it. Any spaces should be replaced with underscores (e.g. The section that contains the header "JavaScript and Java" should have a corresponding `id="JavaScript_and_Java"`)
- The `.main-section` elements should contain at least ten `p` elements total (not each)
- The `.main-section` elements should contain at least five `code` elements total (not each)
- The `.main-section` elements should contain at least five `li` items total (not each)
- You can see a `nav` element with a corresponding `id="navbar"`
- The navbar element should contain one `header` element which contains text that describes the topic of the technical documentation
- Additionally, the navbar should contain link (`a`) elements with the class of `nav-link`. There should be one for every element with the class `main-section`
- The `header` element in the `#navbar` must come before any link (`a`) elements in the navbar
- Each element with the class of `nav-link` should contain text that corresponds to the `header` text within each `section` (e.g. if you have a "Hello world" section/header, your navbar should have an element which contains the text "Hello world")
- When you click on a navbar element, the page should navigate to the corresponding section of the `#main-doc` element (e.g. If you click on a `.nav-link` element that contains the text "Hello world", the page navigates to a `section` element with that id, and contains the corresponding header)
- On regular sized devices (laptops, desktops), the element with `id="navbar"` should be shown on the left side of the screen and should always be visible to the user
- Your technical documentation should use at least one media query

## My two cents

I heard about TailwindCSS from my fellow bootcampers at Brainstation, and it was in my list for sometime now. I decided to use this project to learn it and play with it. 
At first it appeared to me just like any other CSS framework. However, I discovered that the utility-first approach makes CSS quick to write and simple to maintain. And as I experimented with its configuration and customization more, I became more and more aware of how incredibly powerful and robust TailwindCSS can be.

## Related

Developer Certification, representing approximately 300 hours of coursework.

[Responsive Web Design](https://www.freecodecamp.org/certification/afaisalsahar/responsive-web-design)