# Links
When it comes to links, like many things in the markdown language, there are two ways to do it. The simpliest way is to wrap the link with two angle brackets and away you go.

Many markdown editors, VSC included, will automatically make the link a hyperlink in the markdown preview when you enter in a proper web address, but as a general rule and for best practices, we should always wrap a link in angle brackets.

<http://www.google.com>

<https://www.amazon.ca>

Well that's a simple way to link directly to a URL/URI but in most cases we don't link directly to a site URI. Usually we link to a URI via another texted based link/description.

In order to do this, it's a little more involved but still very simple. In this case we wrap the anchor text in **SQUARE BRACKETS [ ]** and right after we put the hyperlink **wrapped in regular brackets/parenthesis ( )**.

For example:<br>
Check out my [Youtube account](https://www.youtube.com) for more great videos!

An extra option we have regarding links is to include a 'title tag' that will be displayed with a user hovers over the link.
We do this by including the text we want as the title tag, wrapped in double quotes, directly after the actual URI, still wrapped inside the round brackets/parenthesis.

Here's an example: [Mines Eye Media Facebook](https://www.facebook.com/mineseyemedia "This is the offical business Facebook page of Mines Eye Media")

On mouseOver of the above MEM FB page link, we can see the text display correctly.

A further options regarding links is that we can apply a token to the actual URI as a placeholder if we want. As Wes puts it, markdown is a language that's designed to be easy to read on the fly, and sometimes we may have a very long link that will throw off the readability of a website.

We can therefore apply a 'token' or reference to the link at the place of our link and then later on at the bottom, or our location of choosing we can define that link.<br>

Here's some examples:<br>
Check out the latest prices on the amazing [Amazon Echo!](https://www.amazon.ca/dp/B07NQ8YDJZ/ref=ods_gw_ha_H1_d_de_wake_dev_ca_092719_en?pf_rd_p=603fb310-345e-49c1-8ea7-8b9ebf6dd607&pf_rd_r=58SZVYS144R287B0KSEW)

The above link kind of breaks up the readability (apparently) of the markdown so instead for this next link, we'll apply a 'token'.

Check out the latest prices on the amazing [Amazon Echo!][1]

Then later on down the page, at the bottom or wherever we desire, we can 'define' the 'token' as so: (nothing should be present in the actual markdown preview here.)

[1]: https://www.amazon.ca/dp/B07NQ8YDJZ/ref=ods_gw_ha_H1_d_de_wake_dev_ca_092719_en?pf_rd_p=603fb310-345e-49c1-8ea7-8b9ebf6dd607&pf_rd_r=58SZVYS144R287B0KSEW

By using this method we could actually use one single token on many differnt links and have a central, single definition. That way, if we ever wanted to change or update the URI, we can just alter that one token variable vs changing independant links.

Also, it should be noted that the token used doesn't have to be a number specifically. It could be whatever deemed, but the point is to have it short and quick to type. For the above examples, it could have been 'echo' or 'ama', etc.