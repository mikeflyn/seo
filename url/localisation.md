# Localisation

If you manage one or more websites designed for users in a specific country speaking a specific language, you want to make sure that search results display the relevant language and country version of your pages. To ensure that your content reaches the correct audience, you will use two general mechanisms:

**URL-level targeting**  
You can use three implementation mechanisms for this:

**Page-level markup**    
Use the   `<link rel="alternate" hreflang="x" href="alternateURL">` tag in the `<head>` section of your pages to list alternate language versions for each page.  Each page should provide an `hreflang` tag that links to all other language variants of itself, as well as a tag that refers back to itself.  For more granular targeting, you can use the `hreflang` attribute to indicate language _and_ country combinations \(e.g. `en-ie`, `en-ca`, `en-us`\). Read more about the `hreflang` tag in Google's Content guidelines section.  





**Site-wide targeting**- In addition making sure your site URLs map to alternate language variants, you will also likely use geographic-specific domains or configure your entire site structure to deliver content to a specific geographic and language preference.  To learn more, read the best practices as explained in [Multi-regional and multilingual sites](https://support.google.com/webmasters/answer/182192) in Google's Content guidelines.





Once you have configured multi-language or multi-regional sites and pages, you can use two sections in the International targeting pages to keep your international presence healthy:  


1.The **Language** section—this helps you ensure your `hreflang` tags use the correct locale codes \(language and optional country\).  More commonly, you can make sure that alternate pages have tags that link back to the pages for your site.  

2. The **Country** section—you can use this tool to set a site-wide country target for your entire site, if necessary.

