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
