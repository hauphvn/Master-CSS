# Jack's Blog

1. CSS selector:

    ```css
    p{
    /*select all p element*/
    }
    ```
    
    ```css
    #myId{
    /*select by element ID*/
    }
    ```
    
    ```css
    .myclassname{
    /*select by class name*/
    }
    ```
    
    ```css
    h1,h2,h3, .myclass{
    /*select a group*/
    }
    ```

2. Styling text:
    - color:#DDD
    - text-align: center|right|left|justify
    - text-decoration: none|underline|overline|line-through
    - text-transform: uppercase|lowercase|capitalize
    - text-indent: 10px
    - letter-spacing: 5px
    - word-spacing: 10px
    - line-height: 1.2 // a number
    - text-shadow: x y color blur

3. Custom fonts
    - From [google font](https://fonts.google.com/)
    - Chose a font and adding into header tag ``<link href="https://fonts.googleapis.com/css?family=Roboto&display=swap" rel="stylesheet">``, in the case I choose Roboto font.  
    - In other the way, adding into css file: ``@import url('https://fonts.googleapis.com/css?family=Roboto&display=swap');``  
    - Using: 
   ```
    h1{
       font-family: font1, font2, font3;
       font-style: normal| italic;
       font-size: 18px; 
       /*default is 16px;*/
       font-weight: normal|bold|400|600|700|800;
    }
    ```
    
4. Install npm live server (option)
    - To make coding faster.  
    - Install: ``npm install -g live-server``  
    - Using: run ``$ live server``
    
5. Padding
    - padding: top right bottom left;
    - padding: top (left,right) bottom;
    - padding: (top,bottom) (left,right);
    - padding: all;
6. Margin:
    - Using is similar to Padding.  
7. Border:
    - border: size style color;
    - border-left-width: 10px;
    - border-width: top, right, bottom, left;(similar the padding)
    - border-left-style: solid;
    - border-left-color: red;
    - border-radius: 5px; (sự bo tròn các góc)
8. Background-color:
    - background-color: color;
    - background-color: transparent;
    - background-color: gradient; You can use any website with keyword ``background gradient generator`` to get a code.  
9. background-image: 
    - type pattern: repeat image
        - background-image: url(./yyy/zzz.jpg);
        - background-size: 
        - background-repeat: repeat|no-repeat;
    - type normal image:
        - background-image: url();
        - background-size: cover|contain;
        - background-position: x y | center
    - type fixed: image không chạy theo khung chứa(div)
        - background-attachment: fixed;
        
10. icons:
    - Ref: [Font Awesome](https://fontawesome.com/)
    - Ref: [Google Material icon](http://google.github.io/material-design-icons/)
    
11. link:
    - States:
        - ``a:link {code css}`` a new link, it is not clicked
        - ``a:visited {code css}`` it was clicked
        - ``a:hover {code css}`` it was applied when user drag on mouse
        - ``a:active {code css}`` when user drag into object and clicked but don't finished action click.
    
12. combinator
    - ``.classParent > .classChild {code css}`` 1 level 
    - ``.classParent .classChild + .classSiblings {code css}`` tìm trong class cha những class anh em của class Child.  
    - ``.classParent .classChild ~ .anyClass {code css}`` tìm trong class cha nhưng class anh em của class Child mà có tên là anyClass.    
     