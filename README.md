# gdpr-banner
With GDPR in full swing, your website will need the tools to be GDPR compliant.

The European Union's GDPR regulations are in full swing, and websites around the world are struggling to comply to the changes. This is especially true for a variety of organizations who either wanted to wait and see how the regulations would impact their interests or how others were implementing the changes.


  		  
## Tutorial		  
For detailed instruction's, view Solodev's [How to Add a Cookies Bar for GDPR Compliance](https://www.solodev.com/blog/how-to-add-a-cookies-bar-for-gdpr-compliance.stml) article.
 
## Demo
  		  
Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/c8bt9e5s/).

## HTML

The tutorial contains the following basic HTML markup.

```
<div class="privacy-banner" style="border-top: 2px solid #ff910e; display: none;">
  <div class="banner-wrapper">
    <p>We use cookies to provide and improve our services. By using our site, you consent to cookies. <a href="/terms/privacy-policy.stml">Learn more</a></p>
    <button aria-label="Close" style="background: #ff910e;" type="button"><span aria-hidden="true">x</span></button>
  </div>
</div>
```

## Solodev Shortcode
```
[privacy_banner color="#ff910e" url="/terms/privacy-policy.stml"]
We use cookies to provide and improve our services. By using our site, you consent to cookies.
[/privacy_banner]
```

## CSS

All required CSS is contained with gdpr-banner.css

## JavaScript

All required JS is contained with gdpr-banner.js

## External Resources

This tutorial includes the following third party resources.

```
<script src="https://code.jquery.com/jquery-3.2.1.slim.min.js"></script>

```

