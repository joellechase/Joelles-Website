$(document).ready(function(){   
$("#readmore").click(function(){
$(".hidden").fadeIn();
$("#readmore").fadeOut();
});
$("#readless").click(function(){
    $("#readmore").fadeIn();
});
});

$(document).ready(function(){
    $("form").submit(function(){
    
      if($("#name").val().length===0){
        alert ("Name is required");
        return false;
      }
      
      return true;
      
    })
  });
  $(document).ready(function(){
      $("button").click(function(){
          var cat=$.get("https://api.thecatapi.com/v1/images/search");
          cat.done(function(response){
              $("img").attr("scr", response.message);
          })
      })
    })