---

layout: default

style: |


    #Cover h2 {
        margin:65px 0 0;
        font-size:70px;
        text-align: center;
        }
    #Cover h3 {
        margin-top: 30px;
        position: static;
        }
    #Cover p {
        margin:10px 0 0;
        text-align:center;
        font-style:italic;
        font-size:20px;
        }
    #Picture h2 {
        color:#FFF;
        }
    #SeeMore h2 {
        font-size:100px
        }
    #SeeMore img {
        width:0.72em;
        height:0.72em;
        }
    #live-demo h2,
    #live-demo .note,
    #welcome-together h2 {
        background-color: rgba(0,0,0,.7);
        color: #fff;
        display: inline-block;
        padding: 0.5em;
        }
    .highlight{
        color: red;
    }

    .shout.with-picture img {
        max-height: 60%;
        margin: 0 auto;
        display: block;
    }
    .shout.with-picture h2 {
        font-size: 120px;
        -webkit-transform: translateY(75%);
        -moz-transform: translateY(75%);
        transform: translateY(75%);
        }
    .shout.medium h2{
       font-size: 70px;
    }
    .shout.medium.with-picture h2 {
        -webkit-transform: translateY(175%);
        -moz-transform: translateY(175%);
        transform: translateY(175%);
        }

    .slide, .slide.shout {
        background: #fff url(pictures/logo-tint.png) no-repeat 95% 90%;
        background-size: 150px;
        }
    .slide h2, .slide h3 {
        color: #444;
        }
    .slide h3 {
        width: 100%;
        font-size: 150%;
        text-align: center;
        position: absolute;
        left: 0;
        bottom: 30%;
        }
    .slide.with-subtitle h2 {
        -webkit-transform: translateY(-85%);
        -moz-transform: translateY(-85%);
        transform: translateY(-85%);
    }
    .left{
        text-algin: left;
    }
    .footnote {
        font-size: 75%;
        position: absolute;
        bottom: 0;
        }
---

# Why Frontend should use Rails? {#Cover}

<h3>你所不知道的前端優勢</h3>



![](pictures/cover-roco.jpg)

## **Hi**

{:.shout.with-picture}
## xdite
![](pictures/xdite.png)

{:.shout.with-picture}
## Ruby on Rails
![](pictures/rails.jpg)

{:.cover}
## &nbsp;
![Fulltime Business Developer](pictures/fulltime.jpg)

