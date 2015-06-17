---
layout: post
title:  "How to Write Blog"
date:   2012-09-12 15:40:56
categories: blog update
---

=== Personal Strengths ===
* An item in a bulleted (unordered) list
* Another item in a bulleted list
** Second Level
** Second Level Items
*** Third level

=== Some Code ===

{% highlight ruby linenos %}
def show
  @widget = Widget(params[:id])
  respond_to do |format|
    format.html # show.html.erb
    format.json { render json: @widget }
  end
end
{% endhighlight %}