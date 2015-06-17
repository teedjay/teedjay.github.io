---
layout: post
title:  "New Year with Jekyll!"
date:   2011-12-31 15:40:56
categories: blog update
---

first post
==========

{% highlight ruby %}
def show
  @widget = Widget(params[:id])
  respond_to do |format|
    format.html # show.html.erb
    format.json { render json: @widget }
  end
end
{% endhighlight %}