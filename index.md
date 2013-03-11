---
layout: page
title: About Me
tagline: 
---
{% include JB/setup %}

## Personal Information

### Yu Jiongyu
>#### Mobile  `18680584004`
>#### E-Mail  ![Email](http://services.nexodyne.com/email/icon/EgKqVgkYtA%3D%3D/jpSw7ZI%3D/R01haWw%3D/0/image.png)
>#### Github @ [twonly](http://www.github.com/github "Github Link")  
>#### Douban @ [xiaowuyi](http://www.douban.com/people/xiaowuyi/ "Douban Link")  
>#### Weibo @ [twonly](http://www.weibo.com/twonly "Weibo Link")

The theme should reference these variables whenever needed.
    
- - -

## Education Background
>#### 2008.9 - 2012.6  SYSU         Network Engineering
>#### 2011.2 - 2011.7  NSYSU@Taiwan Information Engineering
>#### 2011.2 - 2011.7  SYSU         Computer Science

This blog contains sample posts which help stage pages and blog data.
When you don't need the samples anymore just delete the `_posts/core-samples` folder.

    $ rm -rf _posts/core-samples

Here's a sample "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## To-Do

This theme is still unfinished. If you'd like to be added as a contributor, [please fork](http://github.com/plusjade/jekyll-bootstrap)!
We need to clean up the themes, make theme usage guides with theme-specific markup examples.


