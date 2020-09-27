# solar2d-ogtlib
Misc routines to help with Solar2D development.

In the file where you want to use OGTLib, add this at the top:

```local ogt = require "OGTLib"```

Then to use one of the routines, do soemthing like this:

```local SpinSFX = ogt.loadParticleFile("Spin.json")```
