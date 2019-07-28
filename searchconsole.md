## Submit your website to Search Engines

> Nowadys, it seems to be a standard to have a persoal website for Ph.D. candidates in the field of economics. Every year, before on the market, most of the candidates build their own websites on google sites/ weebly/ wix etc. However, if you want to make your site to be visible in the search engines ad improve the visits, you need to submit/verify your site with one or moore search engines. Here I take Google as an example. 

Now I assume you have a personal website called xyz.com or xyz.weely.com. The very next step for you to do is to go to the Goole Search Console:

https://www.google.com/webmasters

Then you can click to add property and it promotes the following box:

![searchconsole](https://raw.githubusercontent.com/zxecon/latex-markdown/master/searchconsole.png)

Personally speaking, I reconmmend the second one: URL prefix, which is easier and quicker, especially when you create your website that is published to a free subdomain, like xzy.weebly.com. I will explain more on the first one at the end.

After you add the URL and click "Continue", it will provide a varierty of ways to verify your ownership. If you build your site with Weebly or Wix, you can add a html code (provided by Google) like following in the pages' *head* section:

```html
<HTML>
  <HEAD>
    <TITLE>Your Page Title</TITLE>
    <meta name="google-site-verification" content="your verification string">
  </HEAD>
<BODY>
```
If everthing goes well, you can now see "you are a verified owner" of this website and it will appear in Google search. After this, you can also add page/website description when you build/modify your website to improve the accuracy of search. 

<HTML>
  <HEAD>
    <TITLE>Your Page Title</TITLE>
    <meta name="google-site-verification" content="your verification string">
  </HEAD>
<BODY>

> New Google Sites pages that you create should automatically appear and be verified in your Search Console account. If your site doesn't appear automatically on the Search Console home page, click Add a site. Your site will be verified automatically.

PS: Domain Verification
After you choose this one, you will get a TXTX record from Google. Then you can add this TXT record to your domain provider. For Weebly users, simply click "Domains" on the starting page and click "manage". At the DNS records section, you can add your TXT after clicking "edit".

Please allow several hours for the verification. 
After all these steps, you can now see your websites' apperence with decription words. And also, you can use "Google Analytics" to see the activities of your website (number of visits, pages been browsed, etc.)

References: [Weebly Support](https://www.weebly.com/app/help/us/en/topics/verify-your-site-with-search-engines); [Google Support](https://support.google.com/webmasters/answer/34592?hl=en)
