# Medics Academy - Course widgets instructions

![alt text](http://i63.tinypic.com/esjh4m.png)



## Purpose:
This document will give you a step-by-step guide on how to insert a course card widget on your website.
This allows you to place Medics.Academy content easily into your web presence so that you can embed our content in a variety of scenarios, such as:

1. Reference your cards in a Blog and or page article
2. On the front page of your site, to help you maximise sales or sign ups
   
## Features:
Next features will arrive soon!
   - [x] _Include a discount code_
   

## How to do it?

1) Place the following _<script>_ near the end of your pages, right before the closing </body> tag, to enable them. 

```javascript
    <script>
        (function (w, d, s, o, f, js, fjs) {
            console.log(w);
            w['MedicsAcademySalesWidget'] = o;
            w[o] = w[o] || function () {
                (w[o].q = w[o].q || []).push(arguments)
            };
            js = d.createElement(s);
            fjs = d.getElementsByTagName(s)[0];
            js.id = o;
            js.src = f;
            js.async = true;
            fjs.parentNode.insertBefore(js, fjs);
        }(window, document, 'script', 'ma', 'http://127.0.0.1:8080/ma_widget.js'));
        ma('init');
    </script>
```


### Bundle:

| Tables           |Type       | Are                                                           |
| ---------------- |-----------|---------------------------------------------------------------|
|*data-productId*  |           |                                                 |
| col 2 is         |           |                                                    |
| zebra stripes    |           |                                                      |


: _String || Number_ = Define the product ID of the course
*data-slug*: _String_ = Define the slug of the course, help us to redirect you at the specific page
*data-duration*: _Number_ = Define the period between the payments
```
<div class="medicsacademy-card medicsacademy-card_sm"
     data-productId=14910
     data-slug="pre-hospital-trauma"
     data-duration="3">
</div>
```


For a free bundle the *data-attribute* has not to be specified!

```
<div class="medicsacademy-card medicsacademy-card_sm"
     data-productId=16109
     data-slug="the-medics-academy-global-health-bundle">
</div>

```

### Course:
```
<!--Course: -->
<div class="medicsacademy-card medicsacademy-card_sm"
     data-productId="229658"></div>
```


![alt text](http://i64.tinypic.com/rlb8zd.png)

3) On the right side, you can see the result (as shown below):

![alt text](http://i67.tinypic.com/2iuswb4.png)

4) To get the code up and running on your website, simply copy the <script></script> tag and everything that is inside it (as shown below) and paste it within your website’s html <head></head> tags;

![alt text](http://i68.tinypic.com/30rry91.png)

5) Once this is done, copy the actual card element and paste it anywhere you want the card to show on your website. 

   The card can come in two different sizes, choose the one that suits you best:
   
   #### Small card
   
   ![alt text](http://i63.tinypic.com/2ah8xft.png)
   
   #### Large card
   
   ![alt text](http://i63.tinypic.com/245wkyt.png)
   
6) Now, you should be all set and see the course card widget implemented on your website.
