# Dom Manipulation Assignment

1. Webiste Name: [Dev To](https://dev.to/)

### Topics

    - Query Selctory, Inner HTML

### Sample Image

![Sample One](./Pic1.png)

### Tasks

        Target the Top description div and change the DEV Community to <Your_Name> and description to your passion

### Output

![Output](./devcommunity.png)

### Code For OutPut

     var e = document.querySelector('.crayons-card .crayons-subtitle-2').innerHTML="Ved Dadhich";

     var d = document.querySelector('.crayons-card p').innerHTML="I like to Code";

2. Webiste Name: [Oppo](https://www.oppo.com/in/)

### Topics

          querySelector,style,color

### Sample Image

![Sample One](./oppo1.png)

### Tasks

      Change the description colour black to orange

### Output

![Output](./oppo.png)

### Code For OutPut

     var e = document.querySelector('.product-card-content .narrow .item .desc').style.color="red";

3. Webiste Name: [Canon](https://in.canon/)

### Topics

          querySelector,src

### Sample Image

![Sample One](./Pic36.png)

### Tasks

    extract the canon logo

### Output

![Output](./canon.png)

### Code For OutPut

     var e = document.querySelector('.navbar-header .navbar-brand .logo').getAttribute('src');
     console.log(e);

4. Webiste Name: [Philips](https://www.philips.co.in/)

### Topics

     querySelector,style,backgroundcolor

### Sample Image

![Sample One](./Pic34.png)

### Tasks

    change the background colour blue to orange

### Output

![Output](./philips.png)

### Code For OutPut

        var e = document.querySelector('.p-footer .p-grid').style.backgroundColor="orange";

5. Webiste Name: [Sony](https://www.sony.co.in/)

### Topics

    querySelector,innerHTMl

### Sample Image

![Sample One](./Pic33.png)

### Tasks

     change the button text To current Date.

### Output

![Output](./sony.png)

### Code For OutPut

       var e = document.querySelector('.mlp-collapse-content .btn-container').innerHTML= new Date();

6. Webiste Name: [Vercel](https://vercel.com/)

### Topics

     querySelector,innerHTMl

### Sample Image

![Sample One](./Pic30.png)

### Tasks

      change the heading “Start with the developer” to “Start with Scratch”

### Output

![Output](./varcel.png)

### Code For OutPut

       var e = document.querySelector('.jsx-499702677 .section-title_title__VEDfK').innerHTML="Start with Scratch";
