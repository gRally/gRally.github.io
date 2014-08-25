Questo shader è il più semplice: una sola texture *(diffuse)* e basta.
```
material MT_Test2
{
	parent grsD
	ambient 1 1 1 1
	diffuse 1 1 1 1
	specular 0 0 0 0 1
	emissive 0 0 0 1
    diffuseMap textures/wood_D.png
}
```

e questo è il risultato:

[![grsD no alpha](img/grsD_no_alpha.jpg)](img/grsD_no_alpha.png)

:warning: è possibile per questo shader rendere la mesh speculare modificando il valore
```
specular 1 1 1 1 64
```
|no alpha `specular 0 0 0 0 1`                                   |                                                                |
|:--------------------------------------------------------------:|:--------------------------------------------------------------:|
|[![grsD no alpha](img/grsD_no_alpha.jpg)](img/grsD_no_alpha.png)|                                                                |
|`specular 1 1 1 1 4`                                            |`specular 1 1 1 1 16`                                           |
|[![grsD alpha 4](img/grsD_alpha_4.jpg)](img/grsD_alpha_4.png)   |[![grsD alpha 16](img/grsD_alpha_16.jpg)](img/grsD_alpha_16.png)|
|`specular 1 1 1 1 32`                                           |`specular 1 1 1 1 64`                                           |
|[![grsD alpha 32](img/grsD_alpha_32.jpg)](img/grsD_alpha_32.png)|[![grsD alpha 64](img/grsD_alpha_64.jpg)](img/grsD_alpha_64.png)|