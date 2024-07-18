---
title: "Hi, I'm Acerola!"
layout: splash
permalink: /
date: 2024-02-11T11:48:41-04:00
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/lemon.png
  # actions:
  #   - label: "Download"
  #     url: "https://github.com/mmistakes/minimal-mistakes/"
  caption: "Photo credit: [**HelloImLemon**](https://helloimlemon.carrd.co/)"
excerpt: "Streams, Electronics/Hardware, Guides"
# intro: 
#   - excerpt: 'Welcome to my Site! I'm a Foxboy Vtuber, Variety Streamer, and Electronics Builder. Here, you can learn more about me, find out more about my projects, and find any guides and tutorials. My goal is to make the craft of streaming and VTubing more accessible, by putting the tools, information, and hardware at your disposal. Centered with `type="center"`'
feature_row:
  - image_path: /assets/images/@bunwithabow.png
    alt: "About Me"
    title: "About Me"
    excerpt: "Learn more about me and my content!"
    url: "/about/"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/Project.png
    alt: "Projects"
    title: "Projects"
    excerpt: "Learn more about my projects hardware projects!"
    url: "/projects/"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/Alice/ProductMic.jpeg
    alt: "Shop"
    title: "Shop"
    excerpt: "Visit my shop for hand-built electronics!"
    url: "https://ko-fi.com/acerola/shop"
    btn_label: "Read More"
    btn_class: "btn--primary"
# feature_row2:
#   - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
#     alt: "placeholder image 2"
#     title: "Placeholder Image Left Aligned"
#     excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
#     url: "#test-link"
#     btn_label: "Read More"
#     btn_class: "btn--primary"
# feature_row3:
#   - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
#     alt: "placeholder image 2"
#     title: "Placeholder Image Right Aligned"
#     excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
#     url: "#test-link"
#     btn_label: "Read More"
#     btn_class: "btn--primary"
# feature_row4:
#   - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
#     alt: "placeholder image 2"
#     title: "Placeholder Image Center Aligned"
#     excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
#     url: "#test-link"
#     btn_label: "Read More"
#     btn_class: "btn--primary"
---
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.1/css/all.min.css">
<style>
  .social-links {
    list-style: none;
    padding: 0;
    display: flex;
    justify-content: center; /* Adjust this for different alignments */
    gap: 20px; /* Spacing between buttons */
    flex-wrap: wrap; /* Allows the list to wrap on smaller screens */
  }
  .social-links li a {
    text-decoration: none; /* Remove underline */
    background-color: #333; /* Default background color */
    color: white;
    padding: 10px;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    width: 50px; /* Icon size */
    height: 50px; /* Icon size */
    transition: transform 0.3s;
  }
  .social-links li a:hover {
    text-decoration: none; /* Remove underline */
    transform: scale(1.1);
    box-shadow: 0 0 10px rgba(0,0,0,0.5);
  }
  /* Social Media Button Colors */
  .twitch { background-color: #6441A5; }
  .twitter { background-color: #1DA1F2; }
  .github { background-color: #333; }
  .email { background-color: #D44638; }
  .youtube { background-color: #FF0000; }
  .tiktok { background-color: #000000; }
</style>
<body>

<ul class="social-links">
  <li><a href="https://www.twitch.tv/acerolavr" class="twitch" target="_blank"><i class="fab fa-twitch"></i></a></li>
  <li><a href="https://twitter.com/acerowola" class="twitter" target="_blank"><i class="fab fa-twitter"></i></a></li>
  <li><a href="https://www.youtube.com/channel/UCot-DFd2ThpvsKqtOgi7tzg" class="youtube" target="_blank"><i class="fab fa-youtube"></i></a></li>
  <li><a href="https://www.tiktok.com/@acerolavr" class="tiktok" target="_blank"><i class="fab fa-tiktok"></i></a></li>
  <li><a href="https://github.com/AcerolaVR" class="github" target="_blank"><i class="fab fa-github"></i></a></li>
  <li><a href="mailto:acerolavr@gmail.com" class="email" target="_blank"><i class="fas fa-envelope"></i></a></li>
</ul>

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}