jq-fixed-widget.js
==================

a jquery plugin to make fixed widget area easily


How to use? Very easy!

after #fixed-widget loaded, use follow code:

  $.fixedwidget({
    fixedObj : '#fixed-sidebar',
    bottomObj : '#footer',
    fixedPos : 10
  });


default options:

  {
    fixedObj : '#fixed-sidebar',  // which box to fixed when scroll window
    bottomObj : '#footer',  // which box to be end of fixed, when #fixed-sidebar is near to #footer, it will be absolute
    fixedPos : 0, // position in window to be fixed, if your site has topnavbar with 50px height, this should be higher
    pre_fun : null, // call function when #fixed-sidebar moves form static into fixed 
    end_fun : null // call function when moves from fixed back into static
  }
