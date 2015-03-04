Shader con Diffuse e Spec.

Questo ha la necessità di avere 2 textures, una per il diffuse e l'altra per lo specular
```
material MT_Test2
{
	parent grsDS
	ambient 1 1 1 1
	diffuse 1 1 1 1
	specular 1 1 1 1 128
    emissive 0 0 0 1
    diffuseMap textures/wood_D.png
    specMap textures/wood_S.png    
}
```
:warning: Per questo shader c'è la necessità di inserire un valore di specular valido, altrimenti non riflette nulla.


|`specular 1 1 1 1 16`                                              |`specular 1 1 1 1 32`                                                 |
|:-----------------------------------------------------------------:|:--------------------------------------------------------------------:|
|[![grsDS alpha 16](img/grsDS_alpha_16.jpg)](img/grsDS_alpha_16.png)|[![grsDS alpha 32](img/grsDS_alpha_32.jpg)](img/grsDS_alpha_32.png)   |
|`specular 1 1 1 1 64`                                              |`specular 1 1 1 1 128`                                                |
|[![grsDS alpha 64](img/grsDS_alpha_64.jpg)](img/grsDS_alpha_64.png)|[![grsDS alpha 128](img/grsDS_alpha_128.jpg)](img/grsDS_alpha_128.png)|