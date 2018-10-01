---
description: >-
  The hreflang attribute tells Google which language you are using on a specific
  page, so the search engine can serve that result to users searching in that
  language.
---

# hreflang for language and regional URLs

## How to Setup Hreflang Tags for International SEO

The **hreflang** attribute \(also referred to as `rel="alternate" hreflang="x"`\) tells Google which language you are using on a specific page, so the search engine can serve that result to users searching in that language.

Code-

```markup
<link rel="alternate" href="http://example.com" hreflang="en-us" />
```



#### HTML &lt;head&gt; Hreflang Example

```markup
<link rel="alternate" hreflang="en-us" href="https://site.com/us/en/page-a" />
<link rel="alternate" hreflang="en-ca" href="https://site.com/ca/en/page-a" />
<link rel="alternate" hreflang="fr" href="https://site.com/ca/fr/page-a" />
<link rel="alternate" hreflang="en-gb" href="https://site.com/uk/en/page-a" />
<link rel="alternate" hreflang="es" href="https://site.com/es/page-a" />
<link rel="alternate" hreflang="x-default" href="https://site.com/us/en/page-a" />
```

### Use Hreflang tag Generator to easily generate Hreflang tags.

{% hint style="info" %}
[https://www.aleydasolis.com/english/international-seo-tools/hreflang-tags-generator/](https://www.aleydasolis.com/english/international-seo-tools/hreflang-tags-generator/)
{% endhint %}

Many websites serve users from around the world with content translated or targeted to users in a certain region. Google uses the `rel="alternate" hreflang="x"` attributes to serve the correct language or regional URL in Search results.

{% embed data="{\"url\":\"https://www.youtube.com/watch?v=8ce9jv91beQ\",\"type\":\"video\",\"title\":\"Expanding your site to more languages\",\"description\":\"Google covers best practices for expanding your site to new languages or country-based language variations. We discuss use cases of international sites, implementation of rel=\\\"alternate\\\" hreflang, and best practices.\\n\\nWebmaster Help Center article on rel=\\\"alternate\\\" hreflang and hreflang=\\\"x-default\\\":\\nhttps://support.google.com/webmasters/answer/189077\\n\\nWorking with multilingual sites:\\nhttp://googlewebmastercentral.blogspot.com/2010/03/working-with-multilingual-websites.html\\n\\nWorking with multiregional sites:\\nhttp://googlewebmastercentral.blogspot.com/2010/03/working-with-multi-regional-websites.html\\n\\nNew markup for multilingual content:\\nhttp://googlewebmastercentral.blogspot.com/2011/12/new-markup-for-multilingual-content.html\\n\\nIntroducing \\\"x-default hreflang\\\" for international landing pages:\\nhttp://googlewebmastercentral.blogspot.com/2013/04/x-default-hreflang-for-international-pages.html\\n\\nWebmaster discussion forum FAQ on internationalization:\\nhttps://sites.google.com/site/webmasterhelpforum/en/faq-internationalisation\\n\\nWebmaster discussion forum for internationalization:\\nhttp://productforums.google.com/forum/\#!categories/webmasters/internationalization\",\"icon\":{\"type\":\"icon\",\"url\":\"https://www.youtube.com/yts/img/favicon\_144-vfliLAfaB.png\",\"width\":144,\"height\":144,\"aspectRatio\":1},\"thumbnail\":{\"type\":\"thumbnail\",\"url\":\"https://i.ytimg.com/vi/8ce9jv91beQ/maxresdefault.jpg\",\"width\":1280,\"height\":720,\"aspectRatio\":0.5625},\"embed\":{\"type\":\"player\",\"url\":\"https://www.youtube.com/embed/8ce9jv91beQ?rel=0&showinfo=0\",\"html\":\"<div style=\\\"left: 0; width: 100%; height: 0; position: relative; padding-bottom: 56.2493%;\\\"><iframe src=\\\"https://www.youtube.com/embed/8ce9jv91beQ?rel=0&amp;showinfo=0\\\" style=\\\"border: 0; top: 0; left: 0; width: 100%; height: 100%; position: absolute;\\\" allowfullscreen scrolling=\\\"no\\\"></iframe></div>\",\"aspectRatio\":1.7778}}" %}



Some example scenarios where `rel="alternate" hreflang="x"` is recommended:

You **keep the main content in a single language** and **translate only the template**, such as the navigation and footer. Pages that feature user-generated content, like forums, typically do this.

Your content has **small regional variations** with **similar content in a single language**. For example, you might have English-language content targeted to the US, GB, and Ireland.

Your site content is **fully translated**. For example, you have both German and English versions of each page.



### Using language annotations

Imagine you have an English language page hosted at `http://www.example.com/`, with a Spanish alternative at `http://es.example.com/`. You can indicate to Google that the Spanish URL is the Spanish-language equivalent of the English page in one of three ways:



H**TML link element in header.** In the HTML `<head>` section of http://www.example.com/, add a `link` element pointing to the Spanish version of that webpage at http://es.example.com/, like this:

```markup
<link rel="alternate" hreflang="es" href="http://es.example.com/" />
```



If you have multiple language versions of a URL, each language page should identify different language versions, including itself.  For example, if your site provides content in French, English, and Spanish, the Spanish version must include a `rel="alternate" hreflang="x"` link for itself **in addition to** links to the French and English versions. Similarly, the English and French versions must each include the same references to the French, English, and Spanish versions.





