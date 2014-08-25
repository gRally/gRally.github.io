piccolo elenco degli shaders:

### Premessa
Ogni materiale ha la possibilità di modificare alcune proprietà di default, ereditati dalle proprietà standard di Ogre:
 
* [ambient](http://www.ogre3d.org/docs/manual/manual_16.html#ambient) 1 1 1
* [diffuse](http://www.ogre3d.org/docs/manual/manual_16.html#diffuse) 1 1 1 1
* [specular](http://www.ogre3d.org/docs/manual/manual_16.html#specular) 0 0 0 0 1
* [emissive](http://www.ogre3d.org/docs/manual/manual_16.html#emissive) 0 0 0 
* [scene_blend](http://www.ogre3d.org/docs/manual/manual_16.html#scene_005fblend) default
* [depth_write](http://www.ogre3d.org/docs/manual/manual_16.html#depth_005fwrite) default
* [depth_check](http://www.ogre3d.org/docs/manual/manual_16.html#depth_005fcheck) default
* [alpha_rejection](http://www.ogre3d.org/docs/manual/manual_16.html#alpha_005frejection) default
* [transparent_sorting](http://www.ogre3d.org/docs/manual/manual_16.html#transparent_005fsorting) default
* [polygon_mode](http://www.ogre3d.org/docs/manual/manual_16.html#polygon_005fmode) default

***
Negli esempi utilizzo queste textures qui:
> grazie a http://awesometextures.blogspot.it/


|Texture diffuse `wood_D`                             |Texture normal `wood_N`                            |
|:---------------------------------------------------:|:-------------------------------------------------:|
|[![Diffuse texture](img/wood_D.jpg)](img/wood_D.png) |[![Normal texture](img/wood_N.jpg)](img/wood_N.png)|
|Texture specular `wood_S`                            |                                                   |
|[![Specular texture](img/wood_S.jpg)](img/wood_S.png)|                                                   |
##[[grsD]]

##[[grsDN]]


##[[grsDS]]

***
##grsDNS
Shader classico con Diffuse, Normal e Spec.

Questo è il più completo, con le 3 textures.
```ini
material roadaDiffuseNormalSpec
{
    parent grsDNS
    specular 1 1 1 1 128
    diffuseMap textures/road_tarmac002.dds
    normalMap textures/black_line_1_bump.dds
    specMap textures/spec_1.png
}
```
:warning: Anche qui, come per il DS bisogna valorizzare lo specular, altrimenti non si vede la riflessione.