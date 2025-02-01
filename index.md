---
---
 

## Product Category

{% capture text %}

dddddddddddddd
{%
  include button.html
  link="1_origami"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/flying_elephant.gif"
  link="1_origami"
  title="Our Research"
  text=text
%}

<video id="video" controls="" preload="none" poster="封面">
      <source id="mp4" src="images/0_1-manual_manipulation.mp4" type="video/mp4">
</video>

 
 