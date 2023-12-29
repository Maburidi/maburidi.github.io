---
layout: home
# multilingual page pair id, this must pair with translations of this page. (This name must be unique)
lng_pair: id_home

# image for page specific usage
img: ":home-heading.jpg"
# publish date (used for seo)
# if not specified, site.time will be used.
#date: 2022-03-03 12:32:00 +0000

# for override items in _data/lang/[language].yml
#title: My title
#button_name: "My button"
# for override side_and_top_nav_buttons in _data/conf/main.yml
#icon: "fa fa-bath"

# seo
# if not specified, date will be used.
#meta_modify_date: 2022-03-03 12:32:00 +0000
# check the meta_common_description in _data/owner/[language].yml
#meta_description: ""

# optional
# please use the "image_viewer_on" below to enable image viewer for individual pages or posts (_posts/ or [language]/_posts folders).
# image viewer can be enabled or disabled for all posts using the "image_viewer_posts: true" setting in _data/conf/main.yml.
#image_viewer_on: true
# please use the "image_lazy_loader_on" below to enable image lazy loader for individual pages or posts (_posts/ or [language]/_posts folders).
# image lazy loader can be enabled or disabled for all posts using the "image_lazy_loader_posts: true" setting in _data/conf/main.yml.
#image_lazy_loader_on: true
# exclude from on site search
#on_site_search_exclude: true
# exclude from search engines
#search_engine_exclude: true
# to disable this page, simply set published: false or delete this file
# don't forget that this is root index.html. If you disable this, there will be no index.html page to open
#published: false

#{%- include util/auto-content-generator.liquid -%}
#{{ website_info_text_first }}

#{{ website_info_text_second }}

---

{%- comment -%} Please delete below and place your page content here {%- endcomment -%}


<!-- <h1 style="text-align: center;"> Mohammed J. Aburidi </h1>	
<h3 style="text-align: center;"> Ph.D. Candidate </h3>	--> 


<h5> Welcome to my personal website! </h5>     

<p> I'm Mohammed, a Ph.D. candidate at the University of California Merced (UCM), USA. My primary research interests lie in graph/geometric machine learning and optimization. Specifically, I employ Optimal Transport theory for metric learning and craft Graph Neural Network (GNNs)-based solvers for combinatorial optimization problems. <br>     

<p> I completed my master's degree in Applied Mathematics at UCM. Additionally, I hold another master's degree in Scientific Computing from An-Najah National University, along with a bachelor's degree in Physics. My interdisciplinary journey unfolds at the intersection of science and innovation. I apply my methods to unravel the intricacies of proteins, drugs, and small molecules, with the dual goal of expanding knowledge and revolutionizing practical applications. <br>      


<div style="height: 30px;"></div>


<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Education & Academic Affiliations</title>
</head>
<body>

  <h2 style="text-align: center; color: #FFD700; font-weight: bold;">Education & Academic Affiliations</h2>

  <div style="text-align: center;">
    <img src="../assets/img/home/ucm.png" alt="Your Image" style="max-width: 30%; height: auto;"/>
  </div>

</body>
</html>


<div style="height: 40px;"></div>




<html lang="en">  
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Home</title>
  <style>
    body {
      text-align: center;
    }

    h2 {
      color: #3366cc;
      font-weight: bold;
    }

    .image-container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 10px;
      margin-top: 10px;
    }

    img {
      max-width:30%;
      height:40px; /* Set the desired height */
      border-radius: 0px; /* Optional: Add rounded corners */
    }
  </style>
</head>
<body>

  <h2 style="text-align: center; color: #FFD700; font-weight: bold;">Prior Affiliations</h2>

  <div class="image-container">
    <img src="../assets/img/home/img1.jpg" alt="Image 1">
    <img src="../assets/img/home/img2.jpg" alt="Image 2">
    <img src="../assets/img/home/img3.jpg" alt="Image 3">
    <img src="../assets/img/home/img4.jpg" alt="Image 4">
    <img src="../assets/img/home/img5.jpg" alt="Image 5">
    <img src="../assets/img/home/img6.png" alt="Image 6">
  </div>

</body>
</html>













