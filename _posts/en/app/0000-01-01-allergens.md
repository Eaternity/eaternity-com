---
layout: page
name: app-allergens
type: post
title:  "Allergens"
categories: app
---

<div>
	<div class="container-hero container-hero-1 clearfix" style="background-repeat: no-repeat;background-size: 1500px 1000px;background-color: rgba(0, 0, 0, 0.0);height: 700px;background-position: 50% 30%;">
		<div class="container-hero-content container-hero-content-1 clearfix">
			<div class="container-4 clearfix" style="margin-bottom:0px;margin-top:30px;width: 960px;height: 46px;border-bottom: 1px solid rgb(0, 0, 0);">
				<button class="text text-5" style="text-align:left;color: #000;" onClick="window.location='/app';" >Eaternity App</button>
				{% for menu in site.categories["app"] %}
				{% if menu.lang == page.lang %}
				<button class="_button" style="float:right;margin-left:20px;margin-top:8px;font-size:0.95em;color: #000;" onClick="window.location='{{menu.url}}';">{{menu.title}}</button>
				{% endif %}{% endfor %}
			</div>
			<img class="image image-1" src="/images/nur-logo-klein-480x299-3.png" data-rimage data-src="/images/nur-logo-klein-480x299-3.png" data-srcat2x="/images/nur-logo-klein-480x299-3@2x.png">
			<!-- <div class="hero-title hero-title-1">Eaternity Reports</div> -->
			<div class="hero-subtitle hero-subtitle-1">Compliant declaration of allergens in your restaurant</div>
			<!-- <button class="_button _button-79">Your customers put their trust in you. Show them you care and join the leaders community on sustainability now. Small effort – Big impact.</button> -->
		</div>
	</div>
</div>


<div style="background: -webkit-linear-gradient(90deg, rgb(255, 255, 255) 0%, rgb(245, 245, 245) 100%) rgb(222, 222, 222);">
	<div class="container">
		<div class="row" style="height:100px">
			<div class="col-md-1"></div>
			<div class="col-md-10">
				<p>We prepare you for allergens compliance regulations enabling you to concentrate on your core business.
The new food labeling EU-regulation 1169/2011 for allergens becomes effective on 13.12.2014 and requires gastro-businesses  in all 28 EU-countries to display ingredient information relating to the fourteen main allergens.

Our automated and rapid analysis of the ingredients used in your restaurant’s meals reduces your workload. by making The information you need on a daily basis is available at your fingertips. Employees have easy access to meet the information requirements of every guest and can print comprehensive and customized meal labels with minimum effort.

If you haven’t got a digital recipe management storage system yet be sure to have a look at our menu-design studio or get in touch with us for more information.

Declaring allergens properly is just the beginning. With our app solution you can also manage and analyze all other nutritional information that interests you. We keep the data up-to-date and legally compliant so you don’t have to.
</p>
			</div>
			<div class="col-md-1"></div>
		</div>
	</div>
</div>
