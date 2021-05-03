---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "How to Update a ThemeForest Theme with the Envato WordPress Toolkit"
url: "/update-themeforest-themes-envato-wordpress-toolkit"
subtitle: "How to install and manage the Envato WordPress Toolkit"
summary: "How to install and manage the Envato WordPress Toolkit"
authors: [ luiscachog ]
tags: [ Wordpress ]
categories: [ SysAdmin , Wordpress ]
keywords: [ ThemeForest, Themes, Wordpress, Envato]
date: 2014-11-10
publishDate: 2014-11-10
lastmod: 2021-05-02
featured: true
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

I've purchased some themes on ThemeForest.com because they're great. So this time I want to write about "How to Update ThemeForest Themes with the Envato WordPress Toolkit".

First of all, Envato WordPress Toolkit it is very similar to a WordPress plugin.
The installation it is the only difference. So I will explain how install the "plugin" and how to use in order to get the last update from your theme.

1. Envato WordPress Toolkit is NOT available on WordPress Repositories, so you will to download from Github. [https://github.com/envato/envato-wordpress-toolkit](https://github.com/envato/envato-wordpress-toolkit)

1. After you download the .ZIP file, you should be able to install from the WordPress Plugin Manager. Or you could upload the **envato-wordpress-toolkit** folder to the `/wp-content/plugins/` directory.

1. Activate the Plugin from the WordPress Plugin Manager.

1. You will need to generate an API key from your Themeforest account.

    1. In order to get your API key from Themeforest, you should login to themeforest.com, go to your dashboard and click on **My Settings** The API Keys screen allows you to generate a free API key.

    {{< figure src="posts/update-themeforest-themes-envato-wordpress-toolkit/generate-api-key.png" caption="Generate Envato API Key" id="envato-api-key" theme="ligth">}}

1. Once the API connection has been established you will see a list of themes that can be auto installed.
  If you don't see any themes and are certain you've done everything correct, there is a good chance the theme author has not updated their theme to be available for auto install and update.
  If that's the case, please contact the theme author and ask them to update their theme's information.

    {{< figure src="posts/update-themeforest-themes-envato-wordpress-toolkit/theme-autoupdate.png" caption="Envato Theme Autoupdate" id="envato-theme-autoupdate" theme="ligth">}}

This "plugin" very helpful to get your themes updated. I hope works for you as well as with me.
