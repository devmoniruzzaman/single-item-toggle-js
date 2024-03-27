jQuery( ".adventures-slider .et_pb_module_header" ).click(function() {
      jQuery(this).toggleClass("toggle-item");
      jQuery(this).next(".dsm_card_carousel_child_description").slideToggle("slow");
      
    });
