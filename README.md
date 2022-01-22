# Kiryl Savich's CV

##(https://immim.github.io/CV_CS50/)



## CS50
>This was my final project for CS50
>CS, web development, CS50
## Features
- [Bootstrap](https://getbootstrap.com/)
- [SASS](https://sass-lang.com/)

I've used Bootstrap framework for some icons
Also used SASS Preproc for CSS writing


## Explaining the project and the database
My final project is a website that introduce myself as Hi-Tech student


### Index.html:
- AS well as I dont know how to fast and beautiful generate HTML in JS. it was written manually.

- Used some HTML5 features like <nav> and <footer>

### Assets.

-Many time goes to find exactly THAT icon you want to use. all of them are Open License.

## CSS styling:

-Most interesting was in creating burger menu. as 3 spans

code example:

    .burgerbutton{
        width: 33px;
        height: 27px;
        opacity: 0;
        display: block;
        z-index: 2;
        cursor: pointer;
        &:checked{
            ~.bur{     //all spans
                opacity: 1;
                transform: rotate(45deg) translate(-2px, -1px);
                background: darkgrey;
                &:nth-last-child(3){  //middle one
                    opacity: 0;
                    transform: rotate(0deg);
                }
                &:nth-last-child(2){  //last one
                    transform: rotate(-45deg) translate(0, -1px);
                }
            }

            ~ #menu li:first-child{
                transition: opacity 0.25s ease;
                opacity: 1;
            }
            ~ #menu li:nth-child(2){
                transition: opacity 0.5s ease;
                opacity: 1;
            }
            ~ #menu li:nth-child(3){
                transition: opacity 0.75s ease;
                opacity: 1;
            }
            ~ #menu li:nth-child(4){
                transition: opacity 1s ease;
                opacity: 1;
            }

            ~ #menu a:hover{
                transition: color 0.5s ease;
                color: grey;

            }
        }
    }


Also making nav anchors for edu was my pain. as I done it with ***sticky***

    #circle1{
        position: sticky;
        display: inline-block;
        height: 36px;
        margin-top: 220px;
        margin-bottom: 240px;
        left: calc(50% - 13px);
        top: 50px;
        z-index: 1000;
        text-decoration: none;
        color: black;
        img{
            width: 36px;
        }
    }


## Video on YouTube
For the CS50 final project you have to make a video showning your project,
[My Final Project presentation](https://youtu.be/PxkKqh-pt9M)

## How fast I've finished course:

- It took 3 years to reach Final project. work and univercity eats so much time.

- Where I get CS50 course?
https://cs50.harvard.edu/x/2022/
