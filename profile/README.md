### Welcome!
If you are interested to get the latest news go to the official website: https://heavygl.github.io/

##### 📚 Specification
> HeavyGL Special functions are not included (glXSetContext, glXSetBuffer,...)

###### Down to a1.2.0
- ```glClearColor(float, float, float)```: Sets the clear color to an RGB value using the RGB 32 bit float values specified.
- ```glClear()```: Clears using the latest clear color.

###### Down to b1.2.0
- ```glGetString(GLenum)```: Returns a string constant depending on the id passed.
- ```glEnable(GLfeature)```: Enables some feature
- ```glDisable(GLfeature)```: Disables a feature
- ```glFillRect(float, float, float, float)```: Draws a rectangle filled using black color

###### Down to c1.2.0 (not released yet)
- ```glCreateMask()```: Returns a new instance of GLmask.
- ```glApplyMask(GLmask)```: Applies any mask.
- ```glCreateTexture()```: Creates a new instance of GLtexture.
- ```glTexture(GLtexture)```: Creates a mask wrapping a texture and applies it automatically.
- ```glColor3f(float, float, float, float)```: Sets the primary color for drawing, RGB 32-bit float scheme.
- ```glFillRect(float, float, float, float)```: Draws a rectangle filled with the latest specified primary fill color.
