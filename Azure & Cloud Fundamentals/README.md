# Azure & Cloud Fundamentals

# Lucas’s Blog Based on Wordpress

## 1. Introduction
In fact, I had the idea to create a blog from a very early age, but its purpose was not to record my life, nor to make a profit by owning a website. My original intention was to make the blog a storage place of some technology stuff, like coding, because my memory is really bad.. From this perspective, my ideal blog is more about recording my own technical practice than personal life. Because of this, when I learned about cloud notes products like notion, I did not hesitate to choose cloud notes instead of personal blogs, because my original intention was to remind myself of forgetfulness, not to share on the Internet For everyone to study together.

This time, the non-tech branch of MSA needs to build a Wordpress blog. I have to say that it still evokes the mood in my heart a long time ago. Therefore I hope to take this opportunity to transplant some of the technical cloud notes I have recorded to my blog, and let the Internet witness my growth.

Blog Link: http://cucumber-wordpress.azurewebsites.net/

## 2. Current Issues and solutions

### 2.1 SEO

Issue:Not being searched by search engine.

Related Reason:SEO is becoming more and more inclined to user intent, rather than simply doing keyword optimization. With the iterative update of the major search engine algorithms, more and more websites are punished for keyword stuffing but low content quality. If you want to get a better search engine ranking, the most effective way to achieve this goal is to target the keywords users search for, to solve specific problems in specific fields, and build valuable, high-quality keywords around these keywords content.

Unfortunately, search engine optimization is much more than finding keywords and generating content. You need to make sure that search engines can index and crawl your site, use titles and descriptions optimized for search engine search results, use key keywords and related keywords correctly, optimize your site performance, and more.

Solution: Using SEO plugin to improve search engine rankings.

### 2.2 Site Speed

Issue:Guess what to do if the website is accessed slowly? No one visits it. Loneliness spread, and soon, no one remembered the name of the site. It will not show up in a good search engine ranking position. It's a bit dramatic, but this is true. Slow websites will not be loved. Therefore, you need to find a way to optimize your WordPress website. The easiest way is through the cache plugin.

Related reason:First, the visitor ’s browser contacts your web server to obtain data about your website. Your visitors can access your website from anywhere. It may be one mile away from your web server or halfway away from the web server. Secondly, your WordPress will contact the website database where the website is installed. Third, the database compiles the data, converts it to an HTML page, and then sends it back to the user. Each time the user refreshes the page, the entire process repeats itself. Your user's browser requests all images again, and whenever he visits your website, the data in the MySQL database will be recalled. If your visitor ’s browser stores the image on their local hard drive and WordPress saves the data obtained from the database to you to make any changes, what would you think? This is exactly what WordPress caching does. Caching is the process of recovering the acquired data to speed up the WordPress website. Caching can minimize the number of data transfers between the visitor and the database. It reduces the number of requests and ultimately reduces the website load time.

Solution: The easiest way is through the cache plugin.

### 2.3 User Behavior Analysis

Issue:Not knowing the details of website visitors

Related reason:Website analytics can help you get detailed information about your website visitors. Here are some things you can learn from website analysis:

1. The number of visitors to your website.
2. Which sources will send you traffic. For example, search engines, social media, advertising or referral links.
3. What is your most popular webpage?
4. The actions that users perform on your website.

Solution:An excellent WordPress analysis solution can easily present all these data understanding reports. This enables you to make informed decisions about your website, which can ultimately help you get more traffic, customers and sales.

## 3. Plugin Comparison and Implementation

### 3.1 SEO

#### 3.1.1 Yoast SEO

Yoast SEO is one of the top two SEO plugins available for WordPress. Another plugin is called All-in-One SEO. Yoast has been downloaded more than 40 million times and is being used by more than 7 million websites. It has a free version and a premium version, and currently the free version has a 4.9 star rating (out of 5 stars). This rating was generated by more than 20,000 reviews.

Yoast was created by Joost de Valk in 2010. Prior to developing the WordPress SEO plugin, Joost accumulated extensive experience in IT and coding, and served as an SEO consultant for many years. Today, it is supported by a team of developers, designers, and marketers, and even sponsored WordCamps (WordPress Conventions) as a way to give back to the community.

