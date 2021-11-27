![Website Schemas](website-schemas.png)
# Website Schemas
Create website schemas that define your business or organization. All examples are in **JSON-LD** format. To include in your website code, you have to indicate you want to load a script like this: `<script type="application/ld+json">The code here</script>` In production mode, you ought to minify the "code". You can go to https://codebeautify.org/jsonminifier to accomplish this. Exclude the "<script type application/ld+json"> and ending </script> from the minification. Just the content of the code.

TOC
---
## Homepage Schema
I created the organization schema on the homepage. All others link to it. [View ➡](homepage/README.md "Home Page")

## About Page Schema
Includes additional details about the company including <abbr title="International Standard Industrial Classification of All Economic Activities">ISICV4</abbr> code. **ISIC** stands for International Standard Industrial Classification of All Economic Activities. This would be flexing linked data to further define your company's entity. A little known attribute defines the skill/expertise to be inferred about this entity. [View ➡](AboutPage/README.md "About Page")

## FAQ Page
Frequently Asked Questions attempts to answer questions about the brand / entity for SERP. Often displayed as a rich snippet in vanity searched for your entity name. Here is an example of what that rich snippet may look like if eligible to display.  [View ➡](FaqPage/README.md "FAQ Page")
![FAQ Schema in SERP](https://developers.google.com/search/docs/advanced/structured-data/images/faqpage-searchresult.png)

## Contact Page
Contact pages are often the "_call to action_". Contact Page converts to rich snippets about your company and can be displayed in the knowledge panel about your entity. [View ➡](ContactPage/README.md "Contact Page")

## Persons / Authors
Getting key persons of your organization into SERP knowledge panels are not as difficult as one might think. Tell google about new pages by following `https://www.google.com/ping?sitemap=https://www.example.com/?url=https://www.website.com/sitemap.xml` I would suggest you add an entry to your `robots.txt` with a line that reads: `Sitemap: http://www.example.com/sitemap.xml`

When the side panel begins to show for each person, Follow the guidelines at https://brandee.edu.vn/glossary/6325583-websearch-en/ after your Person entities are created and displaying to further tweak them. How much detail you put into the person is up to you. Go to https://schema.org/Person to see things I omitted. Ask in the discussions how to add it. [View ➡](PersonPage/README.md "Person Pages")
