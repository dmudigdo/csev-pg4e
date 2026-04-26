
You also need to check out and configure phppgadmin

    git clone https://github.com/csev/phppgadmin.git
    cp scripts/config.inc.php phppgadmin/conf/config.inc.php

---

# Didi's Edits of Dr Chuck's PostgreSQL Notes

I am up to lecture 5, where Dr Chuck directly uses his notes in lectures. These lecture notes are in pure HTML without much CSS. I asked Claude to come up with a CSS file to prettify it, so that it is easier on the eyes.

It worked to a degree, but there were several errors in Dr Chuck's HTML that broke the CSS. I ran the HTML through a [validator](https://validator.w3.org/) and found the errors, I could see that this was written by hand, in one spot `target="blank"` was `traget="blank"`. I will work through it bit by bit, and it should be pretty soon.

