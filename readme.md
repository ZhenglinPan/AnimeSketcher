# AnimeSketcher

**This project is on going and will be updated from time to time.**
***@Date:Jun 10 2023***

## Clarification
I would like to emphasize my utmost respect for the diligent efforts of animation producers and the valuable results they create. The project AnimeSketcher is solely intended for personal research purposes and is in no way associated with any commercial endeavors. Any images or materials labeled as "original" within the project are strictly used for demonstration and will be clearly identified with their original sources. The copyrights of these materials rightfully belong to their respective owners, and should they request removal, the material will be promptly deleted without delay.

<p align="center">
  <img src="https://github.com/ZhenglinPan/AnimeSketcher/blob/master/others/img01.jpg" width="" alt="accessibility text">
</p>

<p align="center">
  <img src="https://github.com/ZhenglinPan/AnimeSketcher/blob/master/others/img03.jpg" width="" alt="accessibility text">
</p>

<p align="center">
  <img src="https://github.com/ZhenglinPan/AnimeSketcher/blob/master/others/img02.jpg" width="" alt="accessibility text">
</p>

This project uses deep learning methods to transform final films of an animation back into sketchs.
本项目的目的是使用深度学习的方法把动画的最终画面变换回原画。

Currently the model is implemented with cycleGAN and a pretrain model can be downloaded [here](https://drive.google.com/file/d/1NwKzV5UxqBrgXHCXa_r6WzJcV8XbRlNO/view?usp=sharing).
目前效果由cycleGAN实现，预训练模型可以在[这里](https://drive.google.com/file/d/1NwKzV5UxqBrgXHCXa_r6WzJcV8XbRlNO/view?usp=sharing)下载。

Dataset is not able to be made public due to a copyright conflict, unfortunately, but you can test the model provided or train your own model instead with implemented code, in such case, a few work need to be done on the code.
由于版权问题，很抱歉数据集不能公开。但是你仍可以使用我训练好的模型进行测试。或者如果你有自己的数据集，也能用我的代码训练自己的模型，不过你可能需要改一些代码。

Test the model with
```python
python test.py --mode test --patch 4
```

This project will be updated from time to time.
不定时更新

