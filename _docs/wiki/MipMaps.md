breve descrizione delle mipmaps:

dal file render.ini è possibile modificare le impostazioni grafiche delle mipmaps:

```ini
[graph_detail]
anisotropy = 4
num_mip_map = 6
```

## num_mip_map
|[![mip with num 12](img/mip_12.jpg)](img/mip_12.png)|[![mip with num 10](img/mip_10.jpg)](img/mip_10.png)|
|:--------------------------------------------------:|:--------------------------------------------------:|
|immagine con `num_mip_map = 12`                     |immagine con `num_mip_map = 10`                     |
|[![mip with num 5](img/mip_5.jpg)](img/mip_5.png)   |[![mip with num 2](img/mip_2.jpg)](img/mip_2.png)   |
|immagine con `num_mip_map = 5`                      |immagine con `num_mip_map = 2`                      |
|[![mip with num 1](img/mip_1.jpg)](img/mip_1.png)   |                                                    |
|immagine con `num_mip_map = 1`                      |                                                    |

## anisotropy
|[![anis 12](img/aniso_12.jpg)](img/aniso_12.png)|[![anis 8](img/aniso_8.jpg)](img/aniso_8.png)|
|:----------------------------------------------:|:-------------------------------------------:|
|immagine con `anisotropy = 12`                  |immagine con `anisotropy = 8`                |
|[![anis 4](img/aniso_4.jpg)](img/aniso_4.png)   |[![anis 2](img/aniso_2.jpg)](img/aniso_2.png)|
|immagine con `anisotropy = 4`                   |immagine con `anisotropy = 2`                |
|[![anis 1](img/aniso_1.jpg)](img/aniso_1.png)   |[![anis 0](img/aniso_0.jpg)](img/aniso_0.png)|
|immagine con `anisotropy = 1`                   |immagine con `anisotropy = 0`                |
