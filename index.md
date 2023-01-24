# Docsify-This LMS Content Pages

## Page Templates

*   [Home](home.md)
*   [Weekly Module](module-01.md)
*   [Schedule](schedule.md)
*   [Topics](topics.md)
*   [Resources](resources.md)
*   [UX Techniques Guide Page (using Accordion format)](ux-techniques-guide.md)
*   [Contact](contact.md)

## Embedding Docsify-This Pages into Other Platforms

### Canvas LMS

[Embed content in Canvas](https://www.howtocanvas.com/create-amazing-pages-in-canvas/embedding-content)  
iFrame Code Example, including URL parameters to seamlessly match Docsify-This content to Canvas:  

```html
<p><iframe style="overflow: hidden; border: 0px #ffffff none; background: #ffffff;" src="https://docsify-this.net?basePath=https://raw.githubusercontent.com/paulhibbitts/cmpt-363-222-pages/main&homepage=home.md&font-family=Lato%20Extended,%20Lato,Helvetica%20Neue,%20Helvetica,%20Arial,%20sans-serif&font-size=1&hide-credits=true" width="800px" height="1400px" allowfullscreen="allowfullscreen"></iframe></p>
```

[How do I add an external URL as a module item?](https://community.canvaslms.com/t5/Instructor-Guide/How-do-I-add-an-external-URL-as-a-module-item/ta-p/967)  
Module external link example:  

```html
https://docsify-this.net?basePath=https://raw.githubusercontent.com/paulhibbitts/cmpt-363/main/docs/222&homepage=week-02.md&toc-alt=true&font-family=Lato%20Extended,Lato,Helvetica%20Neue,Helvetica, Arial,sans-serif&font-size=1&hide-credits=true
```

[Redirect Tool (for adding a link as a navigation item in a course )](https://www.eduappcenter.com/apps/63?filter_text=#.X3uex2hKiM8)  
Redirect URL field example:  

```html
https://docsify-this.net/?basePath=https://raw.githubusercontent.com/paulhibbitts/cmpt-363-222-pages/main&homepage=resources.md&edit-link=https://github.com/paulhibbitts/cmpt-363-222-pages/blob/main/resources.md&font-family=Lato%20Extended, Lato,Helvetica%20Neue, Helvetica, Arial, sans-serif&font-size=1&hide-credits=true
```

### Moodle LMS

[iFrame (for embedding content within pages)](https://docs.moodle.org/401/en/Iframe)  

[External tool (for adding a link to course navigation or elements)](https://docs.moodle.org/401/en/External_tool)