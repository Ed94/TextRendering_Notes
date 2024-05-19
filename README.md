# Text Rendering Notes

I wish I didn't have todo this...

The goal here was to find some solutiont that was small and preferrably interopped well with [odin-lang](https://odin-lang.org).  
So, everything that was either not written in C or was not going to be an easy port, was ignored.

## Not a renderer but it does the hard-stuff for you (free if you negotiate use on a free purpose)

[slug](https://sluglibrary.com)

## Sokol solution (possibly, if your just after a standalone text renderer and willing to just sokol/opengl)

[memononen/fontstash](https://github.com/memononen/fontstash)

[sokol/util/sokol_fontstash.h](https://github.com/floooh/sokol/blob/master/util/sokol_fontstash.h)

There are several forks for fonstash... Going to elabroate on them in a separate [file](fontstash_forks.md)

## Other partial solutions

[kevinmkchinvertext](https://github.com/kevinmkchin/vertext)
(looks to provide everything necessary ~1000 lines of code only)

[RFont](https://github.com/ColleagueRiley/RFont)

[hypernewbie/VEFontCache](https://github.com/hypernewbie/VEFontCache)
(Also looks very good..., but it uses c++, easy to port however since its 1691 lines...)

[libdrawtext](https://github.com/jtsiomb/libdrawtext)

## Learning Resources

[npx-imx/gtec-demo-frameowrk/Doc/FslSimpleUI](https://github.com/nxp-imx/gtec-demo-framework/blob/master/Doc/FslSimpleUI.md)

[Implementing a Font Reader and Rasterizer from Scratch, Part 1: TTF Font Reader](https://handmade.network/forums/articles/t/7330-implementing_a_font_reader_and_rasterizer_from_scratch%252C_part_1__ttf_font_reader)

[LearnOpenGL - Text Rendering](https://learnopengl.com/In-Practice/Text-Rendering)
[Improving Learn OpenGL's Text Rendering Example | Adventures in Coding](https://youtu.be/S0PyZKX4lyI)
[Repo for above vod: johnWRS/LearnOpenGLTextRenderingImprovement](https://github.com/johnWRS/LearnOpenGLTextRenderingImprovement)

[GPU Gems 3: Chapter 25. Rendering Vector Art on the GPU](https://developer.nvidia.com/gpugems/gpugems3/part-iv-image-effects/chapter-25-rendering-vector-art-gpu)

[Writing a TrueType font renderer](https://axleos.com/writing-a-truetype-font-renderer/)

[Wikibooks/OpenGL_Programming/... Text Rendering 01](https://en.wikibooks.org/wiki/OpenGL_Programming/Modern_OpenGL_Tutorial_Text_Rendering_01)
[02 of above](https://en.wikibooks.org/wiki/OpenGL_Programming/Modern_OpenGL_Tutorial_Text_Rendering_02)

## Examples

[refterm](https://www.youtube.com/playlist?list=PLEMXAbCVnmY6zCgpCFlgggRkrp0tpWfrn)

## GPU Related

[GreenLighting/gpu-font-rendering](https://github.com/GreenLightning/gpu-font-rendering)
[evanw/theta](https://github.com/evanw/theta)
[Related article for theta's implementation](https://medium.com/@evanwallace/easy-scalable-text-rendering-on-the-gpu-c3f4d782c5ac)

## Papers

[SIGGRAPH2007: Improved Alpha-Tested Magnification for Vector Textures and Special Effects](https://steamcdn-a.akamaihd.net/apps/valve/2007/SIGGRAPH2007_AlphaTestedMagnification.pdf)
[Resolution Independent Curve Rendering using Programmable Graphics Hardware](https://www.microsoft.com/en-us/research/wp-content/uploads/2005/01/p1000-loop.pdf)

## Misc

### Mr. 4th Programming

[Graphics 2[7] Baking Optimized Fonts Data](https://youtu.be/PQ-wJVjR4MU?list=PLT6InxK-XQvPYA_HLUozeyPGTjwcvYsBj)
[Graphics [8]: Low Level Rendering API Part 1](https://youtu.be/C8gm9l4OJ9o?list=PLT6InxK-XQvPYA_HLUozeyPGTjwcvYsBj)
[Graphics [9]: Low Level Rendering API Part 2](https://youtu.be/Na7pKMupsew?list=PLT6InxK-XQvPYA_HLUozeyPGTjwcvYsBj)
[Graphics [10]: High Level Rendering API](https://youtu.be/jDUTWPEFvY0?list=PLT6InxK-XQvPYA_HLUozeyPGTjwcvYsBj)
...

### Tscoding

[ded editor](https://github.com/tsoding/ded)
[Legendary Font Rendering](https://youtu.be/_t3mtjoHuoQ)
[Rendering Text Editor on GPU](https://youtu.be/srV_l795O_s)

[OpenGL Text Rendering for My Immediate UI Library - Offline Stream #02](https://youtu.be/mq3UXqPmBE8)
