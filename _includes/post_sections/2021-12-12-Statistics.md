<!-- ---
layout: post
title: "Statistics"
# subtitle: "because they lacked opposable thumbs and the brainpower to build a space program."
background: ''
--- -->

## US Media Landscape
<br><br>
Let's first dig into the US media landscape. In the previous section we already discussed why we only considered high circulation media sources. Having a manageable dataset of 147 US media sources, we can investigate the representation of female chief-editors in US media source.
<br><br>
<div class="row">
      <div class="col-lg-4" style="background-color:rgba(173, 216, 230, 0.5); text-align:center">
            <div class="d-block h-100">
                <h4 style="color:#858585;"><br>Gender of editor representation</h4>
                  <p align="justify"> Out of <b>147 US media sources</b> with the highest circulation, only <b>35% of them have female chief-editors</b> </p>
                <hr style="margin: auto;border-color: rgb(173, 216, 230); border-width: 0.25rem; width: 30%;">
                <p align="justify"> Left rated media sources have a <b>higher proportion of female chief-editors</b> compared to right rated media sources </p>
            </div>
      </div>
      <div class="col-lg-8">
            <div class="d-block h-100">
                <iframe  width = "100%" height= "500" frameborder="0" scrolling="no" src="//plotly.com/~VFayt99/3.embed"></iframe>
            </div>
      </div>
      
</div>


<br><br>

If we look at the graph above we see that male editors largely dominate the position of chief-editors in US media sources. About 65% of the chief-editors are men. If we now concentrate on the differences between left leaning and right leaning media sources, we observe that **left leaning media sources have about 40% of the time female chief-editors**. This is similar to what is observed for least biased sources. However, for **right media sources only about 20% are female chief-editors**. Right-center and right biased media sources have each higher ratio's of female chief-editors but the ratio still remains lower than for left leaning media sources. <br>

So woman are underrepresented in jobs like chief-editors and on top of that it depends on the political bias of the media source they work for. Let's see if we can get other interesting results looking at the quotes of female and male speakers. 

<br><br>

## Gender representation in high traffic US media
<br><br>
Let's dive into our quotes dataset. The sunburst plot below shows the share of female versus male speakers. It then also shows the share of those quotes which come from media sources with male or female chief-editors. Now first of all, let us investigate the distribution of quotes from female versus male speakers. We find ourselves in front of an interesting but somber result - less than 20% of the quotes are from female speakers! We can further investigate to see if female speakers have more quotes if the chief-editors are women. For both male and female speakers about 30% of the quotes come from media sources with female chief-editors. 
<br><br><br>
<div class="row">
    <div class="col-lg-8">
            <div class="d-block h-100">
                <iframe width="100%" height="300" frameborder="0" scrolling="no" src="//plotly.com/~VFayt99/1.embed"></iframe>
            </div>
      </div>
      <div class="col-lg-4" style="background-color:rgba(173, 216, 230, 0.5); text-align:center">
            <div class="d-block h-100">
                <h4 style="color:#858585;"><br>Gender representation in media sources</h4>
                  <p align="justify"> Out of <b>8 million quotes</b> from high traffic US media news, <b>less than 20%</b> are from female speakers </p>
                <hr style="margin: auto;border-color: rgb(173, 216, 230); border-width: 0.25rem; width: 30%;">
                <br>
            </div>
      </div>
</div>

<br><br>

Let us now consider the bubble graph below which plots the ratio of female speaker quotes over political bias ratings for each high traffic US media source. The sizes of the bubbles represent the amount of both gender speaker quotes, and the gender sign in front of each media source tells us if the editor is a woman or a men. If we first look at the graph with all the media sources we observe a general trend of a **ratio of female speakers around 15-20%** for the whole political bias spectrum. Notice, however, that most of the sources with a female speaker ratio higher than 30% have a female editor and are rated with a left leaning bias. It should be noted that these media sources include women’s magazine such as Glamour Magazine. It is therefore understandable female chief-editors would be in charge for a female audience. The opposite observation of observing the lower bounds of female ratio, is a quite an interesting result: Several media sources with both left and right leaning political views **quote women only 10% of the time**

<iframe width="100%" height="800" frameborder="0" scrolling="no" src="//plotly.com/~VFayt99/18.embed"></iframe>

<br>
If we now look more closely to only media sources with female chief-editors we observe that are mostly on the left spectrum and thet the average ratio of quotes from female speakers is slightly higher than for the right leaning media sources. Looking at only male chief-editors, the spectrum of female ratio and political bias is very diverse. However, we can notice that **media sources with male chief-editors are twice more likely to quote women less than 10% of the time**.

