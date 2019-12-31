# scrollAnimation
when user scroll page then animation is active and do work..........so implement and run
  
  all links file for this animation----
  
    <!--animate.css-->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/3.7.2/animate.min.css">


     <!-- jQuery library -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
    
    
    jquery code-----for basic animation---
    
                                            
<script>
 
 $(document).ready(function(){
     $(window).scroll(function(){
         var positionTop = $(document).scrollTop();
         console.log(positionTop);

        if((positionTop>608) && (positionTop<1006)){
            $('#card-one').addClass('animated bounceInLeft  slow');
            $('#card-two').addClass('animated bounceInUp  slow');
            $('#card-three').addClass('animated bounceInRight  slow');

        }

        if((positionTop>1390) && (positionTop<1482)){
            $('#card-one-one').addClass('animated bounceInLeft  slow');
            $('#card-two-two').addClass('animated bounceInUp  slow');
            $('#card-three-three').addClass('animated bounceInRight  slow');

        }

        if((positionTop>88) && (positionTop<541)){
            $('#heading').addClass('animated rollIn  slow');
            $('#paragraph').addClass('animated rollIn  slow');
        
        }

        if((positionTop>1039) && (positionTop<1209)){
            $('#sec-heading').addClass('animated slideInLeft  slow');
            $('#sec-para').addClass('animated slideInRight  slow');
            $('#sec-btn').addClass('animated slideInDown  slow');
        
        }

     })
 })

</script>
