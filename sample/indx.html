// Set animation delay if data-delay is specified
Reveal.addEventListener('ready', function ( event ) {
  $('*[data-delay]').each( function () { 
    var delay = $(this).attr("data-delay");
      $(this).css("-webkit-animation-delay", delay+"s"); 
      $(this).css("animation-delay", delay+"s"); 
  });
});

// Set animation duration if data-duration is specified
Reveal.addEventListener('ready', function ( event ) {
  $('*[data-duration]').each( function () { 
    var duration = $(this).attr("data-duration");
      $(this).css("-webkit-animation-duration", duration+"s"); 
      $(this).css("animation-duration", duration+"s"); 
  });
});

// Animate items that are not in a fragment
Reveal.addEventListener('slidechanged', function( event ) {
  // Animate elements that are not a fragment (or in a fragment)
  var filter = '*[data-animate]:not(.fragment):not(.fragment *)';
  
  $(event.currentSlide).find(filter).each( function () {
    $(this).addClass('animated');
    $(this).addClass($(this).attr('data-animate'));
  });		
  $(event.previousSlide).find(filter).each( function () {
    $(this).removeClass('animated');
    $(this).removeClass($(this).attr('data-animate'));
  });		
});

// Animate fragments
Reveal.addEventListener('fragmentshown', function( event ) {
  function loop(i, el) { 
      if ($(el).attr('data-animate')) {
        $(el).addClass('animated');
        $(el).addClass($(el).attr('data-animate'));
      }
      $.each($(el).children().not('.fragment'), loop);
  };
  $.each(event.fragments, loop);
});

// Make the animation runnable again if fragment is hidden
Reveal.addEventListener('fragmenthidden', function( event ) {	  
  function loop(i, el) { 
      if ($(el).attr('data-animate')) {
        $(el).removeClass('animated');
        $(el).removeClass($(el).attr('data-animate'));
      }
      $.each($(el).children().not('.fragment'), loop);
  };
  $.each(event.fragments, loop);
});
For example:

<section>
	<h3 data-animate="bounce slower">Animations are supported too!</h3>
	See <a href="https://github.com/daneden/animate.css">Animate.css</a>.
	<div class="fragment">
		<span data-animate="shake">On</span>
		<span data-animate="wobble">fragments</span>
		<span data-animate="fadeInLeft">too!</span>
	</div>
	<div>
		<p class="fragment" data-animate="fadeInLeft">
			Speed can be controlled with <span data-delay="2" data-animate="bounce" class="infinite">.infinite</span> or <span data-animate="bounce" data-delay="2" data-duration="5">data-duration</span>.
		</p>
		<p class="fragment" data-animate="fadeInRight">
			Animations can be delayed with <span data-delay="2" data-animate="fadeIn"><span data-delay="3" data-animate="bounce">data-delay</span>!</span>
		</p>
	</div>
</section>
This code requires your CSS to include span { display: inline-block; } (otherwise, some animations do not apply on span element).