# ion-opengl
Ion bindings for OpenGL functions

# Usage

**Note** These files do not make any assumptions about the location of the C .h files for OpenGL, as your project may be getting them from a library such as SDL, or from your system's include directory.  You will need to add the relevant GL `#foreign(header = "<GL/gl.h>")`, etc yourself.

Copy the `opengl` folder to your `$IONHOME/system_packages` directory or add it to your `$IONPATH`

Then in your .ion file:

```
import opengl { ... };
```

# Sample Code

See the `test` folder for an example which uses GLew and SDL.
You will need to build the resulting C file with the appropriate GL lib(s) for your platform
