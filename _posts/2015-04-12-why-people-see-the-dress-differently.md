---
title: Why people see the dress differently
tags: [optical illusions, perception, science, internet phenomena]
---

# Why people see *the dress* differently

A while back, February 26 2015, a photo of a dress went viral, because people couldn't agree on what color it was: either you see it as white/gold or black/blue.

< figure>
![The dress][dress-image]
</figure>

There are now multiple sources that have good explanations to how it's possible to see either version. The white balance in the image is poor, and depending on how your brain interprets the white balance in the dress, it'll be either white/gold or black/blue. To show that the same color can be interpreted in different ways depending on context, Randall Munroe made [his own version][xkcd], with the backgrounds completely changed:

< figure>
![xkcd's][xkcd-image]
</figure>

If you compare this comic strip to the original, you'll see that the background color in the original is clearly white/light, and nobody would see the background and say that it's dark. The background simply isn't ambiguous, so we can't use that to explain why people see it differently. In a [Scishow video] Hank Green explains how some people interpret the light blue in the dress as white, which in turn makes the darker color gold, while others don't see the image as washed out and therefor don't see any white in the dress at all, making it black and blue. This still doesn't explain *why*. Not even the now fairly extensive [Wikipedia article] has a satisfactory explanation: the hypotheses to why people see different colors only talk about color perception. The Wikipedia article mentions that the photo is overexposed, but doesn't connect that to any hypothesis. My hypothesis is that you interpret the white balance as being changed in different ways:

1. The white balance is off because the photo is *very* overexposed.
2. The white balance is off because the photo is *slightly* overexposed, and the dress is also a slight *silhouette*.

In the image below, the leaves and the twigs are darkened into black, while for example the rock in the water is only slightly darkened. This is what I mean by "slight silhouette".

< figure>
![A full silhouette][silhouette-image]
</figure>

Let's see if we can figure out what combination of effects make people believe what.



1.	**Black and blue.** The photo is taken in normal daylight, but is very overexposed, which causes everything to become brighter.

	Filter              | Background     | Darker color  | Lighter color
	------------------- | -------------- | ------------- | --------------
	Assumed reality     | Normal colors  | Black         | Deep blue
	After overexposure  | Very bright    | Light brown   | Light blue

2.	**White and gold.** There is backlighting, causing the background to darken, and the photo is slightly overexposed, causing everything to become brighter.

	Filter              | Background     | Darker color  | Lighter color
	------------------- | -------------- | ------------- | --------------
	Assumed reality     | Bright         | Gold          | White
	After backlighting  | Bright         | Brown         | Blue
	After overexposure  | Very bright    | Light brown   | Light blue

I *think* this explanation makes sense, but I might have overlooked something. To me, this seems to explain how some people assume that the photo is backlit, others don't, and therefor come to very different conclusions about reality. In case you're still wondering, the dress is actually black and dark blue.

< figure>
![The dress][dress-image]
</figure>



Image credit:

* *[The dress][dress-image]* by Caitlin McNeill
* *[Dress color][xkcd-image]* by Randall Munroe on [xkcd], used under [CC BY NC 2.5]
* *[The silent][silhouette-image]* by Miguel Virkkunen Carvalho [on Flickr][silhouette-image-on-flickr], used under [CC BY 2.0]


[Scishow video]: https://www.youtube.com/watch?v=jexnhNfOzHg
[xkcd]: https://xkcd.com/1492/
[Wikipedia article]: https://en.wikipedia.org/wiki/The_dress_%28viral_phenomenon%29
[dress-image]: ~assets/dress.png "The dress, by Caitlin McNeill"
[xkcd-image]: ~assets/xkcd-dress-color.png "The dress with different backgrounds, by Randall Munroe"
[silhouette-image]: ~assets/silhouette.jpg "The silent, by Miguel Virkkunen Carvalho"
[silhouette-image-on-flickr]: https://www.flickr.com/photos/miguelvirkkunen/4383001572/
[CC BY NC 2.5]: https://creativecommons.org/licenses/by-nc/2.5/
[CC BY 2.0]: https://creativecommons.org/licenses/by/2.0/
