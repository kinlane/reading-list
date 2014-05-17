---
layout: post
title: Why JSONP is still Mandatory
url: http://blog.algolia.com/jsonp-still-mandatory/
source: http://blog.algolia.com/jsonp-still-mandatory/
domain: blog.algolia.com
image: 
---

<p>At Algolia, we are convinced that search queries need to be sent directly from the browser (or mobile app) to the search-engine without any intermediate layers in order to have a realtime search experience. This is why we have developed a search backend that replies within a few milliseconds through an API that handles security when called from the browser.Cross domain requests For security reasons, the default behavior of a web browser is to block all queries that are going to a domain that is different from the website they are sent from.So when using an external HTTP-based search API, all your queries should be blocked because they are sent to an external domain.There are two methods to call an external API from the browser: The JSONP approach is a workaround that consists in calling an external API  with a DOM  &lt; script &gt;  tag.</p>
<center><p><a href="http://blog.algolia.com/jsonp-still-mandatory/" style='padding:25px; font-sze:18px; font-weight: bold;'>Read Full Story</a></p></center>