{:.footnote.note}
Poster from movie ["Fulltime Killer"](http://www.imdb.com/media/rm2355469568/tt0286635)


## **兩個重點**

// 本場只有兩個重點：

{:.shout .medium .with-subtitle}
## Best Practicss for <br>Speeding Up Your Website

### 最佳實踐

## Asset Pipeline
{:.shout .medium}

## 在 JSDC 講 Rails ?
{:.shout .medium}

// 相信很多人對我挑這個題目來講，一定覺得很奇怪。

## 明明 node.js 比較快
{:.shout .medium}

## 速度比較表

<table style="border:1px #000000 solid; padding:2px; text-align:center;" width="90%">
    <tr>
        <td width="37%"> Web 框架 </td>
        <td width="35%"> 併發模型 </td>
        <td width="45%"> 531 req / s </td>
    </tr>

    <tr>
        <td> Rails  </td>
        <td> Multiple Process </td>
        <td> 531 req / s  </td>
    </tr>

    <tr>
        <td> Sinatra  </td>
        <td> Multiple Process </td>
        <td> 576 req / s  </td>
    </tr>

    <tr>
        <td> Sinatra::Synchrony </td>
        <td> Fibers </td>
        <td> 1692 req / s  </td>
    </tr>

    <tr>
        <td> Goliath </td>
        <td> Fibers </td>
        <td> 1924 req / s  </td>
    </tr>

    <tr>
        <td> Cramp </td>
        <td> Event IO  </td>
        <td> 3516 req / s  </td>
    </tr>
    <tr>
        <td> Node.js </td>
        <td> Event IO </td>
        <td class="highlight"> 3100 req / s </td>
    </tr>
</table>

## node.js 比 Rails 快了 <span class="highlight">6</span> 倍
{:.shout .medium}

## 那...
{:.shout .medium}

// 那...為什麼還要講這個題目？

## 現場調查
{:.shout}

## Best Practicss for <br>Speeding Up Your Website
{:.shout .medium}

## 速度比較表

<table style="border:1px #000000 solid; padding:2px; text-align:center;" width="90%">
    <tr>
        <td width="37%"> Web 框架 </td>
        <td width="35%"> 併發模型 </td>
        <td width="45%"> 531 req / s </td>
    </tr>

    <tr>
        <td> Rails  </td>
        <td> Multiple Process </td>
        <td> 531 req / s  </td>
    </tr>

    <tr>
        <td> Sinatra  </td>
        <td> Multiple Process </td>
        <td> 576 req / s  </td>
    </tr>

    <tr>
        <td> Sinatra::Synchrony </td>
        <td> Fibers </td>
        <td> 1692 req / s  </td>
    </tr>

    <tr>
        <td> Goliath </td>
        <td> Fibers </td>
        <td> 1924 req / s  </td>
    </tr>

    <tr>
        <td> Cramp </td>
        <td> Event IO  </td>
        <td> 3516 req / s  </td>
    </tr>
    <tr>
        <td> Node.js </td>
        <td> Event IO </td>
        <td class="highlight"> 3100 req / s </td>
    </tr>
</table>

## 這張表講的是 <br> <br>「網頁產生速度」
{:.shout .medium}

## 回到正題
{:.shout}

## Scaling Websites
{:.shout}

## Priciples

* Front-end speed
* SQL Query speed
* Method speed
* Programing Language speed


##  Front-end performance
{:.shout .medium}

##  7s -> 1s
{:.shout}

##  SQL Query Performance
{:.shout .medium}

##  500ms -> 50ms
{:.shout}

##  Method Performance
{:.shout .medium}

##  50ms -> 10ms
{:.shout}

##  Programming Language Performance
{:.shout .medium}

##  5ms -> 2ms
{:.shout}


##  Webpage 產生速度 = <br><br> SQL Query speed + <br> <br>Method speed + <br><br> Programing Language speed
{:.shout .medium .left}


## 比較語言和框架本身的速度沒什麼意義

* node.js V.S. Rails
* Rails V.S. Sinatra
* Rails V.S. PHP
* ....

{:.cover}
## 省下來的時間
![Frontend(7s - 1s ) > Backend( 550ms - 62ms)](pictures/time-save.jpg)

##  What can Rails do ?
{:.shout .medium}

## Speed Frontend Performance <span class="highlight">by default</span>
{:.shout .medium}

## Easy to imeplement parallel download

The `HTTP/1.1` specification suggests that browsers download **no more than 2 components** in parallel per hostname. If you serve your images from `multiple hostnames`, you can get more than two downloads to occur in parallel.


## Easy to imeplement parallel download

    config.action_controller.asset_host =
        "http://asset%d.example.com"


    <img src="http://asset1.example.org/demo4.jpg">
    <img src="http://asset2.example.org/demo3.jpg">
    <img src="http://asset3.example.org/demo2.jpg">
    <img src="http://asset4.example.org/demo1.jpg">

// 原本 1 條雙線道變成 4 條雙線道

## Easy to apply CDN

A content delivery network or `content distribution network (CDN)` is a large distributed system of servers deployed in multiple data centers across the Internet. The goal of a CDN is to serve content to end-users with **high availability and high performance**.

## Easy to imeplement parallel download

    config.action_controller.asset_host =
        "http://cdn%d.example.com"


    <img src="http://cdn1.example.org/demo4.jpg">
    <img src="http://cdn2.example.org/demo3.jpg">
    <img src="http://cdn3.example.org/demo2.jpg">
    <img src="http://cdn4.example.org/demo1.jpg">

## Easy to apply CDN

### based on asset **deploy TIMESTAMP**, auto **INVALID**


    <link href="/assets/application-1b7a795f9.css" type="text/css" />
    <link href="/assets/application-ca29aba87.css" type="text/css" />
    <link href="/assets/application-72ae3ec5b.css" type="text/css" />

## Easy to minimal HTTP Request

    //= require_self
    //= require common
    //= require comment
    //= require jquery.fullcalendar
    //= require advertisements

## Auto Compress

* Gzip
* Trim
* Uglify


## Auto CSS Sprite

    @import "icon/*.png";

    $icon-sprite-dimensions: true;
    @include all-icon-sprites;


## Auto ETag

`ETag` , is part of HTTP, the protocol for the World Wide Web. It is one of several mechanisms that HTTP provides for **web cache validation**, and which allows a client to make conditional requests. This allows caches to be more efficient, and saves bandwidth, as a web server does **not need to send a full response if the content has not changed**.


## Auto ETag

    # lib/rack/etag.rb
    def call(env)
      status, headers, body = @app.call(env)
      parts = []
      body.each { |part| parts << part.to_s }
      headers['ETag'] = %("#{Digest::MD5.hexdigest(parts.join(""))}")
      [status, headers, parts]
    end

## 通通第一天就內建
{:.shout .medium}


## That's why you should use Rails
{:.shout .medium}


## Rails 還能作什麼？
{:.shout .medium}

{:.shout .medium .with-picture}
## Package Management
![](pictures/package.jpg)

## Gemfile

    gem "jquery"
    gem "font-awesome"
    gem "tinymce-rails"
    gem "bootstrap-rails", "2.2.0"
    gem "backbone-on-rails"

## Upgrade Asset

    gem "jquery"
    gem "font-awesome"
    gem "tinymce-rails"
    gem "bootstrap-rails", "2.3.0"
    gem "backbone-on-rails"

## Benefit

* 不會弄髒 Git history
* easy upgrade
* dependency


## Directory Management
{:.shout .medium}

## 目錄結構

* app/assets # application 手寫專用 assets
* lib/assets # 常用系統 library
* vendor/assets # 第三方 assets , 如 jQuery plugin

## Bootstrap Hack (1)

    //= require bootstrap-wrapper
    //= require awesome-bootstrap-theme
    //= require awesome-bootstrap-theme-override

## Bootstrap Hack (2)

    @import "bootstrap-setting";
    @import "twitter/bootstrap/variables";
    @import "bootstrap-override";

## Bootstrap Hack (3)

    // puts your override variable here
    // $baseFontSize:  13px;
    // $navbarHeight:  50px;

    $navbarInverseLinkColor: #ddd;
    $navbarInverseBackground: #222;
    $navbarInverseBackgroundHighlight: #610403;
