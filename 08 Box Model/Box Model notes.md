# Box Model & Units notes

I will learn about 
- Width & Height
- Border
- Padding
- Margin
- Border-Radius
- Display Property
- Units


## Width & Height

Everything in CSS is a box . They each have properties like width and height

i.e.
    div{
        width:200px;
        height:300px;

## Border
Borders have a variety of properties including thickness, color, style and radius
i.e.
#two{
    width:400px;
    height:300px;
    border:2px solid blue;
}
 
 You can also set left/right colors
 i.e.
#two{
    width:400px;
    height:300px;
    border:2px solid blue;
    border-top:4px dashed red;
}

## Padding
i.e.
#one{
    width:400px;
    height:300px;
    padding:20px;
    border:5px dotted purple;
}

## Margin
i.e.
#three{
    width:400px;
    height:300px;
    border:2px dashed red;
    margin:50px;
}

## Border-Radius
Radius rounds borders. 50% make a circle. You can also round 1,2,3 or even 4 corners


#three{
    width:400px;
    height:300px;
    border:2px dashed red;
    border-radius:25%;
    margin:50px;
    Padding:30px;
}

## Display Property
Some elements are _**inline**_ and some are _**block**_
- **_Inline_** elements are on one side. They ignore width/margin though
- **_block_** elements are above one another

There are more possibilities though. 

Inline-block combines side by side elements with all properties
i.e.   
    display:inline-block;


## Units