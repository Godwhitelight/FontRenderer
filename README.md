#   <h3 align="center">FontRenderer</h3>
  <h3 align="center">🌟Star this project to support me!🌟</h3>

A simple Font renderer for MCP.

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
