# [albumentations_dataaugmentation](https://albumentations.ai/)

![image](https://github.com/user-attachments/assets/561205ad-e335-4a5f-bc38-6ba826b99de0)


## Necessity of data augmentation
- **For High accuracy**
- **Generalization**
- **Overfitting**
* [画像データ拡張ライブラリ ~ albumentations ~](https://qiita.com/Takayoshi_Makabe/items/79c8a5ba692aa94043f7)
* [Albumentationsのaugmentationをひたすら動かす #Python](https://qiita.com/kurilab/items/b69e1be8d0224ae139ad)
* [データ拡張ライブラリ Albumentationsの簡単な使い方](https://zenn.dev/yuto_mo/articles/266cad53af37db)

## Pure Example
1. Setup for directory

![image](https://github.com/user-attachments/assets/8e6b4840-116f-4ea0-a0e1-f1898ea029e9)


2. Set condition
* `path_img`: Input directory for images ex) /original/img above
* `path_mask`: Input directory for masks ex) /original/mask above
* `path_out`: Output directory for images and masks, here img and mask folders are created automatically ex) /out above
* `ext`: extension of input mages, it is not necessary to convert from `jpg` and `jpeg` which is collapsed by compression to `png` or `tiff`
* `num`: you can add a suffix to the original filename.

![image](https://github.com/user-attachments/assets/545fa176-4919-4b1e-9acb-91443a4bb8bb)

3. Choose processing you want
* You can add or remove each processing by commentout
* I recommend you confirm how processing works before [URL](https://albumentations.ai/docs/getting_started/transforms_and_targets/).
![image](https://github.com/user-attachments/assets/d6fa60b9-4cea-4854-90f4-8dc9e97b22c3)
