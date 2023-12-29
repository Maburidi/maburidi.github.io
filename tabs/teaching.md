---
layout: teaching
# multilingual page pair id, this must pair with translations of this page. (This name must be unique)
lng_pair: id_teaching

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
#published: false


# you can always move this content to _data/content/ folder
# just create new file at _data/content/links/[language].yml and move content below.
###########################################################
#                Links Page Data
###########################################################
page_data:
  main:
    header: "Teaching"
    info: "  "

  # To change order of the Categories, simply change order. (you don't need to change list order.)
  category:
    - title: "2023" 
      type: id_2023
      color: "#FFD700"
    - title: "2022"
      type: id_2022 
      color: "gray"
    - title: "2021" 
      type: id_2021
      color: "#FA8072"
    - title: "2020" 
      type: id_2020
      color: "#E6E6FA"


  list:
    -

    # Awards

    - type: id_2023            
      title: "Spring: MATH-131"                   
      url: "https://catalog.ucmerced.edu/preview_course_nopop.php?catoid=20&coid=48564"      
      info: "Numerical Methods for Scientists and Engineers, Applied Math Department, University of California, Merced"
    - type: id_2022            
      title: "Fall: MATH-131"                   
      url: "https://catalog.ucmerced.edu/preview_course_nopop.php?catoid=20&coid=48564"      
      info: "Numerical Methods for Scientists and Engineers, Applied Math Department, University of California, Merced"
    - type: id_2022            
      title: "Spring: MATH-131"                   
      url: "https://catalog.ucmerced.edu/preview_course_nopop.php?catoid=20&coid=48564"      
      info: "Numerical Methods for Scientists and Engineers, Applied Math Department, University of California, Merced"
    - type: id_2021            
      title: "Fall: MATH-022"                   
      url: "https://catalog.ucmerced.edu/preview_course_nopop.php?catoid=16&coid=39688"       
      info: "Calculus II for Scientists and Engineers, Applied Math Department, University of California, Merced"

    - type: id_2021            
      title: "Spring: CS-10671101"                    
      url: "https://catalog.ucmerced.edu/preview_course_nopop.php?catoid=16&coid=39688"       
      info: "Principles of Programming I, Computer Science Department An-Najah National University"
    - type: id_2020           
      title: "Fall: CS-11000127"                    
      url: "https://catalog.ucmerced.edu/preview_course_nopop.php?catoid=16&coid=39688"       
      info: "Introduction to Computer Science, Computer Science Department An-Najah National University"



---
