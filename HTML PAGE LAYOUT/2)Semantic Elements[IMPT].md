Semantic Elements [Important]
• Semantic elements provide clear meanings to both the browser and developers.
• Examples of non-semantic elements like <div> and <span> convey no information about their content.
• In contrast, semantic elements such as <footer>, <header>, and <article> offer clear definitions of their content.
• Incorporating semantic elements enhances website accessibility and contributes to a well-organized website structure.
• HTML5 introduces specific semantic tags that enable more intuitive layout definitions compared to the generic <div> tag.
• A semantic tag's name reflects its purpose.

```html
<header>
  <!-- Defines the masthead or other header information on the page.
  Typically repeated on every page of a site, though not mandatory. -->
</header>

<nav>
  <!-- Defines a container for navigation links. -->
</nav>

<footer>
  <!-- Defines the text at the bottom of a page, such as copyright or contact information.
  Typically repeated on every page of the site. -->
</footer>

<article>
  <!-- Defines a block of text representing a single article, story, or message.
  Can stand alone logically; for example, on a news site, each news story is an article. -->
</article>

<aside>
  <!-- Defines a block of text tangential to the main discussion, like a note, tip, or caution.
  Can be removed without disrupting the main document. -->
</aside>

<section>
  <!-- Defines a generic content or application section.
  Examples include book chapters or numbered sections of a thesis.
  A site's home page could be split into sections such as Introduction, News, and Contact Information.
  A section begins with a heading, like <h2>, followed by other content.
  Use <section> if the area defined would be included in an outline of the document or page. -->
</section>
```