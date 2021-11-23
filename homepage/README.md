<p align="center">
  <img src="https://github.com/denverprophitjr/Website-Scemas/blob/main/website-schemas.png" alt="Website SChemas" />
</p>

# The goal of this project is to provide guidance and suggested JSON-LD markup for your website.

## [Homepage Schema](#homepage)
Logo dimmenions are suggested to remain 500 pixels by 500 pixels.

Line 2 can be any subset of [*Organization*](https://schema.org/Organization#subtypes "Organization Sub-Types") _right click open in new tab_
```"founders":[
    {
      "@type":"Person",
      "name":"founder #1 (list all founders)"
      "@id": "",
    }
    ~~~
  ],
  ```
  Search person in google knowledge graph. Click the share URL option. Insert into the blank quotes. Alternatively, you can create a company roster page per role. `/about/team/denver-prophit.html` Include a person schema on the new page. Put the URL in the `"@id": ""` line inside the double quotes after `"@id":`
  
  For `availableLanguage`, if you support more than one language, enclose like so: `["English", "Spanish"],`
  *Edit* `sameAs` *URL's* must remain in quotes.
  
  *businessFunction* - You can use one of these to define your entities function.

```
http://purl.org/goodrelations/v1#ConstructionInstallation
http://purl.org/goodrelations/v1#Dispose
http://purl.org/goodrelations/v1#LeaseOut
http://purl.org/goodrelations/v1#Maintain
http://purl.org/goodrelations/v1#ProvideService
http://purl.org/goodrelations/v1#Repair
http://purl.org/goodrelations/v1#Sell
http://purl.org/goodrelations/v1#Buy
```
For `itemOffered` Head over to Wikipedia.org. Search for the main topic of what you do. My type was `Service`. Your's may be `Product` It just really depends!
