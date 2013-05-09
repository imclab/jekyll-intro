---
layout: default
title: My first post with Jekyll
---

Now I'm blogging with Jekyll and I wanted to show you some ruby code I wrote recenty:


{% highlight ruby %}
@posts.each do |post|
  puts "<h1><%= post.title %>"
end
{% endhighlight %}
