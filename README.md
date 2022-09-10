![](https://i.imgur.com/143AeXh.png)
**A minimalistic CSS library for your website with no jQuery depenency**

## Components
- [Introduction](#Introduction)
- [Buttons](#Buttons)
- [Input](#Input)
- [Card](#Card)
- [Avatar](#Avatar)
- [Form](#Form)
- [Margins and Paddings](#margins-and-paddings)
- [Modal](#modal)

## Introduction
Platinum UI has 5 different coloring scheme which are 

- Primary
- Secondary
- Warning
- Error
- Success

## Buttons
Platinum UI currently offers 5 different types of buttons which are

```html
<button class="platinum-btn-primary" >Primary Button</button>
<button class="platinum-btn-secondary">Secondary Button</button>
<button class="platinum-btn-warning">Warning Button</button>
<button class="platinum-btn-error">Error Button</button>
<button class="platinum-btn-success">Success Button</button>
```

![](https://i.imgur.com/FHkHm5x.jpg)

## Input
Platinum UI currently offers 5 different types of input which are

```html
<input class="platinum-input-primary" placeholder="Primary Input"/>
<input class="platinum-input-secondary" placeholder="Secondary Input"/>
<input class="platinum-input-warning" placeholder="Warning Input"/>
<input class="platinum-input-error" placeholder="Error Input"/>
<input class="platinum-input-success" placeholder="Success Input"/>
```

![](https://i.imgur.com/pl1sN6l.jpg)

## Card
Platinum offers simple and easy to create card using *platinum-card* class.

```html
<div class="platinum-card">
    <img src="https://via.placeholder.com/150">
    <p>Hello World!</p>           
</div>  
```

![](https://i.imgur.com/JdE9CfR.jpg)

## Avatar
You can create image avatar easily using *platinum-avatar* class

```html
<img src="https://via.placeholder.com/150" class="platinum-avatar" />
```

![](https://i.imgur.com/MmxdDEU.jpg)

## Form
Platinum takes care of all paddings, margins and responsiveness for you. Use class *platinum-common-form* to add styling to your forms.

```html
<form class="platinum-common-form" style="width: 20%;">
    <label for="name">Name:</label>
    <input class="platinum-input-primary"/>
    <label for="name">Age:</label>
    <input class="platinum-input-primary"/>
    <button type="submit" class="platinum-btn-primary">Submit</button>
</form>
```

![](https://i.imgur.com/RsPRToq.jpg)

## Margins and Paddings
![](https://i.imgur.com/rP31fyZ.png)

## Modal
### Top default modal

```html
<button class="platinum-btn-primary" onclick="document.getElementById('open-confirm').style.display='block';">Open Modal Delete</button>
<div class="platinum-modal" style="display: none;" id="open-confirm">
    <div class="platinum-modal-dialog-sm platinum-dialog-top">
        <p style="font-family: 'Roboto'; font-size: 20px;">Are you sure you want to delete?</p>            
    </div>
</div>
```

### Center modal

```html
<button class="platinum-btn-primary" onclick="document.getElementById('display-info').style.display='block';">Open Modal Info</button>
<div class="platinum-modal" style="display: none;" id="display-info">
    <div class="platinum-modal-dialog-sm platinum-dialog-center">
        <p style="font-family: 'Roboto'; font-size: 20px;">Please restart the website to load new contents!</p>            
    </div>
</div>
```

### Full screen modal

```html
<button class="platinum-btn-primary" onclick="document.getElementById('display-info1').style.display='block';">Open Fullscreen Modal</button>
<div class="platinum-modal" style="display: none;" id="display-info1">
    <div class="platinum-modal-dialog-fullscreen">
        <p style="font-family: 'Roboto'; font-size: 20px;">Please restart the website to load new contents!</p>            
    </div>
</div>
```


