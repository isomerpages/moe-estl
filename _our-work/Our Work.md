---
title: Our Work
permalink: /our-work/
description: ""
---
<style>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@900&display=swap');
    .careers {
        display: grid;
        justify-content: space-around;
        grid-gap: 20px;
        grid-template-columns: 35% 35% 35%;
    }
    .career {
        position: relative;
        display: flex;
        flex-direction: column;
        border-radius: 8px;
        padding: 23px;
        /* border: 1.5px solid #474849; */
        box-shadow: 0 0 4px rgba(33,33,33,.2);
        cursor: pointer;
    }
    .career:hover {
        box-shadow: 0 0 11px rgba(33,33,33,.2);
    }
    .career-title {
        margin-top: 20px;
        font-family: "Montserrat", sans-serif;
        font-size: 26px;
        color: #276ef1 !important;
    }
    .career-sum {
        font-family: "Lato", sans-serif;
        font-size: 17px;
        margin: 10px 0 !important;
        flex-grow: 2;
        line-height: 24px !important;
        /* color: #276ef1 !important; */
    }
    .link-tag {
        position: absolute;
        top: 0;
        bottom: 0;
        left: 0;
        right: 0;
        margin-bottom: 0 !important;
    }
    @media only screen and (max-width: 600px) {
        .careers {
            grid-template-columns: 100%;
        }
    }
</style>

## How we Work
When we build solutions for our users, we don’t merely start with the user. We have actual users within the team! Teachers (Education Officers) who have many years of on-ground experience and domain knowledge are part of our development team, serving as product managers. They have the utmost empathy for all our teachers, having been there and champion strongly the user perspective. 

What’s more, as an in-house unit within the Ministry of Education, we have direct access to speak to and test out our solutions with schools and teachers. That means we constantly ensure that we are building the right solutions, while our engineers ensure the solutions are built right.

We are organised in focused cross-functional Agile teams working together from the get-go. We build quickly, measure the outcomes and use the data to learn and iterate continually. Ultimately, we seek to enable every student on their journey to realise their potential.



## Our Work
This could be the overview page of all our products or work that we do. We choose to name it as "Our Works" as some of our work is not exactly to build a product but help out in different ways.


**Markdown - 3col**

| ![All Ears](/images/work-allears-thumb.png) | ![FlexiList](/images/work-flexilist-thumb.png)  | ![One School Bus](/images/work-oneschoolbus-thumb.png) |
| -------- | -------- | -------- |
| **All Ears**     | **FlexiList**     | **One School Bus**     |

**Markdown - 2col (with text link, image cannot link)**

| ![All Ears](/images/work-allears-thumb.png) | ![FlexiList](/images/work-flexilist-thumb.png)  |
| -------- | -------- |
| **[All Ears](https://moe-estl-staging.netlify.app/what-we-do/all-ears/)**     | **[FlexiList](https://moe-estl-staging.netlify.app/what-we-do/flexi-list/)**     |


**HTML row col (image link + text)**

<div class="row">  
	<div class="col"> 
    <a href="/what-we-do/all-ears/"><img src="images/work-allears-thumb.png" alt="All Ears"></a><br>
     <div class="header"><b>All Ears</b></div><br>
  </div>
	<div class="col"> 
      <a href="/what-we-do/flexi-list/">  <img src="images/work-flexilist-thumb.png" alt="FlexiList"></a><br>
       <div class="header"><b>FlexiList</b></div><br>
	</div>
</div>
	
**HTML copy from OGP**
<div class="careers">
    <div class="career">
            <a href="/products/checkfirst" class="link-tag"></a>
			<img src="https://d33wubrfki0l68.cloudfront.net/44e87bd9f4a94c9e5bedc763c6b08cb38ce55f2f/ac86c/images/checkfirst.png" class="border-radius: 8px;" alt="CHECKFIRST" title="CHECKFIRST">
        <span class="career-title">CHECKFIRST</span>
        <span class="career-sum">Calculator and eligibility builder for the government</span>
    </div>
    
    <div class="career">
            <a href="/products/datagovsg" class="link-tag"></a>
        <img src="https://d33wubrfki0l68.cloudfront.net/097e3650297f66313d94938cdc9fcb192d4734fd/3939c/images/data.gov.sg.png" class="border-radius: 8px;" alt="DATA.GOV.SG" title="DATA.GOV.SG">
        <span class="career-title">DATA.GOV.SG</span>
        <span class="career-sum">Open repository for Singapore’s public data</span>
    </div>
    
    <div class="career">
            <a href="/products/digimc" class="link-tag"></a>
        <img src="https://d33wubrfki0l68.cloudfront.net/fb85b3584824e050b505821974f15751a3f30053/1ea07/images/digimc.png" class="border-radius: 8px;" alt="DIGIMC" title="DIGIMC">
        <span class="career-title">DIGIMC</span>
        <span class="career-sum">Digital medical certificates with assured authenticity</span>
    </div>

</div>