The free version has following key features:

1. XML site maps – XML site maps are not necessarily necessary for SEO, but they can help search engines find the most important pages on your site. Usually, search engines will find the most important pages through internal links on your website, and you are responsible for the internal link structure. The site map makes this process much simpler, and Yoast can generate a site map for you.
2. Title tags and meta descriptions-Which elements of the website do the titles and page excerpts in the search results correspond to? The essence is the title tag and meta description of your website page. Yoast allows you to set title tags and meta descriptions for articles to change how they are displayed in search engines. These are different from the titles and excerpts you see on the article page.
3. Snippet preview – When you edit the title tag and meta description of an article, Yoast displays a snippet preview, allowing you to view the article ’s display in the search engine.
4. SEO analysis — It is difficult to understand whether the main keywords are used correctly. Fortunately, Yoast comes with an SEO analyzer, which allows you to enter keywords and let the tool analyze your content to rate it.
5. Content Analysis-Marked as "Readability" in Yoast, this tool analyzes your content to determine the difficulty of reading. Readability is not a direct ranking factor, but it can help reduce the bounce rate of your website and increase the length of visitors ’visits. If too many visitors find your content difficult to read, they will leave, which indirectly tells the search engine that your content is problematic. However, the debate about whether readability needs to be optimized remains.
6. Internal link analysis-your internal link structure can help you direct Google's crawler program to content that you want to rank higher than others. Yoast comes with an analysis tool that can help you optimize the internal link structure.
7. Cornerstone Content Label-Cornerstone Content Label is a dormant but growing SEO strategy. Basically, you will find three to five keywords that you want to rank the entire website, and build a long format (10000 words) page for them. This strategy relies on a strong internal link structure to help optimize the ranking of these keywords on your website by attracting search engine crawlers to visit cornerstone content pages. Yoast allows you to mark specific content as basic content and helps you optimize the internal link structure accordingly.
8. Integrate Google Webmaster Tools -404 pages and other errors to reduce Google's crawling frequency of your website. Google webmaster tools help you quickly understand search engine crawler access errors and fix them when they occur.
9. Permission control – Content and SEO analysis tools are useful for blogs, but you may not want your authors to be able to edit Yoast SEO ’s entire site settings. This function can control the permissions of the plug-in.

Compared with the All-in-One SEO, the free version of Yoast is rich enough for a novice webmaster. So I chose the Yoast SEO plugin to improve the search engine ranking for my blog.

