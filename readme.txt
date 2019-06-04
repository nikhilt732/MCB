JUST CLONE THE FILE ON THE DESKTOP AND OPEN YOUR BROWSER AND TYPE file:///C:/Users/MUJ/Desktop/website/index.html#fff
TO RUN THE CODE.
I HAVE USED THE LOGO AND CONTENT FROM MY COLLEGE BUDDY.

IF YOU WANT YOU CAN EVEN ADD AN SLIDE SHOW BY USING THE FOLLOWING CODE.
<body>
....
<section>
  <img class="mySlides" src="4.jpeg"
  style="width:100%">
  <img class="mySlides" src="2.jpeg"
  style="width:100%">
  <img class="mySlides" src="3.jpeg"
  style="width:100%">
</section>
<script>

var myIndex = 0;
carousel();

function carousel() {
  var i;
  var x = document.getElementsByClassName("mySlides");
  for (i = 0; i < x.length; i++) {
    x[i].style.display = "none";
  }
  myIndex++;
  if (myIndex > x.length) {myIndex = 1}
  x[myIndex-1].style.display = "block";
  setTimeout(carousel, 3000);
}
</script>

</body>

thank you and you ask your doubts 