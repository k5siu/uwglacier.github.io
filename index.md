---
layout: single
author_profile: true
title: "Welcome to the University of Waterloo Glaciology Group Wiki"
---
This website has a wealth of technical tips and tricks that can making your life working with GlaDS (and more!) easier. The goal is that this site will be the central place that we all look for solutions to our specific problems. Along with that, we all need to remember to post about our solutions!

## Contribution instructions
You can contribute from the Github web interface, or by cloning the repository and pushing changes.

Add a markdown file in the `_pages/` directory with your content. If you want to add the file to the top navigation bar, also add the appropriate data to `_data/navigation.yml`.

You can typset math:

$$\frac{\partial u}{\partial t} + \nabla \cdot \vec{q} = 0$$

And you can include pictures from a link with this code:

```html
<figure>
	<a href="http://farm9.staticflickr.com/8426/7758832526_cc8f681e48_b.jpg"><img src="http://farm9.staticflickr.com/8426/7758832526_cc8f681e48_c.jpg"></a>
	<figcaption><a href="http://www.flickr.com/photos/80901381@N04/7758832526/" title="Morning Fog Emerging From Trees by A Guy Taking Pictures, on Flickr">Morning Fog Emerging From Trees by A Guy Taking Pictures, on Flickr</a>.</figcaption>
</figure>
```

<figure>
	<a href="http://farm9.staticflickr.com/8426/7758832526_cc8f681e48_b.jpg"><img src="http://farm9.staticflickr.com/8426/7758832526_cc8f681e48_c.jpg"></a>
	<figcaption><a href="http://www.flickr.com/photos/80901381@N04/7758832526/" title="Morning Fog Emerging From Trees by A Guy Taking Pictures, on Flickr">Morning Fog Emerging From Trees by A Guy Taking Pictures, on Flickr</a>.</figcaption>
</figure>

Or you can include local photos with
```markdown
![image-center]({{ site.url }}{{ site.baseurl }}/assets/images/diurnal_hs_hc.png){: .align-center}

```

![image-center]({{ site.url }}{{ site.baseurl }}/assets/images/diurnal_hs_hc.png){: .align-center}
