# Auto Skip extension for Netflix, Prime and Disney+

🏎 Auto Skip Intro, Recaps, Credits and Ads 🏎.

Just install the extension and you will be happy to binge watch everything like a pro 📺

## Install

* Select the following code
* Drag and drop the code in your bookmark toolbar
* Open the streaming website and click on the newly created shortcut
* Enjoy, your won't need to wait anymore to binge watch!

`javascript:var e="Prime Video";setInterval(function(){return function(){for(var i=0,o=[{platform:"Netflix",info:"Skipping credits.",selector:".skip-credits > a"},{platform:"Netflix",info:"Playing next episode.",selector:'[data-uia="next-episode-seamless-button"]'},{platform:"Netflix",info:"Continue playing.",selector:"[aria-label='Continue Playing']"},{platform:"Netflix",info:"Skipping recap.",selector:"[aria-label='Skip Recap']"},{platform:"Netflix",info:"Skipping intro.",selector:"[aria-label='Skip Intro']"},{platform:e,info:"Skipping credits.",selector:".f1oordr3"},{platform:e,info:"Playing next episode.",selector:".fd8k8m6"},{platform:e,info:"Skipping ad.",selector:".adSkipButton"},{platform:e,info:"Skipping recap.",selector:".skipElement"},{platform:"Disney+",info:"Skipping credits",selector:".skip__button"},{platform:"Disney+",info:"Playing next episode",selector:"button.sc-gipzik.play"}];i<o.length;i++){skipSelector=o[i];var t=document.querySelector(skipSelector.selector);if(t){t.click(),console.log(skipSelector.platform+": "+skipSelector.info);break}}}()},500);`

![Install](install.gif)