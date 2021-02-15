# CSS Text

I am learning about 
- text-align
- font-weight
- text-decoration
- line-height
- letter-spacing
- font-size
- font


**text-align**
Sets text to be left, right, center or justify.
i.e.
    text-align:center;
    
**font-weight**
Controls boldness of text. 
- This can be done through keywords like bold, bolder, light, lighter
- This can also be done through numbers ( 100 ( very light) -> 900 (very dark))
- Default is 400
i.e.
    font-weight:600;

**text-decoration**
Text decoration provides underline, overline or line-through
i.e. 
    text-decoration:underline;
    text-decoration:underline blue; <- Color can be specified
    text-decoration:underline blue wavy; <- Style too
    text-decoration:none; <- Removes underline ( good for links)
    
**line-height**
This controls the height of a line of text. The space is multiplied by a plain number
i.e.
    line-height:2;
    line-height:50px;
    
**letter-spacing**
This controls spacing in between letters 
i.e.
    letter-spacing:15px;
    
**font-size**
These control the size of your text. You use either relative (em,rem %) and absolute measurements ( px,pt,cm)
i.e.
    font-size:12px;
    font-size:1.2em
    
**font** 
Sets font. Can have a stack ( giving 2nd/3rd choices)
i.e. font-family:Verdana, sans-serif;