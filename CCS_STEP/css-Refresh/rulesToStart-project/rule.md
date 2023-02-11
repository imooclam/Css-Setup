# Rule to start project

![ how browser work!](../img/../../img/rule/r1.png   " website work")
![ how browser work!](../img/../../img/rule/r2.png   " website work")
![ how browser work!](../img/../../img/rule/r3.png   " website work")
![ how browser work!](../img/../../img/rule/r4.png   " website work")
![ how browser work!](../img/../../img/rule/r5.png   " website work")
![ how browser work!](../img/../../img/rule/r6.png   " website work")
![ how browser work!](../img/../../img/rule/r7.png   " website work")
![ how browser work!](../img/../../img/rule/r8.png   " website work")
![ how browser work!](../img/../../img/rule/r9.png   " website work")
![ how browser work!](../img/../../img/rule/r10.png   " website work")
![ how browser work!](../img/../../img/rule/r11.png   " website work")
![ how browser work!](../img/../../img/rule/r12.png   " website work")
![ how browser work!](../img/../../img/rule/r13.png   " website work")
![ how browser work!](../img/../../img/rule/r14.png   " website work")
![ how browser work!](../img/../../img/rule/r15.png   " website work")

 we have many note here:

- frist we always use grid system as much we can

## hero section

- he focus  frist into grid
 then he want to make width 1300px so that will help  the contant in img not stick into edages then he center it by margin auto

- img=> with %

- any header he focus on 6 major thing

  - font-size
  - color
  - font-weight
  - line-height
  - margin-bottom
  - letter-spacing
  
- any paragraph he focus on 3 thing

  - font-size
  - font-weight
  - line-height
  - color
  - margin-bottom

![ how browser work!](../img/../../img/rule/r16.png   " website work")
![ how browser work!](../img/../../img/rule/r17.png   " website work")
![ how browser work!](../img/../../img/rule/r18.png   " website work")
![ how browser work!](../img/../../img/rule/r19.png   " website work")
![ how browser work!](../img/../../img/rule/r20.png   " website work")
![ how browser work!](../img/../../img/rule/r21.png   " website work")

### How to make navigation

- we frist  creat btn on for close and second for menu
- we make this btn Display non in css and display block  in media query max-width 900
- we transfer menu list  we make nav is postion absolute we create anew feature background of nav
- we make ul flex-direction column
- we must hide the nav menu list and  if we ant to make animation we cant go with display none so we will use 3 thing we want to close it
  
``` css
opacity:0;
pointer-events:none;
visibility:hidden;

```

- we make nav open

``` css
opacity:1;
pointer-events:auto;
visibility:visible  ;

```

also nav open when we open   we should have close icon so we select close icon and make it display block and display none in css

![ how browser work!](../img/../../img/rule/nav1.png   " website work")
![ how browser work!](../img/../../img/rule/nav2.png   " website work")
![ how browser work!](../img/../../img/rule/nav3.png   " website work")
![ how browser work!](../img/../../img/rule/nav5.png   " website work")
![ how browser work!](../img/../../img/rule/nav6.png   " website work")
![ how browser work!](../img/../../img/rule/nav7.png   " website work")
![ how browser work!](../img/../../img/rule/nav8.png   " website work")
![ how browser work!](../img/../../img/rule/nav9.png   " website work")

## btn create a btn |"| button=> for action

- btn:link&&btn:visted is togather
- btn:hover&&btn:active is togather
- we focus on btn on 8 major thing
  - color
  - background
  - padding
  - display
  - curser
  - transition
  - border radius
  - font-size
  - letter-spacing

**Note :** Dont ever use border in hover its bad thing cuz the screen will pop up and scale so we always use box-Shadow instend

## img

- if you want to make img more  rounded by border radius we use width and height  together with same value
so thats because some browser will complain if you dont provide both likes safari

![ how browser work!](../img/../../img/rule/r22.png   " website work")
![ how browser work!](../img/../../img/rule/r23.png   " website work")
![ how browser work!](../img/../../img/rule/r24.png   " website work")

**Note and very Important:**

- Dont forget you always  color contrast checker between  text and bg
  
 you may also break rules
if we have larg text and bold

![ how browser work!](../img/../../img/rule/ru1.png   " website work")
![ how browser work!](../img/../../img/rule/ru2.png   " website work")

## header

- frist
  
```Html
<header>
  <logo>
    <nav>
      <header>
        
        ```

