---
layout: links
# multilingual page pair id, this must pair with translations of this page. (This name must be unique)
lng_pair: id_links

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
    header: "Funding"
    info: "  "

  # To change order of the Categories, simply change order. (you don't need to change list order.)
  category:
    - title: "Awards"
      type: id_awards
      color: "gray"
    - title: "Fellowships"
      type: id_fellowships
      color: "#F4A273"
    - title: "Assistantships"
      type: id_assistantship
      color: "red"


  list:
    -

    # Awards
    - type: id_fellowships
      title: "LLNL DSC Fellowship"
      url: "https://data-science.llnl.gov/dsc"
      info: "July-2023: Lawrence Livermore National Laboratory Data Science Challenge Grad Fellowship"

    # Fellowships
    - type: id_awards
      title: "UCM GSA Travel Award"
      url: "https://gsa.ucmerced.edu/funding/travel-awards"
      info: "December 2023: Graduate Student Association (GSA) Travel Award Fellowship, University of California, Merced (UCM)"

    - type: id_fellowships
      title: "UCM GSOP Fellowship"
      url: "https://graduatedivision.ucmerced.edu/financial-support/internal-fellowships/graduate-student-opportunity-program"
      info: "May 2022: Graduate Student Opportunity Program Fellowship, University of California, Merced (UCM)" 

    - type: id_awards
      title: "UCM AM Internship Recognition Award"
      url: " "
      info: "May 2022: Applied Mathematics Internship Recognition Award, University of California, Merced (UCM)"

    - type: id_awards
      title: "UCM AM Certificate of Video Instruction Award"
      url: " "
      info: "June 2022: Applied Mathematics Certificate of Video Instruction Award, University of California, Merced (UCM)"

    - type: id_assistantship
      title: "UCM 5 Years RA/TA Assistantship"
      url: " "
      info: "February 2021: Research and teaching assistantship during Ph.D., University of California, Merced (UCM)"

    - type: id_assistantship
      title: "IBRO isiCNI Assistantship"
      url: "https://imbizo.africa/archive/2018/"
      info: "January 2018: IBRO-Simons Computational Neuroscience Imbizo Summer School, travel, accommodation and financial assistantship"  

    - type: id_fellowships
      title: "SFB 874 Fellowship"
      url: "https://www.sfb874.ruhr-uni-bochum.de/en/frontpage/"
      info: "October 2017: International Student Fellowship - SFB 874, Ruhr University Bochum, October 2016, NRW, Germnay"  

    - type: id_assistantship
      title: "CAMS Assistantship"
      url: "https://imbizo.africa/archive/2018/"
      info: "January 2016: The Center for Advanced Mathematical Sciences (CAMS) Financial Assistantship, Computational Neuroscience by the Mediterranean Winter School, January 2016, AUB, Lebanon"  


---














