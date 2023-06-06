pnpm dev

if live-server gives you problems (black screen), try increasing the wait value on the serve:html5 command and running everything again

i used live-server instead of vite for this one because haxe flixel does some damn weird stuff that triggers the js output to change like 20 times in every haxe compilation, live-server has an option to wait x MS before reloading everything, which vite doesn't, the problem is that vite crashes with this and leaves you hanging with a black screen, and then you have to manually reload it every time which kinda misses the whole point of doing all of this

[demo](https://youtu.be/hD0aFZIA1wU) (~5 seconds on first build, < 1.5s on following builds)