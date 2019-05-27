# Killme_DCGAN
Generate "Kill me baby" images by DCGAN
https://qiita.com/taku-buntu/items/0093a68bfae0b0ff879d

# Usage
Before you run dcgan.py, you need to unrar kill_me_baby_datasets.rar. 
And it needs you to install pandas, numpy, tensorflow, keras, opencv3, matplotlib in advanced. 
And we implemented this codes in tensorflow1.13.1. 

```
source mkvenv.src.sh
pip install opencv_python
pip install tensorflow
pip install matplotlib

unrar x kill_me_baby_datasets.rar
python3 dcgan.py
```

And then you can get 25 generated images figure in images/gen_imgs and Visualized interpolation latent image in images/latent
