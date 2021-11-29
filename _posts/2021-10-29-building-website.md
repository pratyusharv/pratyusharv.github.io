---
title: 'How I Built my Website'
date: 2021-10-29
permalink: /posts/building-website/
tags:
  - coding
  - personal website
---


Personal websites are a [must-have](https://theacademicdesigner.com/2019/personal-academic-website-benefits/) for academics. Personal websites serve as an extended resume; every facet of your academic pursuits are clearly documented. If you're a junior scholar, having your own page on the internet is even more crucial. Personal pages liberate you from having to depend on your institute. Your website will stay intact even after you shift to a new faculty, and you don't have to deal with the IT department.
<br />
<br />
There are countless free options for building your own website with minimal effort. For example, [Wix](https://www.wix.com/) and [Wordpress](https://wordpress.com/). However, their ease-of-use is offset by their freemium model. Visitors to your website are hounded by ads, and there are privacy issues as well. 

## Why I chose GitHub: 
I went ahead with GitHub mainly because it is not intrusive like the freemium sites mentioned above. You get a clean looking URL, flexibility and you can brush up your coding skills in the process. And hosting on Github also allows you to have granular control over your website. In the end, you get a beautiful, minimal and an easy to maintain website, all with minimum effort. 

## Steps:
In this tutorial, I assume you're familiar with the very basics of coding and Github jargon like _repository_, _forking_, _cloning_ etc. If you have zero idea about Github, go this [post](https://jayrobwilliams.com/posts/2020/06/academic-website/).

### Setting Up:

1. ### Create a Github Account:
    The very first step is to create a GitHub profile (if you don't already have one). When creating, extra attention must be paid to your username, since your
    website's URL will be **yourusername.github.io**. 

2. ### Adding the Template to your GitHub:
    The template I've used is [Academic Pages](https://academicpages.github.io/). You have to **fork** the template repo in order to add it to your profile for modification. Go to this [link](https://github.com/academicpages/academicpages.github.io) and click on the fork button on the top right. 

    | ![fork](/images/posts/building/fork.png) |
    |:--:| 
    | _Click on the highlighted button_ |

3. ### Changing the Repo Name:
    After the template has been forked into your account, the repo will now read **yourusername/academicpages.github.io**. To make your website show up, you have to change the repo's name. To change the name, first go to **Settings**.
    
    | ![settings](/images/posts/building/settings.png) |
    |:--:|
    | _This will take you to the Settings_ |

    The name option will show up right in front. Change the name of the repo to **yourusername.github.io**.
    
    | ![name](/images/posts/building/name.png) |
    |:--:|
    | _Edit the text box_ |

4. ### Going Live:
    After changing your name, open **Settings** again. However, this time, go to the **Pages** section.
    
    | ![pages](/images/posts/building/pages.png) |
    |:---:|
    | _Open the drop-down menu_ |

    Change **Branch** to **Master** and leave the folder option as **root**. Then click save. You should see a prompt informing you that your site has been successfully published.   
    Now, to view the site, go to **https://yourusername.github.io**.   
    You can now see the template hosted in your repo.

### Customizing:
4. ### Cofiguration File:
    The configuration file _\_config.yml_ contains all the basic details about your wesbite. It is present in the root directory of your repo. Open it and start editing it. 
    
    | ![config](/images/posts/building/config.png) |
    |:---:|
    | _Click on the Pencil button to edit_ |

    You should edit the following options:
    - Locale
    - Title
    - Name
    - Description
    - URL (Should be edited to **https://yourusername.github.io**)
    - Repository (Change to ****yourusername/yourusername.github.io**)
    - Under Site Author:
        - Name
        - Bio
        - Location 

    In addition to all these, you can also add your social media profiles, and a profile picture. To add your profile picture, upload a photo named **profile.png** to the **images** folder in the root directory.   
    Commit the file and open your website to see the new edits. 

5. ### Editing the Header:
    The Header contains the navigation links to various sections of your website. If you want to change it, go to the **_data** folder in your root directory and open **navigation.yml** file.   
    Comment out the sections you do not want. 


## Further Editing:
Now that your rudimentary website is up and running, you can customise it further to your wishes. Add your CV, write some blog posts, update your portfolio and publications. You can create entirely new sections as well. The template is infinitely flexible. If you commit some changes you do not like, you can always revert back. Check out another [post](https://jayrobwilliams.com/posts/2020/07/customizing-website/) by Jay Rob Williams to make your website look more fancy. You can also contact me anytime with your queries. I'd be more than happy to help!
