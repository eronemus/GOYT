$('#product1').hide();

$('#img1').hover(function() {
    $('#product1').toggle();
    $('#product2, #product3, #product4, #product5, #product6').hide();
});

$('#button1').click(function() {
    $('#product1').show();
    $('#product2, #product3, #product4, #product5, #product6').hide();
})


$('#product2').hide();

$('#img2').hover(function() {
    $('#product2').toggle();
    $('#product1, #product3, #product4, #product5, #product6').hide();
});

$('#button2').click(function() {
    $('#product2').show();
    $('#product1, #product3, #product4, #product5, #product6').hide();
})



$('#product3').hide();

$('#img3').hover(function() {
    $('#product3').toggle();
    $('#product1, #product2, #product4, #product5, #product6').hide();
});

$('#button3').click(function() {
    $('#product3').show();
    $('#product1, #product2, #product4, #product5, #product6').hide();
})



$('#product4').hide();

$('#img4').hover(function() {
    $('#product4').toggle();
     $('#product1, #product2, #product3, #product5, #product6').hide();
});

$('#button4').click(function() {
    $('#product4').show();
    $('#product1, #product2, #product3, #product5, #product6').hide();
})

$('#product5').hide();

$('#img5').hover(function() {
    $('#product5').toggle();
    $('#product1, #product2, #product3, #product4, #product6').hide();
});

$('#button5').click(function() {
    $('#product5').show();
    $('#product1, #product2, #product3, #product4, #product6').hide();
})

$('#product6').hide();

$('#img6').hover(function() {
    $('#product6').toggle();
    $('#product1, #product2, #product3, #product4, #product5').hide();
});

$('#button6').click(function() {
    $('#product6').show();
    $('#product1, #product2, #product3, #product4, #product5').hide();
})

$("#hbtn").click(function(){
    alert("$1,599.00");
});

$("#hbtn2").click(function(){
    alert("$1,599.00");
});

$("#hbtn3").click(function(){
    alert("$1,599.00");
});

$("#hbtn4").click(function(){
    alert("$1,599.00");
});

$("#hbtn5").click(function(){
    alert("$1,599.00");
});

$("#hbtn6").click(function(){
    alert("$1,599.00");
});