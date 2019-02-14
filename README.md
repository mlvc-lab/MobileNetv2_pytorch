--Training Command--

sudo python3 main.py <directory position of ImageNet dataset>

ex) sudo python3 main.py /home/mlvcgpu/youmin/imagenet


--Test Command--

sudo python3 main.py --test True <directory position of ImageNet dataset>

ex) sudo python3 main.py --test True /home/mlvcgpu/youmin/imagenet


--Resume Command--

sudo python3 main.py --resume <checkpoint.pth file position> <directory position of ImageNet dataset>

ex) sudo python3 main.py --resume /home/mlvcgpu/youmin/mobilenetv2_base/checkpoint.pth /home/mlvcgpu/youmin/imagenet