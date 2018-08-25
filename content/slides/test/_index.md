---
title: 'Demo RemarkJS Slideshow '
date: "2018-06-02T16:43:02-04:00"
outputs: "Reveal"

reveal_hugo:
    parallax_background_image: 'https://s3.amazonaws.com/hakim-static/reveal-js/reveal-parallax-1.jpg'
    theme: black
    templates:
        fish:
            class: fish
            background-image: "https://source.unsplash.com/nI3bUW1Xqik/420x600"
            background-size: "50%"
            state: "opacity50"
---
# title
---
{{< slide state="opacity50" background-image="https://source.unsplash.com/nI3bUW1Xqik/420x600" background-size="50%" >}}
# H1
## H2
### H3

---

{{< slide state="opacity30" background-image="https://d33ypg4xwx0n86.cloudfront.net/direct?url=https%3A%2F%2Fstatic01.nyt.com%2Fimages%2F2018%2F08%2F12%2Ffashion%2F12IOWAGUNS1%2F12IOWAGUNS1-articleLarge-v2.jpg%3Fquality%3D75%26auto%3Dwebp%26disable%3Dupscale&resize=w1408" >}}
# image 

---

{{< figure src="https://d33ypg4xwx0n86.cloudfront.net/direct?url=https%3A%2F%2Fstatic01.nyt.com%2Fimages%2F2018%2F08%2F12%2Ffashion%2F12IOWAGUNS1%2F12IOWAGUNS1-articleLarge-v2.jpg%3Fquality%3D75%26auto%3Dwebp%26disable%3Dupscale&resize=w1408" title="Steve Francia" >}}

---
{{< slide background="linear-gradient(to top, #ff00cc, #333399)" state="opacity30" >}}
![alt text](data:image/gif;base64,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)

This is `inline` code
---

Slide with a footnote.[^fn1]

[^fn1]: This is the footnote.

{{% note %}}
Don't forget to thank the audience.
{{% /note %}}

---

Name    | Age
--------|------
Bob     | 27
Alice   | 23
---
#code
``` go
func getTrue() bool {
    return true
}
```
---

<section data-noprocess data-background-iframe="https://slides.com" data-background-interactive>
	<h2>Iframe</h2>
</section>

---

## Definitions

This is a ** **bold** ** word.  Italics _ _italics_ _

~~Cat~~
: Fluffy animal everyone likes 

Internet
: Vector of transmission for pictures of cats

> "This is a quote"   
<cite>- Author</cite>

---
{{< slide template="fish" >}}

* This is a sentence
* This is a sentence that is longer
* This is a sentence that is longer This is a sentence that is longer This is a sentence that is longer


---

{{< frag c="This is a sentence" class="bullet" >}}
{{< frag c="This is a sentence that is longer" class="bullet" >}}
{{< frag c="This is a sentence that is longer This is a sentence that is longer This is a sentence that is longer" class="bullet" >}}

---

{{< youtube w7Ft2ymGmfc >}}

---
{{< slide name="vimeo" >}}
{{< vimeo 141800188 >}}this is vimeo

---
Footnotes:
