# FontRenderer
A simple Font renderer for MCP. need to credit me.

FEEL FREE TO STAR ME. WORKED HARD ON THIS PROJECT.

__How to add__:
  - Change all the package names to your own.
  - In FontRenderer.java line 31 Change the location to your own folder.

__How to use__:
  
  NEEDED A FONT FOLDER.
  ```
    public static FontRenderer fr = new FontRenderer("Moon Light",20,Font.PLAIN,true,true);
    fr.drawStringWithShadow("Your String", 3, 3, Color.WHITE.getRGB());
  ```
  OR
  
  NOT NEEDED A FONT FOLDER.
  ```
    public static FontRenderer fr = new FontRenderer(new Font("Moon Light", 20,Font.PLAIN),true,true);
    fr.drawStringWithShadow("Your String", 3, 3, Color.WHITE.getRGB());
  ```
  
 **YOU MUST CREDIT ME IN THE FOLLOWING FORMAT.**
```java
    /*
        ****************************
        * CREATED BY G0dwhitelight *
        ****************************
     */
```
