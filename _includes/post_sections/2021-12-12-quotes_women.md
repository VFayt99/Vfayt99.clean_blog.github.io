<!-- ---
layout: post
title: "Topics of Quotes by Women"
# subtitle: "because they lacked opposable thumbs and the brainpower to build a space program."
background: ''
--- -->

The female voice in media is underrepresented not only in a quantitative perspective but also in a qualitative perspective and female expert opinions are reportedly underrepresented in certain male-dominated topic fields like politics, governemnt and enonomy and  [8](https://www.coe.int/en/web/genderequality/women-in-media ). Let’s see if we can confirm these claims using the data at hand. Therefore, we preprocessed the quotes extracted from Quotebank in a standard NLP pipeline and conducted topic analysis either on quotes from male or from female speakers, to elucidate diverging trends in mentioned topics based on gender.

#### Topics of Quotes by Women and Men

Some expected and classically gender-associated topics appeared in the topic analysis: In the quotes of women, the topic of lifestyle and fashion appears as a common topic (third topic), which is absent in men’s quotes, whereas the topic of sports (seventh topic) and business (sixth topic) is prominent with men but doesn’t crystallize in female quotes.

<div class="row">
    <div class="col-lg-6">
            <div class="d-block h-100">
                <img src="https://raw.githubusercontent.com/VFayt99/femedia/master/_includes/post_sections/imgs_by/top_quotes_female_gdsmm_topic_6.png" style="width:100%">
            </div>
    </div>
    <div class="col-lg-6">
            <div class="d-block h-100">
                <img src="https://raw.githubusercontent.com/VFayt99/femedia/master/_includes/post_sections/imgs_by/top_quotes_male_gdsmm_topic_2.png" style="width:100%">
            </div>
    </div>
</div>

But also the topic of social issues (ethnicity, sexuality, family) is a prominent topic with female speakers but doesn’t clearly show in male quotes. 

<div class="row">
    <div class="col-lg-6">
            <div class="d-block h-100">
                <img src="https://raw.githubusercontent.com/VFayt99/femedia/master/_includes/post_sections/imgs_by/top_quotes_female_gdsmm_topic_2.png" style="width:100%">
            </div>
    </div>
    <div class="col-lg-6">
            <div class="d-block h-100">
                <img src="https://raw.githubusercontent.com/VFayt99/femedia/master/_includes/post_sections/imgs_by/top_quotes_male_gdsmm_topic_6.png" style="width:100%">
            </div>
    </div>
</div>


If we consider very similar topics in both datasets like business and government, it still seems that in general there is a different spin on how the topics seem to be approached. Female quotes have a community and social aspect, whereas in male quotes it seems to be more focused on either business or politics in the pure sense.

<div class="row">
    <div class="col-lg-6">
            <div class="d-block h-100">
                <img src="https://raw.githubusercontent.com/VFayt99/femedia/master/_includes/post_sections/imgs_by/top_quotes_female_gdsmm_topic_1.png" style="width:100%">
            </div>
    </div>
    <div class="col-lg-6">
            <div class="d-block h-100">
                <img src="https://raw.githubusercontent.com/VFayt99/femedia/master/_includes/post_sections/imgs_by/top_quotes_male_gdsmm_topic_5.png" style="width:100%">
            </div>
    </div>
</div>
<br>
<div class="row">
    <div class="col-lg-3">
    </div>
    <div class="col-lg-6">
            <div class="d-block h-100">
                <img src="https://raw.githubusercontent.com/VFayt99/femedia/master/_includes/post_sections/imgs_by/top_quotes_male_gdsmm_topic_1.png" style="width:100%">
            </div>
    </div>
    <div class="col-lg-3">
    </div>
</div>


##### Proportion of quotes from each topic, for male and female quotes:
<iframe width="100%" height="500" frameborder="0" scrolling="no" src="//plotly.com/~natasakrco/7.embed"></iframe>

The number of quotes in common topics still show that women are mentioned far less in classically male-dominated fields like politics, economy, business, and sports. And there are very cliché heavy topics like beauty and lifestyle which appear among the leading topics for female quotes whereas they are very rare for male speakers and vice versa for very male-heavy topics like sports.

##### Distribution of topics by gender and bias of journal:

We further investigate the distribution of quote numbers of the common  topics found in the whole subset. One interesting aspect is if the topic distribution is strikingly different in right- vs. left-leaning media outlets, which would indicate a different perception of women in the political parties. 

<iframe width="100%" height="1200" frameborder="0" scrolling="no" src="//plotly.com/~natasakrco/26.embed"></iframe>

Another potentially interesting aspect is the gender of the direct producer of the text. One might expect that the gender of the text author might influence his/her choice of person to quote. However, as discussed in the [section about the construction of the dataset](https://vfayt99.github.io/femedia/2021/01/04/Data.html), we could only get a hold of the editors-in-chief of the journal in question as the closest and accessible approximation for the person deciding on the content in the media outlet. However, the plots clearly show that the distribution of topics is very similar in the different subset of the overall dataset. It seems that the topics for which both women and men are quoted do not strongly depend on the editor's gender. 

##### Most frequent words in Quotes by Women and Men in a pretty Slideshow

For those interested in all the topic clusters we have found, you can find the slideshows for both female and male speaker topics below!

{% include post_sections/carousel_topicybywomen.html %} {% include post_sections/carousel_topicybymen.html %}
