# love.github.io
<audio controls autoplay loop><source src="tuyhongnhan.mp3" type="audio/mpeg"></audio>\\
	<script>
      document.body.addEventListener("click", function (evt) {
        console.dir(this);
        console.log(evt.target);
        var audio = new Audio("sound.mp3");
        audio.oncanplaythrough = function(){
          audio.play();
        }
        audio.loop = true;
        audio.onended = function(){
          audio.play();
        }
      });
    </script>



    
   <audio src="sound.mp3" type="audio/mpeg" controls autoplay loop></audio>