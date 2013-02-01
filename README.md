jQuery.unprefixed-events
========================

Vendor-prefix agnostic event binding, eg: $('#myElement').on('transitionend'...)

Bind to any of the following without worrying about which vendor-prefixed event name to use:
* transitionend
* animationstart
* animationiteration
* animationend

Normalises vendor-specific TRANSITION and ANIMATION events (and potentially others too) so that we can easily do things like jQuery('#myElement').on('transitionend'...) without caring about which vendor prefix to use.

Under the hood, jQuery will bind to the appropriate vendor-prefixed event name.

Inspred by the transEndEventNames example at http://modernizr.com/docs/#prefixed

Requires:    jQuery and Modernizr.js
Tested with: jQuery 1.8.3 and Modernizr 2.6.2
