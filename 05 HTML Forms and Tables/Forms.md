**Forms**

Input id the most common form tsg, it does not have a forms tag

The type specifies the type of input , they can be : 

    - Text
    - Password
    - Color
    - File
    - Number
    - Radio
    - Checkbox

This is a small selection . Most tags have a palceholder tag, which lets you put greyed out suggested input.

Label

Label is used to attach labels to a controls.Input contains a for to match an inputs id
.
**Buttons**

Buttons have 2 tags, the button text goes inbetween them

Buttons in a form will by default submit. To not submite, include type="button"

**Name attribute**

any inputs with a name attribute are added to the send URL. All inputs should be named

**Checkbox**

<input type="checkbox" name="cb>

**Radio Buttons**

        <label for="yes">Yes</label>
        <input type="radio" id="yes" name="TandC">
        <label for="no">No</label>
        <input type="radio" id="no" name="TandC">

**DropDown**

        <label for="login">Where do you want to log in </label>
        <select name="login" id="where">
            <option value="llama">llama.com</option>
            <option value="Google">Google</option>
            <option value="FB">FB</option>
        </select>

**Range**

        <label for="feel"></label>
        <input type="range" name="feeling" id="feel" min="0" max="5" value="4">

**textarea**

Text area is not an input, it is started by <textarea>

you can set rows by <textarea rows="10">

# Validations

MOst validations are in JS, but HTML has a few

 - required if the word required is in a tag, then the system will require data
 - min/max length lets you specify text length minlength="6" maxlength="12"
 - email type checks for an @ sign
 - url looks for a 
 - tel checks for phone  numbers





