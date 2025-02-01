---
---
 

## Product Category

{% capture text %}

dddddddddddddd
{%
  include button.html
  link="Origami"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/flying_elephant.gif"
  link="Origami"
  title="Our Research"
  text=text
%}


<video id="video" controls="controls" width="800" height="450" preload="none" poster="封面">
      <source id="mp4" src="Origami/0_1-manual_manipulation.mp4" type="video/mp4">
</video>

 