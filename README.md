<!-- TOC -->

- [reveal.js's sample](#revealjss-sample)
- [Environmental preparation](#environmental-preparation)
- [Display slides](#display-slides)
- [Create slides](#create-slides)

<!-- /TOC -->

# reveal.js's sample

sample  
<https://araryo1993.github.io/reveal-js-sample/index.html>

# Environmental preparation
settings
- Git (<https://git-scm.com/downloads>)
- Node.js (<https://nodejs.org/ja/>)

clone repository  
```
git clone https://github.com/hakimel/reveal.js
```

# Display slides
Execute the following to start the server.  
```
npm install
npm start
```

# Create slides
You can create and modify slide by modifying index.html.
And, You can create slides in Markdown by editing the following index.html.  

```
<div class="reveal">
	<div class="slides">
		<section data-markdown="./slide.md"
			data-separator="---$"
			data-separator-vertical=">>>$">
		</section>
	</div>
</div>
```

`section data-markdown`:`.md`file path  
`data-separator`:define go to right page  
`data-separator-vertical`::define go to under page
