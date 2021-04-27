---
layout: default
title: Hello, TypiJS
subtitle: A CMS framework for building fully-featured SPA sites built on Angular, NodeJS and MongoDB with TypeScript
sitemap:
  priority: 0.9
---

<div class="hero-banner">
	{% include page/title.html %}

    <img src="{{ '/assets/imgs/typijs-logo.png' | prepend: site.baseurl }}" id="footer-img"/>

	<div id="describe-text">
		<p>A simple, minimal CMS portal for a small and medium sites, focusing on creating content</p>
		<p>Get started from <strong> <a href="https://github.com/typijs/typijs"> repository</a> </strong></p>
	</div>

	<div class="video-container">
		<video width="100%" poster="https://github.com/angular-cms/angular-cms/raw/main/resources/images/on-page-preview.jpg" controls>
			<source src="/assets/videos/angular-cms.webm" type="video/webm">
		</video>
	</div>    
</div>

<div class="container">
<section>
	<div class="row">
		<div class="col-50">
				<h2>How can I <strong>keep track</strong> of my sales team?</h2>
				<p>Hydra learns your business. By analyzing your sales data, Hydra optimizes your sales process and show you where you should be spending your resources.</p>

		</div>
		<div class="col-50">
			<img src="/assets/imgs/typijs-bg-1.jpg"/>
		</div>
		
	</div>
	</section><section>
	<div class="row">
		<div class="col-50">
			<h2>How can I <strong>keep track</strong> of my sales team?</h2>
				<p>Hydra learns your business. By analyzing your sales data, Hydra optimizes your sales process and show you where you should be spending your resources.</p>

		</div>

		<div class="col-50 col-reorder">
			<img src="/assets/imgs/typijs-bg.png"/>
		</div>
	</div>
</section><section>
	<div class="row">
		<div class="col-50">
			<h2>How can I <strong>keep track</strong> of my sales team?</h2>
				<p>Hydra learns your business. By analyzing your sales data, Hydra optimizes your sales process and show you where you should be spending your resources.</p>

		</div>
		<div class="col-50">
			<img src="https://github.com/angular-cms/angular-cms/raw/main/resources/images/on-page-preview.jpg"/>
		</div>
		
	</div>
	</section>
</div>

{% include page/footer.html %}


