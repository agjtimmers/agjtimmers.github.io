---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<html>
 <head>
    <style>
    {
        box-sizing: border-box;
    }
    /* Set additional styling options for the columns*/
    .column {
    float: left;
    width: 50%;
    }

    .row:after {
    content: "";
    display: table;
    clear: both;
    }
    
    .container {
        width: 50%;
        height: 300px;
    }
      
    img {
        width: 100%;
        height: 100%;
        object-fit: cover;
      }
    </style>
 </head>
 <body>
    <div class="row">
        <div class="column" style="background-color:#FFFFFF;">
            <img src="_assets/Profile.jpeg" />
        </div>
        <div class="column" style="background-color:#FFFFFF;">
            <h2>Welcome!</h2>
            <p>Something about myself</p>
        </div>
    </div>
 </body>
</html>
