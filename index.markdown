---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<html>
 <head>
    <style>
    body {
  display: grid;
  padding: 2rem;
  grid-template-columns: 300px 1fr;
  gap: 1rem;
  align-items: center;
  max-width: 800px;
  margin: 0 auto;
  font: 500 100%/1.5 system-ui;
}
img {
  max-width: 100%;
  height: auto;
}
      
    @media (max-width: 650px) {
  body {
    display: block;
    font-size: 80%;
  }
  p {
    position: relative;
    margin: -3rem 0 2rem 1rem;
    padding: 1rem;
    background: rgba(white, 0.8);
  }
}
    </style>
 </head>
 <body>
    <div class="row">
        <div class="column" style="background-color:#FFFFFF;">
            <img src="_assets/Profile.jpeg">
        </div>
        <div class="column" style="background-color:#FFFFFF;">
            <h2>Welcome!</h2>
            <p>Something about myself</p>
        </div>
    </div>
 </body>
</html>
