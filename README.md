# hello-world
hello world

$('.list li').each(function(i, ele) { 
    console.log(i, ele); 
    // console.log(this == ele); // true 
    $(this).html(i); 
    if ($(this).attr('data-item') == 'do') { 
        $(this).html('data-item: do'); 
    }; 
}) 
