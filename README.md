# LearnHTML_CSS

## HTML5
XHTML makes sures it has all the closing tags.
HTML5 is more flexible.
It is more widely used.
- <!DOCTYPE html> It tells that the written markup language is HTML.
- All the tags are enclosed within the <html> tag and it's the building block of html.
- Anything contained inside <head> tag won't be displayed on content area of browser.
    - <meta> tag communicates with both browser and serach engine to provide information about the page. 
    - In meta tags, the three sub parts description, Content-type,viewport (scaling of the webpage)
    - name='description' , content='which is page description'.
    - http-equiv='Content-type' , content='text/html' , charset='utf-8'
        - The http-equiv attribute provides an HTTP header for the info/value of the content attribute.
        - The content attribute gives the value associated with the http-equiv or name attribute.
    - name='viewport' , content='width=device-width, height=device-height, initial-scale=1' 
    - style are located in head-tag. Has one rule Body=>color=>red Ex: ```<style type="text/css">Body{color:'red';}</style>```
    - script are javascript functions, which will be used on html documents.
- <Body> tags are the visible are of the web browser.
  
## HTML TABLE FORMS

```
    <form>
        <table>
                <tr>
                    <td></td>
                </tr>
        </table>
    </form>

```
- Forms are used gather the uout from the users.
- Forms data can be inputted into a database or sent to an email address.
- Form inputs are created in the HTML.
- Data is submitted to a PHP script for the processing.

## IFrame 
- IFrame is HTML document embedded into another HTML document.

```
        <iframe src="http://www.bing.com" width="100%" height="800">
            <p>You browser doesn't support iframe.</p>
        </iframe> <br>
```



## GRID

```
  
  <div style="display:grid;grid-template-columns: 100px 1fr;">
    <div style="background-color: blue;">Anurag Kumar Singh</div>
    <div style="background-color: green;">Software Developer</div>
  </div>
  <div style="display:grid;grid-template-columns: 100px 1fr 1fr 1fr;">
    <div style="background-color: blue;">Anurag </div>
    <div style="background-color: green;">Software Tester</div>
    <div style="background-color: pink;">Software Enginners</div>
    <div 

```
## FLEXBOX
  ```
  <div style="display:flex;flex-direction: row;">
  <div style="background-color: pink;flex:2">div2<p>This is Anurag Kumar, what are you doing?</p></div>
    <div style="background-color: yellow;flex:2"> div1<p>This is Anurag Kumar, what are you doing?</p></div>
  </div>
  ```