This is a README File



```javascript
v       ar imagName, text, fontColor;

        imagName = prompt("Enter image name: ");
        text = prompt("Enter text: ");
        fontColor = prompt("Enter font color: ");
        
        document.write("<p style= 'color: " + fontColor + "';>"+ text+ "</p>");
        document.write("<img src = '"   +imagName+  ".png'  style = 'width: 250px; height : 250px; border:3px solid "+fontColor+";'>");


![Cat Photo](cat.png)
