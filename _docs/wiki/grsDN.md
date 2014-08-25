Shader con Diffuse e Normal.

Questo ha la necessità di avere 2 textures, una per il diffuse e l'altra per il normal.
```
material MT_Test2
{
	parent grsDN
	ambient 1 1 1 1
	diffuse 1 1 1 1
	specular 1 1 1 1 64
    emissive 0 0 0 1
    diffuseMap textures/wood_D.png
    normalMap textures/wood_N.png
}
```

:warning: è possibile per questo shader rendere la mesh speculare inserendo il valore
```
specular 1 1 1 1 64
```

|`specular 1 1 1 1 64`                                              |`specular 1 1 1 1 128`                                                |
|:-----------------------------------------------------------------:|:--------------------------------------------------------------------:|
|[![grsDN alpha 64](img/grsDN_alpha_64.jpg)](img/grsDN_alpha_64.png)|[![grsDN alpha 128](img/grsDN_alpha_128.jpg)](img/grsDN_alpha_128.png)|
