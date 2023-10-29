<!-- # Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

## Colors

### Primary

- Very dark blue (main background): 
- Dark desaturated blue (card background):  v
- Soft violet (accent): 

### Neutral

- White (main heading, stats): hsl(0, 0%, 100%)
- Slightly transparent white (main paragraph): hsla(0, 0%, 100%, 0.75)
- Slightly transparent white (stat headings): hsla(0, 0%, 100%, 0.6)

## Typography

### Body Copy

- Font size: 15px

### Font

- Family: [Inter](https://fonts.google.com/specimen/Inter)
- Weights: 400, 700

- Family: [Lexend Deca](https://fonts.google.com/specimen/Lexend+Deca)
- Weights: 400








<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <!-- displays site properly based on user's device -->
<!-- 
    <link
      rel="icon"
      type="image/png"
      sizes="32x32"
      href="./images/favicon-32x32.png"
    />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Lexend+Deca&display=swap"
      rel="stylesheet"
    />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Inter&display=swap"
      rel="stylesheet"
    />

    <title>Frontend Mentor | Stats preview card component</title>
    <link rel="stylesheet" href="style.css" />
    

    <!-- Feel free to remove these styles or customise in your own stylesheet 👍 -->
  </head>
  <body>
    <div class="hero-card">
      <article class="section">
        <h1>Get <span id="insights">insights </span>that help your business grow.</h1>
        <p class="para">
          Discover the benefits of data analytics and make better decisions
          regarding revenue, customer experience, and overall efficiency.
        </p>
        <div class="footer">
          <p>10k+ <span class="x">companies</span></p>
          <p>314 <span class="x">templates</span></p>
          <p>12m+ <span class="x">queries</span></p>
        </div>
      </article>
      <article>
        <img src="images/image-header-desktop.jpg" alt="an office" />
        <!-- <div class="overlay"></div> -->
      </article>
    </div>
  </body> -->

  <!-- 
 <style>
    .attribution { font-size: 11px; text-align: center; }
    .attribution a { color: hsl(228, 45%, 44%); }
  </style> -->
</html>





::after::before {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.hero-card {
  display: flex;
  min-height: 100vh;
  min-width: 20vw;
  margin: 130px 100px 130px 100px;
  padding: 10px;
  background-color: hsl(233, 47%, 7%);
  justify-content: center;
  align-items: center;
}

.section {
  background-color: hsl(244, 38%, 16%);
  padding: 29px;
  justify-content: center;
  flex-direction: column;
  height: 210px;
  width: 300px;
  border-top-left-radius: 10px;
  border-bottom-left-radius: 10px;
}
img {
  /* color: hsl(277, 64%, 61%); */

  background-size: 5px;
  background-repeat: no-repeat;
  object-fit: contain;
  padding: inline 150px;
  padding-block: 60px;
  background-blend-mode: multiply;
  justify-content: center;
  height: 300px;
  width: 325px;
  display: flex;
  border-top-right-radius: 10px;
  border-bottom-right-radius: 10px;
  /* position: relative;
  z-index: 1; */
}

/* .overlay {
  background-color: hsl(277, 64%, 61%);
  position: ;
  top: 0;
  left: 0;
  width: 20%;
  height: 20%;
} */
p {
  color: white;
  font-family: "Inter", sans-serif;
  font-size: medium;
  font-weight: 600;
  text-align: center;
}
.para {
  font-family: "Lexend Deca", sans-serif;
  font-weight: lighter;
  padding-right: 60px;
  color: white;
  opacity: calc(0.5);
  line-height: 1.5;
  padding-bottom: 15px;
  font-size: 10px;
  text-align: left;
}
.x {
  text-align: center;
  font-size: 8px;
  color: beige;
  opacity: 0.5;
  padding-bottom: 20px;
  font-weight: 100;
}
h1 {
  color: aliceblue;
  padding-right: 2px;
  font-weight: 600;
  text-align: left;
  font-family: "Inter", sans-serif;
}
#insights {
  color: hsl(277, 64%, 61%);
}

.footer {
  display: flex;
  gap: 50px;
  padding-right: 500px;
  color: aliceblue;
  text-align: left;
  padding-bottom: 90px;
  text-transform: uppercase;
}

/* Small devices (portrait tablets and large phones, 600px and up) */
@media screen and (max-width: 700px) {
  .hero-card {
    flex-direction: column-reverse;
    width: 45%;
    height: 900px;
    gap: none;
    margin-top: 120px;
    flex-wrap: 1;
  }

  .section {
    display: flex;
    gap: none;
    width: 150px;
    min-height: 360px;
    padding: 140px 30px 0px 30px;
    border-radius: 0px 0px 10px 10px;
  }

  img {
    background-size: 5px;
    background-repeat: no-repeat;
    object-fit: contain;
    justify-content: center;
    height: 190px;
    width: 210px;
    display: flex;
    border-top-right-radius: 50px;
    border-top-left-radius: 50px;
  }

  .para {
    line-height: 1.5;
    padding: 15px;
    font-size: 0.7em;
    font-weight: bolder;
    text-align: center;
    justify-self: center;
    padding-top: 120px;
    margin-top: 0;
    margin-bottom: 110px;
  }

  .footer {
    display: grid;
    justify-content: center;
    text-align: center;
    padding-left: 60px;
    padding-bottom: 380px;
  }

  .footer > p {
  }

  h1 {
    text-align: center;
    font-size: 16px;
    padding-top: px;
  }
}
 -->
