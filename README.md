# Candy-Museum
static webpage illustrating multiple bootstrap4 functionalities
>Tech Stack followed:
* FrontEnd: HTML,CSS
* Framework: Bootstrap4
  * text-center 
  * mt-5 
  * d-none d-lg-block d-lg-inline
  * order-md-1 order-2
  
* to fill the navbar while scrolling
```javascript
<script>
        $(function () {
            $(document).scroll(function () {
                var $nav = $("#mainNav");
                $nav.toggleClass("scrolled", $(this).scrollTop() > $nav.height());
            });
        });
</script>
```
* to update the size of text as per screen size
```css
@media (max-width: 1200px){
	.headingGroup h1{
	font-weight: 100;
	font-size: 3rem;
}
}
```

 
  
  ## Screenshot ##
  ![Page ScreenShot](/candyMuseumImage.png)