#### 3.1.2 Yoast SEO Implementation
First search for seo yoast in the background of the plug-in, you can find the plug-in, click install to install online, and then click activate to activate it.
![Yoast SEO](https://raw.githubusercontent.com/ripenedcat/msa-machinelearning/master/Azure%20%26%20Cloud%20Fundamentals/png/1.png)
##### 3.1.2.1 General Submenu
###### a) Dashboard
Enter seo on the left panel, we can see some tips on the Dashboard page, including he will suggest you to check the configuration of your website seo,

###### b) Features
Click on features and find that many functions have been enabled by default, including SEO analysis, Readability analysis, Cornerstone content, Text link counter, XML sitemaps, Ryte integration, Admin bar menu, Security: no advanced settings for authors, REST API: Head endpoint. sitemap is important,
A Sitemap is a list of pages on your website. Creating and submitting a Sitemap helps Baidu discover and understand all the pages on your website. You can also use Sitemap to provide other information about your site, such as the date of the last update, the frequency of updates to the Sitemap file, etc., for the search engine Spider to refer to.
Using yoast ’s sitemap, the link is fixed, which is the domain name `/` sitemap_index.xml
The xml sitemap that comes with Yoast seo is very convenient to use. The first advantage is automatic update. As long as you add a website page, it will be automatically linked to the site map, so you do n’t need to generate it yourself; As long as you turn on the xml sitemap function, a link to the sitemap can be automatically generated and can be used directly, which is very convenient.
###### c) Webmaster tools
You can verify the webmaster tools of the four search engines Baidu, Google, Bing and yandex here. Just click the link below each box to get the verification code, fill in the box and save it.

![](https://github.com/ripenedcat/msa-machinelearning/raw/master/Azure%20%26%20Cloud%20Fundamentals/png/2.png)

##### 3.1.2.2 Search appearance Submenu
###### a) General
Title seperator is the title separator, you only need to choose one of `-` and `|`, these two are the most common.
Knowledge graph and `schema.org` Set the properties of the website. If your website is an enterprise website, then choose orgnization here. Then you need to fill in the company name and upload the company's logo. If your website is a personal blog, then choose personal.

![](https://github.com/ripenedcat/msa-machinelearning/raw/master/Azure%20%26%20Cloud%20Fundamentals/png/3.png)
###### b) Content type
Here are some settings for various types of content pages on your website, such as post, page, portfolio, etc.

Show Posts in search results? This setting has two meanings. The first is whether it is included in the search engine, and the second is whether it is displayed in the sitemap.

If you choose Yes, it is both included in the search engine and displayed in the sitemap.

Date in Snippet Preview Here is to choose whether or not to display the date of the web page update in the search results. For sites with many page updates, it is recommended to open it better.

Yoast SEO Meta Box This is to choose whether to display the SEO setting area in the background of the web page, it is recommended to display

SEO titile Set the format of the title of this page, just keep the default

Meta description Set the description format of this page, just keep the default
###### c) Media
Choose yes here, then click save changes to save

![](https://github.com/ripenedcat/msa-machinelearning/raw/master/Azure%20%26%20Cloud%20Fundamentals/png/4.png)
###### d) Taxonomies
This is where you can set up various types of categories for your website. Similarly, there are many different types of categories displayed. same, 
Let's use Categories as an example

Show Categories in search results?

This setting has two meanings. The first is whether it is included by the search engine, and the second is whether it is displayed in the sitemap.

If you choose Yes, it is both included in the search engine and displayed in the sitemap.

SEO titile Set the format of the title of this category page, keep the default, if you want to modify, just remove the archive and page

Meta description Set the description format of this category page, just keep the default

Yoast SEO Meta Box This is to choose whether to display the SEO setting area in the background of the web page, it is recommended to display

After everything is set, click save changes to save.

![](https://github.com/ripenedcat/msa-machinelearning/raw/master/Azure%20%26%20Cloud%20Fundamentals/png/5.png)
###### e) Archive
The content in this menu is similar to the previous settings

Author archives settings and Date archives settings are not included

Special pages can be kept by default
###### f) Breadcrumbs
I suggest not to use his breadcrumb navigation function, because it may conflict with the breadcrumb navigation of the theme you use.
###### g) RSS
Just keep the default here
##### 3.1.2.3 Social Submenu
###### a) accounts
First of all, when you set up your website as a personal website in the front, it will not be displayed here. It will only be displayed here when you choose to be an organization.

![](https://github.com/ripenedcat/msa-machinelearning/raw/master/Azure%20%26%20Cloud%20Fundamentals/png/6.png)
###### b) Facebook
Here is the link, title and description shown above and what the representative picture is when set to your website and shared by the social platform Facebook

You can set and select according to the following prompt box.

Fill in the facebook account. Pictures are generally chosen logo

Then click save changes
###### c)Twitter
Add Twitter card meta data keep default enabled here

The default card type to use select Summary with large Image.

Then click save changes
###### d) Pinterest
I don’t use Pinterest, so don’t worry about it here.

##### 3.1.2.4 Tools Submenu
![](https://github.com/ripenedcat/msa-machinelearning/raw/master/Azure%20%26%20Cloud%20Fundamentals/png/7.png)
###### a) Import and export
You can export the seo settings of your existing website here, or you can import the seo settings of other websites
###### b) Bulk editor
You can batch edit the title and description of all your pages here.

![](https://github.com/ripenedcat/msa-machinelearning/raw/master/Azure%20%26%20Cloud%20Fundamentals/png/8.png)
###### c) Text link counter
Click once, he will calculate all the links in all your articles once, so that it is convenient for you to make a SEO setting, and the result of this calculation will also be displayed on the summary page menu of each page

#### 3.1.3 Benifits after implementing Yoast SEO
It improves the ranking of my website in search engines, thereby increasing the number of website visits, and ultimately improving the website’s sales or promotion skills
### 3.2 Cache Management

The two major contenders for the best WordPress cache plugin are:

1. W3 Total Cache: A feature-heavy solution, featuring a huge array of settings for meticulously configuring your site’s caching.
2. WP Super Cache: A more simplified but no less powerful option, which is well-suited to high-traffic websites.

#### 3.2.1 Introduction to WP Super Cache 

WP Super Cache was created by Automattic, the company behind WordPress. It lets you generate static HTML files that your web server can display to your website’s visitors. This is a far quicker alternative to processing WordPress PHP scripts, which can be costly as well as time consuming.

WP Super Cache has three methods for serving cached files. ‘Expert’, the fastest method, can help ensure that your site performs well under pressure from heavy traffic (making it useful for scalability). The ‘Simple’ method isn’t quite as fast, but enables files to be served with sections that remain dynamic. The last method, ‘WP-Cache caching’, caters to logged-in users. It ensures that they receive reliable performance when performing actions on your site.

Since WP Super Cache is simple, relatively lightweight, and easy to configure, it’s a good fit for those who are relatively new to WordPress. It can also sync with your Content Delivery Network (CDN), which means you can further boost your site’s speed.

#### 3.2.2 Introduction to W3 Total Cache

Just like WP Super Cache, W3 Total Cache can smoothly integrate with your CDN. However, it also saves bandwidth by minifying and compressing your site’s files. In fact, this plugin’s versatile compression and rendering settings can improve overall speed and performance by 10x. It also contains features to significantly lessen download times on your site, further enhancing the user experience in the process.

W3 Total Cache differs from WP Super Cache in that it is web host agnostic. This means it can serve as a reliable caching solution, regardless of your hosting provider. By comparison, WP Super Cache functions better on low-powered servers.

Due to its multiple settings for minimizing JavaScript and Custom Style Sheet (CSS) files, as well as its object caching capabilities, W3 Total Cache is better suited to more advanced users. It’s also a good fit if you’re developing a WordPress site that is largely targeting a mobile user demographic, as it supports caching for Accelerated Mobile Pages (AMP).

I would not write too much here about the detailed comparison between the two cache management tools. Finally I chose to use WP Super Cache due to its lightweight, simple, reliable, and free caching solution. Detailed comparison can be found [here](https://www.hostinger.com/tutorials/wp-super-cache-vs-w3-total-cache).

#### 3.2.3 WP Super Cache Implementation
![](https://github.com/ripenedcat/msa-machinelearning/raw/master/Azure%20%26%20Cloud%20Fundamentals/png/9.png)
##### 3.1 Easy tab
First go to the general tab and turn on the cache function.

##### 3.2 Advanced Tab
My personal setting method is shown below. The basic method is to open all the options recommended by the system, and set the cache refresh to once a day to improve access speed.

![](https://github.com/ripenedcat/msa-machinelearning/raw/master/Azure%20%26%20Cloud%20Fundamentals/png/10.png)
![](https://github.com/ripenedcat/msa-machinelearning/raw/master/Azure%20%26%20Cloud%20Fundamentals/png/11.png)
![](https://github.com/ripenedcat/msa-machinelearning/raw/master/Azure%20%26%20Cloud%20Fundamentals/png/12.png)


By default, cache is based on the user access driver, and the pre-cache makes the user have not yet accessed, you can first generate a cache file. The pre-cache page operates as follows, select 0 minutes, that is, do not refresh the pre-cache file. If there are too many blog posts, frequent refreshes will affect system performance. In particular, web hosting is not recommended.

![](https://github.com/ripenedcat/msa-machinelearning/raw/master/Azure%20%26%20Cloud%20Fundamentals/png/13.png)

It is not recommended to configure the CDN interface, but if your website server is located in a remote place, such as China, it is best to configure the local CDN to increase the speed of world access, such as Alibaba Cloud.
Other settings basically do not need to be changed, so I won't repeat them one by one here.

#### 3.2.4 Benifits after implementing WP Super Cache
WP Super Cache generates static HTML files for my WordPress site. When a visitor visits a certain page of the website, the server can directly display the pre-cached HTML page to him, without the need to spend time and effort to run PHP to generate the HTML file instantly, which not only speeds up the page access speed, but also reduces the server CPU usage.

The acceleration of page access speed not only helps to improve the user experience, but also helps to improve the SEO ranking of the website.

### 3.3 Analytics plugin

#### 3.3.1 Introduction to MonsterInsight

Is there a reason not to use Google Analytics? MonsterInsight is such a plugin that integrates Google Analytics. Before we delve into the Google Analytics installation process, we need to take a moment to study why it is recommended to use the MonsterInsights plugin instead of manually analyzing the installation.

Although manually installing Google Analytics allows you to collect basic traffic statistics such as sessions, pageviews, bounce rate, etc., the disadvantage is that it cannot fully utilize the full potential of Google Analytics. For example, if you need to use more Google Analytics tracking features such as download tracking, link tracking, form tracking, e-commerce, tracking, etc., you must manually customize the code for each instance. There is no doubt that if you are not a developer or an analysis expert, this may be tedious. It ’s possible that even a slight error can distort the entire Google Analytics tracking, which means that the data you get from your Google Analytics account is incorrect, which can lead you to make the wrong decision for your business.

On the other hand, MonsterInsights can easily install Google Analytics with just a few clicks. MonsterInsights is the most popular WordPress Google Analytics plugin in existence. To enable enhanced tracking, you only need a few clicks or install the appropriate plugin. Since you never need to touch any line of code, you can save your precious time during the entire installation process.

#### 3.3.2 MonsterInsight Installation
##### a) Creating Google Analytics account
1. Click here to go to Google Analytics.
2. Click Create an account.
3. Once you have signed in to your Google account, click Access Google Analytics.
##### b) Link your Google Analytics account to MonsterInsight
Complete the login and binding of Google Analytics account according to the Monster Insight page prompt. Since I have completed this part, there is no picture guide.

##### c) Look at your website overview
You can see your website data of sessions, pageviews, average session duration and bounce rate.

![](https://github.com/ripenedcat/msa-machinelearning/raw/master/Azure%20%26%20Cloud%20Fundamentals/png/21.png)
![](https://github.com/ripenedcat/msa-machinelearning/raw/master/Azure%20%26%20Cloud%20Fundamentals/png/22.png)

#### 3.3.3 Benifits after implementing MonsterInsight
Help me better understand users' Insight, and then continue to improve and strengthen the operation of my website.

## 4. Other Plugin installed

**Akismet Anti-Spam**<br>
Akismet is a comment spam filtering service. Akismet catches blog comment and pingback spam using their algorithms. This algorithm learns from its mistakes and from the actions taken by participating websites.On popular websites, the amount of spam comments could get as high as 85%. This means out of every 100 comments only 15 are legitimate. Comment moderation is a time consuming task, and Akismet can save you hours. Akismet will catch spam comments before it lands in your moderation queue as pending. This allows you to focus your energy on moderating comments by real users.

**Updraft Plus**<br>
![](https://github.com/ripenedcat/msa-machinelearning/raw/master/Azure%20%26%20Cloud%20Fundamentals/png/15.png)
The webmaster ’s greatest fear is that the website crashes, and the server can be restarted again. The most troublesome thing is that even the data is lost together. This is why the ransomware virus is so terrible before, because he does not damage your computer, but all the computer ’s data. Hold up, and Updraft Plus is a plug-in tool that can back up the entire website data, whether it is Theme, plugin, uploaded data, database, etc., as long as there is a problem with the website, one-click restore, In addition, Updraft Plus also provides a schedule Backup, you can also store backup data to various cloud spaces, it is really a very professional backup tool!

**WP Editor.md**<br>
How could a blog be without markdown? WP Editor.md allows you to use markdown at each posts.

## 5. Theme

My site is using the kratos-pjax theme. It's a really beautiful theme, thanks for the author! I've done several modifications. Please enjoy!

[Theme github](https://github.com/xb2016/kratos-pjax)
