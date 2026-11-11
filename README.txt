CEDAR PRACTICE WEBSITE - FIVE PAGE STARTER

Upload the contents of this ZIP to the root of your GitHub Pages repository.
Practice website base URL: https://madhuriworking0-spec.github.io/digital-marketing-practice/

Pages included:
- index.html (from home.html)
- about-us.html
- careers.html
- get-in-touch.html
- contact-us.html (redirects to Get in Touch)

Important checks:
- The supplied contactus.html was byte-for-byte identical to careers.html and had the title "Careers". It is therefore not used as a separate Contact Us page; contact-us.html safely redirects to Get in Touch.
- Internal links to the supplied pages now use the practice website. Links to pages not included in this five-page set return to the practice homepage rather than opening the original dev website.
- The supplied HTML depends on stylesheets, scripts, and images hosted on dev.cedarmanagement.co.uk. Those asset URLs are retained so the design can render. They load resources but are not page-navigation links. To make the site fully independent, those assets must be downloaded and bundled in a later step.
- GTM container GTM-KVCZPH7C was added to the four full HTML pages (head and noscript).
- Contact forms / WordPress functions may not submit on static GitHub Pages without a backend.
