# Words on a Screen

## What is Words on a Screen?

Words on a Screen is website that displays provided words on your screen. It does its best to render the words as large as possible.

## How do I use Words on a Screen?

Words on a Screen is located at https://jonathannye.github.io/wordsonascreen/

You can provide your own words via the query parameter `words`. For example:

<pre><a href="https://jonathannye.github.io/wordsonascreen/?words=hello%20friend">https://jonathannye.github.io/wordsonascreen/?<b>words=hello%20friend</b></a></pre>

Words on a Screen is not clever enough to break your words into multiple lines. We all have our limitations. However, you may give it some help by inserting `%0A` escapes into your provide words. For example:

<pre><a href="https://jonathannye.github.io/wordsonascreen/?words=one%20line%0Atwo%20line">https://jonathannye.github.io/wordsonascreen/?words=one%20line<b>%0A</b>two%20line</a></pre>

Different `mode`s are also supported:

* If you are [feeling salty](https://www.youtube.com/watch?v=3KquFZYi6L0), you may also provide `mode=salt` and your feelings will be vindicated. Example:
<pre><a href="https://jonathannye.github.io/wordsonascreen/?words=so%20saline&mode=salt">https://jonathannye.github.io/wordsonascreen/?words=so%20saline<b>&mode=salt</b></a></pre>
* If you enjoy red, green, and pretty snow you may provide `mode=xmas`. Example:
<pre><a href="https://jonathannye.github.io/wordsonascreen/?words=so%20pretty&mode=xmas">https://jonathannye.github.io/wordsonascreen/?words=so%20pretty<b>&mode=xmas</b></a></pre>

## Why does Words on a Screen exist?

Words on a Screen was created primarily to display words on Chromecasts in concert with [DashCast](https://stestagg.github.io/dashcast/). The advantage of using DashCast over, say, casting a Chrome tab, is that the page will stick around indefinitely without any need to keep a tab open.

My personal use case was that each team space in my org usually had at least one TV with a Chromecast for displaying project dashboards. With Words on a Screen, I could occasionally co-opt them for ~~guerilla workplace memery~~ organic team camaraderie.

## Why is Words on a Screen the way it is?

I'm not a Web dev by trade, I'm in this for the memes.

My friend [Sam](https://github.com/samuelmaddock) helped out a lot, particularly with the cool text-fitting stuff that was cribbed from another [meme-based application](https://codepen.io/samuelmaddock/pen/VGemQy).