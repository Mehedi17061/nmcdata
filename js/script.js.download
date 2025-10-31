// Initiate the wowjs
new WOW().init();

// Sticky Navbar
$(window).scroll(function() {
    if ($(this).scrollTop() > 45) {
        $('.nav-sec').addClass('extraclass');
    } else {
        $('.nav-sec').removeClass('extraclass');
    }
});



// $('.testi').owlCarousel({
//nav: false,
 //   margin: 15,
 //   autoplay: true,
 //   loop: true,
 //   autoplayTimeout: 5000,
 //   smartSpeed: 1000,
 //   autoplayHoverPause: true,
//    dots: false,
//    responsive: {
  //      0: {
//            items: 1,
 //           nav: false
 //       }

//    }
//});



    $(".testi").owlCarousel({          loop:true,
        center:false,
        nav:true,
        margin:-7,
		// navText:["<button class='owl-btn cmn-btn'> < </button>","<button class='owl-btn cmn-btn'> > </button>"],
		
        responsive:{
            0:{
                items:1,
            },
            576:{
                items:1,
				   margin:0,
            },
            768:{
                items:1
            },
            992:{
                //items: $('.testi').data('item')
                items: 2
            }
        }
    });


    // $(".team").owlCarousel({      //     loop:true,
    //     center:true,
    //     margin:30,
	// 	navText:["<img src='images/left-arrow.png'>","<img src='images/right-arrow.png'>"],
    //     nav: $('.team').data('nav'),
    //     dots: $('.team').data('dots'),                         //     autoplay: $('.team').data('auto'),
		
    //     responsive:{
    //         0:{
    //             items:1,
    //         },
    //         576:{
    //             items:1,
    //         },
    //         768:{
    //             items:1
    //         },
    //         992:{
    //             //items: $('.testi').data('item')
    //             items: 2
    //         }
    //     }
    // });


    $(".team").owlCarousel({          loop:false,
        center:false,
        nav:false,
		autoplay:false,
		loop: false,
        margin:-7,
		// navText:["<button class='owl-btn cmn-btn'> < </button>","<button class='owl-btn cmn-btn'> > </button>"],
		
        responsive:{
            0:{
                items:1
            },
            576:{
                items:1,
             },
            768:{
                items:2
            },
            992:{
                //items: $('.testi').data('item')
                items: 3
             }
        }
    });



// Testimonials section 
$('.client').owlCarousel({
    nav:false,
	dots:false,
	autoplay:true,
	loop:true,
	margin:20,
	autoplayTimeout: 3500,
	smartSpeed:1000,
    autoplayHoverPause:true,
    responsive:{
        0:{
            items:1
        },
		360:{
            items:2
        },
		767:{
            items:3
        },
		1144:{
            items:5
        },
    }
});



