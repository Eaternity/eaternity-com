---
layout: page
name: organic
type: post
title:  "Consortium"
categories: foodprint
published: true
permalink: /foodprint
---

<div class="container-hero-10 container-hero-1 clearfix" style="background-image: url('/images/Sonnenaufgang-3.jpg');background-size: 500px 229px;background-position: left center;;background-size: 100%">
	<div class="container-hero-content container-hero-content-1 clearfix">
		<div class="container-4 clearfix" style="margin-bottom:-40px;margin-top:30px;width: 960px;height: 46px;border-bottom: 1px solid rgb(0, 0, 0);">
			<button class="text text-5" style="text-align:left" onClick="window.location='/foodprint';" >FoodPrint Consortium</button>
				{% for menu in site.categories["foodprint"] %}
				{% if menu.lang == page.lang %}
				<button class="_button" style="float:right;margin-left:20px;margin-top:8px;font-size:0.95em" onClick="window.location='{{menu.url}}';">{{menu.title}}</button>
				{% endif %}{% endfor %}
		</div>
		<br />
		<img class="image image-1" src="/images/nur-logo-klein-480x299-3.png" data-rimage data-src="/images/nur-logo-klein-480x299-3.png" data-srcat2x="/images/nur-logo-klein-480x299-3@2x.png">
		<img class="image image-2" src="/images/cloud-negativ-248x231-1.png" data-rimage data-src="/images/cloud-negativ-248x231-1.png" data-srcat2x="/images/cloud-negativ-248x231-1@2x.png">
		<div class="hero-title hero-title-1">FoodPrint Consortium</div>
	</div>
</div>


<div class="container">
	<div class="row">
		<div class="col-md-2"></div>
		<div class="col-md-8">
			<br />
			<p>We believe in the power of sharing data and knowledge. Our vision is to create a scientific knowledge hub on Food and its related impacts. We want to achieve this by providing appropriate ICT infrastructure for data storage, management and harmonization and setting-up a governance structure for regulating publication rights and data exchange. By sharing our findings and fostering exchange we can accelerate progress in research and jointly increase our impact. </p>
			<br />
		</div>
		<div class="col-md-2"></div>
	</div>
</div>


<div class="gradient-box">
<div class="container">
	
	<div class="row">
		<div class="col-md-2"></div>
		<div class="col-md-8">
			
			<p class="black-font">1. Scientific validation (a scientific knowledge hub).</p>
			<p>
			We think that scientific methodology is our best guide for decisions. The food system is complex and entangled with other sectors and aspects of life. It is hard for one person to oversee it all. Measurability and generating transparency are key to informed decisions.</p>
			<p>
			We believe in the power of sharing data and knowledge. Our vision is to build a scientific knowledge hub on Food and its related impacts. We provide an ICT infrastructure for data storage and management and a governance structure for regulating publication rights and data exchange. By sharing our findings and fostering exchange we can accelerate progress in research and increase our impact.</p>
			
			<p class="black-font">2. Easy and practicable tools.</p>
			<p>
			Knowledge can be useless if it is not accessible to and applicable for all. We extremely value use-friendly instruments and tools that support daily decisions. Our strategy is not to compromise with accuracy by reducing complexity. We want to empower people to deal with complexity. This is our motivation with all the tools that we develop. Let it be for scientists, restaurant managers, cooks or any individual that has a private interest.</p> 
			
			<p class="black-font">3. Have impact (as a community)</p>
			<p>
			The only true validation of our work lies in our actual impact. Creating comparability and transparency and measure progress is intrinsically connected to the way we work. In the end we will only have an impact through the work and efforts of others. We further try to choose strategically which groups to support first to maximize impact. We need everyone on board!</p>
			
			
			
			<br />
		</div>
		<div class="col-md-2"></div>
	</div>
	
	
	<div class="row">
		<div class="col-md-2"></div>
		<div class="col-md-8">
			<p class="black-font">Join our projects:</p><br />
		</div>
		<div class="col-md-2"></div>
	</div>
	
	<div class="row">
		<div class="col-md-2"></div>
		<div class="col-md-4 hover-zoom" style="background-image: url('/images/gruenGelb.jpg');background-size: 500px 229px;background-position: left center;;background-size: 100%;height:140px;"><br /><br />
			<a href="/foodprint/organic"><div class="hero-title hero-title-1">Organic</div></a>
		</div>
		<div class="col-md-4 hover-zoom" style="background-image: url('/images/roooot.jpg');background-size: 500px 229px;background-position: left center;;background-size: 100%;height:140px;"><br /><br />
			<a href="/foodprint/health"><div class="hero-title hero-title-1">Health</div></a>
		</div>
		<div class="col-md-2"></div>
	</div>
	
	
</div>
</div>



<style>
.black-font {
	padding: 50px 0 0 0;
	margin:0;
	font-family: 'Futura LT', 'Helvetica Neue', Helvetica, Arial, sans-serif;
	font-size: 41px;
	font-style: normal;
	font-variant: normal;
	font-weight: 200;
	line-height: 55px;
	color: rgb(0, 0, 0);
}

.gray-font {
	padding: 0;
	margin:0;
	font-family: 'Futura LT', 'Helvetica Neue', Helvetica, Arial, sans-serif;
	font-size: 41px;
	font-style: normal;
	font-variant: normal;
	font-weight: 200;
	color: rgb(126, 126, 126);
	line-height: 55px;
}

.gradient-box {
	background-color: rgb(222, 222, 222);
	background-image: linear-gradient(360deg, rgb(255, 255, 255) 0%, rgb(245, 245, 245) 100%);
	min-width:1000px;
}

p {
	margin-top:10px;
	text-align:left;
}

img {
	margin-bottom:100px;
	margin-top:60px;
}

.shadow {
	box-shadow: 0px 0px 3px #888888;
}

.container {
	min-width:1000px;
}

.container-hero-10 {
  height: 540px;
}

.hero-title {
	color: rgb(255, 255, 255);
}

.hover-zoom div {
    -webkit-transition: all 1s ease; /* Safari and Chrome */
    -moz-transition: all 1s ease; /* Firefox */
    -ms-transition: all 1s ease; /* IE 9 */
    -o-transition: all 1s ease; /* Opera */
    transition: all 1s ease;
}

.hover-zoom:hover div {
    -webkit-transform:scale(1.05); /* Safari and Chrome */
    -moz-transform:scale(1.05); /* Firefox */
    -ms-transform:scale(1.05); /* IE 9 */
    -o-transform:scale(1.05); /* Opera */
     transform:scale(1.05);
}


</style>
