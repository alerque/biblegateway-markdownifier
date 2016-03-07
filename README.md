# biblegateway-markdownifier

Userscript to generate markdown from Biblegateway.com

Once installed, simply browse to a passage on BibleGateway.com and a text area
will appear with formatted markdown.

![biblegateway.com preview](preview.png)

The markdown produced will follow this structure:

```
> **[Romans 8:1-2](https://www.biblegateway.com/passage/?search=romans+8%3A1-2&version=NIV)** (NIV)
>
> 8&nbsp;Therefore, there is now no condemnation for those who are in Christ Jesus, <sup>**2**</sup> because
through Christ Jesus the law of the Spirit who gives life has set you free from the law of sin and death.
```

and it will render like this:

> **[Romans 8:1-2](https://www.biblegateway.com/passage/?search=romans+8%3A1-2&version=NIV)** (NIV)
>
> 8&nbsp;Therefore, there is now no condemnation for those who are in Christ
> Jesus, <sup>**2**</sup> because through Christ Jesus the law of the Spirit
> who gives life has set you free from the law of sin and death.

## Installation instructions

1. Add tampermonkey to your web browser to run the userscript
1. Open the [js file in raw mode](https://github.com/scottTomaszewski/biblegateway-markdownifier/raw/master/biblegateway_markdownifier.user.js)

The tampermonkey should pick it up and ask you to install it.  Alternatively,
you can just copy the userscript into tampermonkey directly.

## Credit and Thanks

I didn't write the first iteration of this script, I just modified it to
support the new BibleGateway layout.  Original credit goes to
[alerque](https://github.com/alerque) and [dancek](https://github.com/dancek).
Thanks guys for getting this started.
