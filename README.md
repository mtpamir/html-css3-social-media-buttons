# HTML CSS3 Social Media Buttons

This is a repo for a very simple HTML CSS3 Social Media Buttons.

Social Media Buttons are a regular buttons for the websites now a days. So, I made it very simple. 

There are three different styles. 
1. Square Border (Default)
2. Rounded Border
3. Circle Border



### Square Border 

#### CSS

```
.social-bordered{
  height: 50px;
  width: 50px;
  line-height:50px;
  border: 1px solid;
  text-align: center;
}
```
#### Usage
```
<i class="fa fa-facebook social-bordered"></i>
```


### Rounded Border 

#### CSS

```
.rounded-border{
  border-radius: .5rem;
}
```
#### USage
```
<i class="fa fa-facebook social-bordered rounded-border"></i>
```

### Circle Border 

#### CSS

```
.circle-border{
  border-radius: 50%;
}
```
#### Usage
```
<i class="fa fa-facebook social-bordered circle-border"></i>
```

You can simply add as many social icons as you need. You can get social colors from [Meterial UI](https://www.materialui.co/socialcolors "Social Colors").

### Example Social Icon (FontAwsome Facebook icon)

```
/* facebook */
a .fa-facebook.social-bordered, .fa-facebook.social-bordered{
     border-color: #3b5999;
     color: #3b5999;
     background-color: rgba(59,89,153,0);
     -webkit-transition: color .7s, background-color .7s;
     transition: color .7s, background-color .7s;
}
 a .fa-facebook.social-bordered:hover, .fa-facebook.social-bordered:hover{
     color: #fff;
     background-color: #3b5999;
}
```
