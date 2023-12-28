---
layout: projects
# multilingual page pair id, this must pair with translations of this page. (This name must be unique)
lng_pair: id_projects

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
image_viewer_on: true
# please use the "image_lazy_loader_on" below to enable image lazy loader for individual pages or posts (_posts/ or [language]/_posts folders).
# image lazy loader can be enabled or disabled for all posts using the "image_lazy_loader_posts: true" setting in _data/conf/main.yml.
image_lazy_loader_on: true
# exclude from on site search
#on_site_search_exclude: true
# exclude from search engines
#search_engine_exclude: true
# to disable this page, simply set published: false or delete this file
#published: false

page_data:
  main:
    header: "Research Projects"
    info: "Knowledge does not come, but you have to go to it"
    text_color: "white"
    # if you don't want to use background image, comment it. back_color will be activated.
    img: ":rp.jpg"
    back_color: "lightblue"

  category:
    - title: "Current"
      type: id_current
      color: "gray"
    - title: "Accomplished"
      type: id_accomplished
      color: "#62b462"
    - title: "Internship"
      type: id_internship
      color: "#2FD0ED"

  list:
    ## example
    #- type: id_example
    #  project_name: "Example Project"
    #  project_excerpt: "Examples"
    #  img: ":project1_thumb.jpg"
    #  img_title: "img title1"
    #  date: "2021-03-13"
    #  post: |
    #    # Examples

    #    Helo there! 


    ## picture
    #- type: id_picture
    #  project_name: "Example Project"
    #  project_excerpt: "Picture"
    #  img: ":project2_thumb.jpg"
    #  img_title: "img title2"
    #  date: "2021-04-23"
    #  post: |
    #    # Title
    #    This is project content.
    #
    #    ![Image](:project2_thumb.jpg)

    # quote
    - type: id_current
      project_name: "Combinatorial Optimization with Graph Neural Networks (GNNs)"
      project_excerpt: "Mohammed Aburidi and Roummel Marcia"
      img: ":p1.jpg"
      #img_title: "img title3"
      date: "2023-10-27"
      post: |
        l.
        
    - type: id_current
      project_name: "Wasserstein distance-Based GNN for Drug-Drug Interaction Prediction"  
      project_excerpt: "Mohammed Aburidi and Roummel Marcia"                      
      img: ":p2.jpg"
      #img_title: "img title3"
      date: "2023-09-20"
      post: |
        l.

    - type: id_current
      project_name: "Drug-Drug Interaction Prediction via Matrix Factorization"   
      project_excerpt: "Mohammed Aburidi and Roummel Marcia"                      
      img: ":p3.jpg"
      #img_title: "img title3"
      date: "2023-12-15"
      post: |
        L.
        
    - type: id_accomplished
      project_name: "Optimal Transport-Based Network Alignment: Graph Classification of Small Molecule Structure-Activity Relationships in Biology"   
      project_excerpt: "Mohammed Aburidi and Roummel Marcia"                      
      img: ":p4.jpg"
      #img_title: "img title3"
      date: "2023-08-15"
      post: |
        L.

    - type: id_accomplished
      project_name: "Optimal Transport and Contrastive-Based Clustering for Annotation-Free Tissue Analysis in Histopathology Images"   
      project_excerpt: "Mohammed Aburidi and Roummel Marcia"                      
      img: ":p5.jpg"
      #img_title: "img title3"
      date: "2023-06-10"
      post: |
        L.

    - type: id_accomplished
      project_name: "CLOT: Contrastive Learning-Driven and Optimal Transport-Based Training for Simultaneous Clustering"   
      project_excerpt: "Mohammed Aburidi and Roummel Marcia"                      
      img: ":p6.jpg"
      #img_title: "img title3"
      date: "2023-03-20"
      post: |
        L.

    - type: id_accomplished
      project_name: "Genetic Variant Detection Over Generations: Sparsity-Constrained Optimization Using Block-Coordinate Descent"   
      project_excerpt: "Mohammed Aburidi and Roummel Marcia"                      
      img: ":p7.jpg"
      #img_title: "img title3"
      date: "2022-09-10"
      post: |
        L.
    - type: id_accomplished
      project_name: "Rubost Detrended Fluctuation Analysis (DFA) and its application to envelopes of human alpha rhythms"   
      project_excerpt: "Mohammed Aburidi, Guido Nolte, Andreas K. Engel"                      
      img: ":p8.jpg"
      #img_title: "img title3"
      date: "2018-08-10" 
      post: |
        L.
        
    - type: id_internship 
      project_name: "Parallelized Ray-Based Framework Adaptive ReaL Time Analysis of Big Fusion Data"   
      project_excerpt: "Mohammed Aburidi, Laurie Stephey, Ralph Kube, Michael Churchill, Jong Choi"                      
      img: ":p8.jpg"
      #img_title: "img title3"
      date: "2018-08-10" 
      post: |
        L.



--- 
