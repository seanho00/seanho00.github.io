---
layout: splash

header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/seanho-golden-ears.jpg
  caption: "The Golden Ears, &copy;2013 Sean Ho"
  excerpt: "Home page of Dr. Sean Ho"

intro: 
  - excerpt: ''

feature_left:
  - image_path: /assets/img/unsplash-c333d6YEhi0-bible.jpg
    alt: "Sermons by Sean"
    title: "Preaching"
    excerpt: 'Sermons in various Vancouver-area churches'
    url: "https://sermons.seanho.com/"
    btn_label: "Read More"
    btn_class: "btn--inverse"

feature_center:
  - image_path: /assets/img/unsplash-K3uOmmlQmOo-pencil_shavings.jpg
    alt: "Course material"
    title: "Teaching"
    excerpt: 'Course material from TWU'
    url: "https://twu.seanho.com/"
    btn_label: "Read More"
    btn_class: "btn--inverse"

feature_right:
  - image_path: /assets/img/unsplash-5fNmWej4tAA-laptops_work.jpg
    alt: "Anchorlytics Consulting"
    title: "Consulting"
    excerpt: 'Statistical consulting, data analysis, and forecasting'
    url: "https://anchorlytics.com/"
    btn_label: "Read More"
    btn_class: "btn--inverse"

---

{% include feature_row id="intro" type="center" %}

{% include feature_row id="feature_left" type="left" %}

{% include feature_row id="feature_center" type="center" %}

{% include feature_row id="feature_right" type="right" %}
