let link=document.createElement('link'); link.rel="stylesheet"; 
	link.href="https://mehedihasannabil.github.io/youtube/border_animation.css"; 
	document.getElementsByTagName('head')[0].appendChild(link);
if (document.getElementsByTagName('html')[0].getAttribute('dark') === 'true') {
	const link=document.createElement('link'); link.rel="stylesheet"; 
	link.href="https://mehedihasannabil.github.io/youtube/dark_youtube.css"; 
	document.getElementsByTagName('head')[0].appendChild(link);
} else {
	const link=document.createElement('link'); link.rel="stylesheet"; 
	link.href="https://mehedihasannabil.github.io/youtube/light_youtube.css"; 
	document.getElementsByTagName('head')[0].appendChild(link);
}