```Css
  Header : flex
  js /al-item
  background
   this is most importatant thing when we put headerCss
   we make  fixed height 
   so it 9.6rem
   height :9.6rem
  

```

 ![ how browser work!](../img/../../img/rule/ru4.png   " website work")
 ![ how browser work!](../img/../../img/rule/ru3.png   " website work")

- we have bad problem
it comming from padding

 ![ how browser work!](../img/../../img/rule/ru5.png   " website work")
 ![ how browser work!](../img/../../img/rule/ru6.png   " website work")

### create Navigation

 ![ how browser work!](../img/../../img/rule/ru7.png   " website work")

- He love that hero section more wider than other section

1300 for hero secion and  1200 for rest of hero

## codes to make  some thing gray

 ![ how browser work!](../img/../../img/rule/ru8.png   " website work")
 ![ how browser work!](../img/../../img/rule/ru9.png   " website work")
 ![ how browser work!](../img/../../img/rule/ru10.png   " website work")
 ![ how browser work!](../img/../../img/rule/ru11.png   " website work")

**Note** => every time we start ne section

```Css
.newSection{
  
  padding: 9.6rem 0;

}

```

## card

  ![ how browser work!](../img/../../img/rule/im1.png   " website work")
  ![ how browser work!](../img/../../img/rule/im2.png   " website work")
  ![ how browser work!](../img/../../img/rule/im3.png   " website work")

  ![ how browser work!](../img/../../img/rule/ru12.png   " website work")

  ![ how browser work!](../img/../../img/rule/ru13.png   " website work")
  ![ how browser work!](../img/../../img/rule/ru14.png   " website work")
  ![ how browser work!](../img/../../img/rule/ru15.png   " website work")
  ![ how browser work!](../img/../../img/rule/ru16.png   " website work")

img = width 100%

## testimoial

 we can set grid here as that

```Css
grid-templete-column: 55fr 45fr
```

  ![ how browser work!](../img/../../img/rule/te1.png   " website work")
  ![ how browser work!](../img/../../img/rule/te2.png   " website work")
  ![ how browser work!](../img/../../img/rule/te3.png   " website work")
  ![ how browser work!](../img/../../img/rule/te4.png   " website work")
  ![ how browser work!](../img/../../img/rule/te5.png   " website work")

- look at text and saw the setup

## price Card

We make this column less wider we use width 75% and  justify self

We want the user to select this on write
Its visual hirchey
So we should de emphsize this one on left
 This is one here we well create to improve hirchey

![ how browser work!](../img/../../img/rule/pr1.png   " website work")
![ how browser work!](../img/../../img/rule/pr2.png   " website work")

![ how browser work!](../img/../../img/rule/pr3.png   " website work")
![ how browser work!](../img/../../img/rule/pr4.png   " website work")
![ how browser work!](../img/../../img/rule/pr5.png   " website work")
![ how browser work!](../img/../../img/rule/pr6.png   " website work")
![ how browser work!](../img/../../img/rule/pr7.png   " website work")

## cta

 very important of you make back ground img you should set attribute like role in html

```Html
role="img"

aria-label="Women  enjoying Food"

```

**Form need to inherit font family**
**Color inherit it mean its automatically inheret from parent**

outline focus problem

we fixed by **box-shadow**

![ how browser work!](../img/../../img/cssImg/cta1.png   " website work")
![ how browser work!](../img/../../img/cssImg/cta2.png   " website work")
![ how browser work!](../img/../../img/cssImg/cta3.png   " website work")
![ how browser work!](../img/../../img/cssImg/cta4.png   " website work")
![ how browser work!](../img/../../img/cssImg/ct5.png   " website work")
![ how browser work!](../img/../../img/cssImg/cta6.png   " website work")
![ how browser work!](../img/../../img/cssImg/cta7.png   " website work")
![ how browser work!](../img/../../img/cssImg/cta8.png   " website work")
![ how browser work!](../img/../../img/cssImg/cta9.png   " website work")
![ how browser work!](../img/../../img/cssImg/cta10.png   " website work")
![ how browser work!](../img/../../img/cssImg/cta11.png   " website work")
![ how browser work!](../img/../../img/cssImg/cta12.png   " website work")
![ how browser work!](../img/../../img/cssImg/cta13.png   " website work")
![ how browser work!](../img/../../img/

## Footer

we use grid 1.5fr 1.5fr 1fr 1fr 1fr

![ how browser work!](../img/../../img/rule/footer1.png  " website work")
![ how browser work!](../img/../../img/rule/footer2.png  " website work")
![ how browser work!](../img/../../img/rule/footer3.png  " website work")
![ how browser work!](../img/../../img/rule/footer4.png  " website work")
