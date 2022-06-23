[![Badge site](https://img.shields.io/badge/@media-responsive-blueviolet.svg)](https://getbootstrap.com/docs/4.3/layout/overview/)

Страницы, адаптированные для просмотра на разных типах устройств, должны содержать в разделе `<head>` метатег `viewport`.

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

Так, `max-width: 576px` означает, что ширина окна браузера меньше 576 пикселов, а `min-width: 1200px`, наоборот, сообщает, что ширина окна больше 1200 пикселов.

## min
```css
//Extra small devices (portrait phones, less than 576px) 
//No media query for `xs` since this is the default in Bootstrap


/*Small devices (landscape phones, 576px and up) */
@media (min-width: 576px) { ... } 
/*Medium devices (tablets, 768px and up) */
@media (min-width: 768px) { ... } 
/*Large devices (desktops, 992px and up) */
@media (min-width: 992px) { ... } 
/*Extra large devices (large desktops, 1200px and up) */
@media (min-width: 1200px) { ... }
```
## max
```css
/*Extra small devices (portrait phones, less than 576px)*/
 @media (max-width: 575.98px) { ... } 
/* Small devices (landscape phones, less than 768px)*/
 @media (max-width: 767.98px) { ... }
/* Medium devices (tablets, less than 992px)*/
 @media (max-width: 991.98px) { ... } 
/* Large devices (desktops, less than 1200px)*/
 @media (max-width: 1199.98px) { ... } 
/* Extra large devices (large desktops) */

```
## min and max
```css
/*Extra small devices (portrait phones, less than 576px)*/
 @media (max-width: 575.98px) { ... } 
/* Small devices (landscape phones, 576px and up)*/
 @media (min-width: 576px) and (max-width: 767.98px) { ... } 
/* Medium devices (tablets, 768px and up)*/
 @media (min-width: 768px) and (max-width: 991.98px) { ... } 
/* Large devices (desktops, 992px and up) */
@media (min-width: 992px) and (max-width: 1199.98px) { ... }
/* Extra large devices (large desktops, 1200px and up) */
@media (min-width: 1200px) { ... }
```

<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto+Flex:opsz,wght@8..144,100;8..144,200;8..144,300;8..144,400;8..144,500;8..144,600;8..144,700;8..144,800;8..144,900;8..144,1000&display=swap'); 

body{
    width: 90%;
    max-width: 800px;
    box-sizing: border-box;
    margin: 0 auto;
    font-size: 18px;
    color: #444;
    font-family: 'Roboto Flex', sans-serif;
}
h1,h2,h3,h4{ 
    color:#354361; 
    
}

a{
    color:#034ad8;
    text-decoration: none;
    font-weight: 500;
            
        }


</style>

