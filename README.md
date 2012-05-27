molokaim
========

An improved Molokai theme for Sublime Text 2 &amp; TextMate

## Motivation
The Molokai theme currently (May 27th, 2012) shipped with Sublime Text 2 is nice but doesn't include some essential syntax highlighting from Markdown. I love Markdown and write it virtually every day, and I'm tired of seeing it so poorly rendered.

## Realization
TextMate themes are horrendous, using XML to declare something as basic is a painful waste of markup, it would almost make Sublime's JSON settings look pithy. So the least people could do is add comments to make that XML soup a little more palatable.

Guess not, so while I'm refining this theme for my taste I'll also be adding useful comments declaring the opening of a sub-section

```xml
<!-- Start Markdown -->
<dict>
  <key>name</key>
  <string>Markup: Separator</string>
  <key>scope</key>
  <string>meta.separator</string>
  <key>settings</key>
  <dict>
    <key>background</key>
    <string>#242424</string>
    <key>foreground</key>
    <string>#60A633</string>
  </dict>
</dict>
<!-- ... -->
<!-- End Markdown -->
```