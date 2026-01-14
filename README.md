# Complex-Optical-Remote-Sensing-Aircraft-Detection-Dataset
A complex optical remote sensing aircraft dataset (CORS-ADD) is constructed, which originates from several satellites with varying imaging characteristics and covers more diverse aircraft.

## Dataset Description
We construct a complex optical remote sensing aircraft detection dataset (CORS-ADD). Multiple satellites are selected as the data sources, like WorldView-2, WorldView-3, Pleiades, Jilin-1, IKONOS, and Google Earth, to ensure the diversity of scenes and targets. We obtain 5486 images based on manual annotation with a total of 32,285 aircraft (for the oriented bounding boxes). Despite the apron and runway, our dataset also contains various rare scenes, including the aircraft carrier, ocean and land with flying aircraft. The targets cover multiple aircraft such as civil aircraft, bombers, fighters, and early warning aircraft, of which the scale ranges from 4×4 pixels to 240×240 pixels. The annotations is labeled as DOTA format.
The displays of the complex scenes and multiple aircraft are shown as follows.
![display](https://user-images.githubusercontent.com/61158621/216558564-853beca5-fd32-408c-a9fa-ac70ff7cce5f.png)

## Dataset Resource and Usage License
The dataset is available on the following links:

**Baidu Driver**: https://pan.baidu.com/s/1cC4aIUWk8KyUhxWzsCU3eg. (extraction password: _3zpp_)

**Google Driver**: https://drive.google.com/drive/folders/1vijI1xeWLYH7eppcU7ytNQMQ6RPRcs7I?usp=drive_link.

The decompression password is _Cors-add_.  We provide the datasets with horizontal bounding boxes (CORS-ADD-HBB.rar) and oriented bounding boxes (CORS-ADD-OBB.rar). The data with HBBs and OBBs is not excatly the same. **We recommend using the data with OBBs** which is labeled more carefully with fewer problem. **Star this project and we will update the corresponding data consistently**. If you want use our dataset, please follows these rules : 

• Use of Google Earth images must respect the ["Google Earth" terms of use](https://about.google/brand-resource-center/products-and-services/geo-guidelines/).

• All images and their associated annotations in CORS-ADD **can be used for academic purposes only, but any commercial use is prohibited**.

• If you need to use our dataset to make research, please cite our essay (Complex Optical Remote Sensing Aircraft Detection Dataset and Benchmark) **(The essay is acceped and the link is below)**.
~~~
@article{shi2023complex,
  title={Complex optical remote-sensing aircraft detection dataset and benchmark},
  author={Shi, Tianjun and Gong, Jinnan and Jiang, Shikai and Zhi, Xiyang and Bao, Guangzhen and Sun, Yu and Zhang, Wei},
  journal={IEEE Transactions on Geoscience and Remote Sensing},
  volume={61},
  pages={1--9},
  year={2023},
  publisher={IEEE}}
@article{shi2025progressive,
  title={Progressive class-aware instance enhancement for aircraft detection in remote sensing imagery},
  author={Shi, Tianjun and Gong, Jinnan and Hu, Jianming and Sun, Yu and Bao, Guangzhen and Zhang, Pengfei and Wang, Junjie and Zhi, Xiyang and Zhang, Wei},
  journal={Pattern Recognition},
  volume={164},
  pages={111503},
  year={2025},
  publisher={Elsevier}}
~~~

## Contact
If you have any the problem or feedback in using CORS-ADD, please contact

Tianjun Shi at **shitianjun@stu.hit.edu.cn**.
