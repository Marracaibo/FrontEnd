# FrontEnd
a portfolio project based on http://kenwheeler.github.io/slick/ tamplate. 
Demo
http://kenwheeler.github.io/slick
Responsive Option Example
The responsive option, and value, is quite unique and powerful. You can use it like so:
$(".slider").slick({

  // normal options...
  infinite: false,

  // the magic
  responsive: [{

      breakpoint: 1024,
      settings: {
        slidesToShow: 3,
        infinite: true
      }

    }, {

      breakpoint: 600,
      settings: {
        slidesToShow: 2,
        dots: true
      }

    }, {

      breakpoint: 300,
      settings: "unslick" // destroys slick

    }]
});

Dependencies
jQuery 1.7

i used 8icon for the icons 

Rights: You are permitted to use the resources for any number of personal and commercial projects.
You may modify the resources according to your requirements and include them into works, such as websites, applications or other materials intended for sale.
No attribution or link back to this site is required, however any credit will be much appreciated.
Prohibitions: You do not have the rights to redistribute, resell, lease, license, sublicense or offer files downloaded 
to any third party ìas isî or as a separate attachment from any of your work. If you wish to promote my resources on your site, 
you must link back to the resource page where users can find the download and not directly to the download file.
