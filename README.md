# Horiseon Homepage Refactor

This project involves refactoring the Horiseon Homepage to make the page's files easier to
understand and to add accesibility in the form of a webpage title and image alt messages. Many of
the html semantic tags are changed to make their roles clearer, including changing generic "div" to "aside."
Many redundant classes with the same purpose are combined to reduce clutter. CSS classes are reordered to
reflect their usage in the HTML. IDs without unique changes were removed. Moved main banner image call to
html for clarity and consistency.

## Built With

* [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
* [Git]
* [Github](https://github.com/)

## Deployed Link

* [See Live Site](https://rslepejian.github.io/refactoring-example-site/)

## Preview of Working Site

![Image](assets/images/01-html-css-git-homework-demo.png)

## Code Snippet

This code snippet was chosen because it houses the main information displayed on the webpage.

```html
    <article class="content">
        <!-- This is subsection one of the main content -->
        <div id = "search-engine-optimization" class="content-sub">
            <!-- Subsection image, floated left -->
            <img src="./assets/images/search-engine-optimization.jpg" class="float-left" alt = "Workstation image" />
            <!-- Subsection title -->
            <h2>Search Engine Optimization</h2>
            <!-- Subsection content -->
            <p>
                The dominance of mobile internet use means that users are searching for the right business as they travel, shop, or sit on their couch at home. Search Engine Optimization (SEO) allows you to increase your visibility and find the right customers for your business.
            </p>
        </div>
        <!-- Main content subsection two -->
        <div id = "online-reputation-management" class="content-sub">
            <img src="./assets/images/online-reputation-management.jpg" class="float-right" alt = "Reputation up" />
            <h2>Online Reputation Management</h2>
            <p>
                The web is full of opinions, and some of these can be negative. Social media allows anyone with an internet connection to say whatever they want about your business. Online Reputation Management gives you the control over what potential customers see when they search for your business.
            </p>
        </div>
        <!-- Main content subsection three -->
        <div id = "social-media-marketing" class="content-sub">
            <img src="./assets/images/social-media-marketing.jpg" class="float-left" alt = "Social Media Logos" />
            <h2>Social Media Marketing</h2>
            <p>
                Social media continues to have a sizable influence on buying habits. Social media marketing helps you determine which platforms are suited to your brand, using analytics to find the right markets and increase your lead generation.
            </p>
        </div>
    </article>
```

## Authors

* **Raffi Lepejian** 

## Contact Information

- [Link to Portfolio Site](#)
- [Link to Github](https://github.com/rslepejian)
- [Link to LinkedIn](https://linkedin.com/in/raffi-lepejian-071876153)

