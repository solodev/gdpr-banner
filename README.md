# gdpr-banner


  		  
## Tutorial		  
For detailed instruction's, view Solodev's [How to Add a Cookies Bar for GDPR Compliance](https://www.solodev.com/blog/how-to-add-a-cookies-bar-for-gdpr-compliance.stml) article.
 
## Demo
  		  
Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/c8bt9e5s/).

## HTML

The tutorial contains the following basic HTML markup.

```
<div class="privacy-banner" style="border: 2px solid #ff910e; display: none;">
    <div class="banner-wrapper">
        <p>We use cookies to provide and improve our services. By using our site, you consent to cookies.
            <a href="/terms/privacy-policy.stml">Learn more</a>
        </p>
        <button aria-label="Close" style="background: #ff910e;" type="button">
            <span aria-hidden="true">x</span>
        </button>
    </div>
</div>
<section class="main-content">
    <h2>
        Et harum quidem rerum facilis
    </h2>
    <p>
        Et harum quidem rerum facilis est et expedita distinctio. Nam libero tempore, cum soluta nobis est eligendi optio cumque
        nihil impedit quo minus id quod maxime placeat facere possimus, omnis voluptas assumenda est, omnis dolor repellendus.
        Temporibus autem quibusdam et aut officiis debitis aut rerum necessitatibus saepe eveniet ut et voluptates repudiandae
        sint et molestiae non recusandae. Itaque earum rerum hic tenetur a sapiente delectus, ut aut reiciendis voluptatibus
        maiores alias consequatur aut perferendis doloribus asperiores repellat.
    </p>
</section>
<section class="sub-content">
    <h2>
        Et harum quidem rerum facilis
    </h2>
    <p>
        Et harum quidem rerum facilis est et expedita distinctio. Nam libero tempore, cum soluta nobis est eligendi optio cumque
        nihil impedit quo minus id quod maxime placeat facere possimus, omnis voluptas assumenda est, omnis dolor repellendus.
        Temporibus autem quibusdam et aut officiis debitis aut rerum necessitatibus saepe eveniet ut et voluptates repudiandae
        sint et molestiae non recusandae. Itaque earum rerum hic tenetur a sapiente delectus, ut aut reiciendis voluptatibus
        maiores alias consequatur aut perferendis doloribus asperiores repellat.
    </p>
</section>
      

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

