---
title: "Chapter Activity"
layout: default
pages:
  - title: "May 2024 Workshop with Visiting Professor Noritaka Noda"
    url: "2024-05-01.Professor_Noda_Workshop/"
    image: "https://live.staticflickr.com/65535/53742639406_e181fdbfea_b.jpg"
  - title: "2022 Chapter Luncheon"
    url: "2022-06-01.Chapter_Luncheon/"
    image: "2022-06-01.Chapter_Luncheon/20220611-122314.jpg"
  - title: "2019 Chapter Luncheon"
    url: "2019-09-01.Chapter_Luncheon/"
    image: "2019-09-01.Chapter_Luncheon/img-1490.jpg"
  - title: "May 2019 Workshop with Visiting Professor Yoshitada Sato"
    url: "2019-05-01.Professor_Sato_Workshop/"
    image: "2019-05-01.Professor_Sato_Workshop/img-1418.jpg"
  - title: "2018 Chapter Luncheon"
    url: "2018-09-01.Chapter_Luncheon/"
    image: "2018-09-01.Chapter_Luncheon/no-1.jpg"
  - title: "June 2018 Workshop with Visiting Professor Kubota"
    url: "2018-06-01.Professor_Kubota_Workshop/"
    image: "2018-06-01.Professor_Kubota_Workshop/img-1275.jpg"
  - title: "September 2017 Chapter Luncheon and Ikebana Demonstration"
    url: "2017-09-09.Chapter_Luncheon/"
    image: "2017-09-09.Chapter_Luncheon/cptr-luncheon-sep2017-001-copy.jpg"
  - title: "June 2017 Workshop with Visiting Professor Mayumi Chino"
    url: "2017-06-01.Professor_Chino_Workshop/"
    image: "2017-06-01.Professor_Chino_Workshop/img-0949.jpg"
  - title: "September 2016 Luncheon"
    url: "2016-09-17.Chapter_Luncheon/"
    image: "2016-09-17.Chapter_Luncheon/img-0829.jpg"
  - title: "March 2016 Workshop with Professor Kiyoshi Imagawa"
    url: "2016-03-01.Professor_Imagawa_Workshop/"
    image: "2016-03-01.Professor_Imagawa_Workshop/5912925.jpg"
  - title: "March 2015 Workshop with Senior Professor Makoto Fujii"
    url: "2015-03-01.Professor_Fujii_Workshop/"
    image: "2015-03-01.Professor_Fujii_Workshop/8522960.jpg"
  - title: "August 2014 Demonstration and Chapter Luncheon"
    url: "2014-08-01.Demonstration_and_Luncheon/"
    image: "2014-08-01.Demonstration_and_Luncheon/9836619.jpg"
  - title: "Ribbon Cutting and Exhibition"
    url: "2012-07-28.Anniversary_Ribbon_Cutting/"
    image: ""
  - title: "Reishiki-Ike"
    url: "2012-07-28.Anniversary_Reishiki_Ike/"
    image: ""
  - title: "Demonstration"
    url: "2012-07-28.Anniversary_Demonstration/"
    image: ""
  - title: "Banquet"
    url: "2012-07-28.Anniversary_Banquet/"
    image: ""
  - title: "July 2012 10th Anniversary Celebration with Headmaster Sen'ei Ikenobo"
    url: "2012-07-28.10th_Anniversary_Celebration/"
    image: ""
  - title: "10th Anniversary Event Introduction (2012)"
    url: "2012-01-01.Anniversary_Introduction/"
    image: ""
  - title: "Our Activities"
    url: "2010-01-01.Our_Activities/"
    image: "2010-01-01.Our_Activities/6868604.jpg"
---

# Chapter Activities

Please enjoy the photos of our Chapter activities.

<ul class="page-list">
{% for p in page.pages %}
  <li>
    <a href="{{ p.url }}">{{ p.title }}</a>
    {% if p.image != "" %}
    <br><a href="{{ p.url }}"><img src="{{ p.image }}" alt="{{ p.title }}"></a>
    {% endif %}
  </li>
{% endfor %}
</ul>
