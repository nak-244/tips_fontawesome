# fontAwesomeで丸で囲まれた数字を作る
## 丸で囲んだ数字

~~~html
<p>丸で囲んだ数字
<span class="fa-stack fa-lg">
<i class="fa fa-circle fa-stack-2x"></i>
<i class="fa fa-inverse fa-stack-1x">1</i>
</span>
</p>
~~~

## 大きさはspanタグにfont-sizeで制御
~~~html
<p>大きさはspanタグにfont-sizeで制御
<span class="fa-stack fa-lg" style="font-size: 1em;">
<i class="fa fa-circle fa-stack-2x"></i>
<i class="fa fa-inverse fa-stack-1x">2</i>
</span>
</p>
~~~

### 色はcolorで制御
~~~html
<p>色はcolorで制御
<span class="fa-stack fa-lg" style="font-size: 1em; color: blue;">
<i class="fa fa-circle fa-stack-2x"></i>
<i class="fa fa-inverse fa-stack-1x">3</i>
</span>
</p>
~~~
