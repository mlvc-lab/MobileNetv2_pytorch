--Training Command--

sudo python3 main.py <directory position of ImageNet dataset>

ex) sudo python3 main.py /home/mlvcgpu/youmin/imagenet




--Test Command--

sudo python3 main.py --test True <directory position of ImageNet dataset>

ex) sudo python3 main.py --test True /home/mlvcgpu/youmin/imagenet




--Resume Command--

sudo python3 main.py --resume <checkpoint.pth file position> <directory position of ImageNet dataset>

ex) sudo python3 main.py --resume /home/mlvcgpu/youmin/mobilenetv2_base/checkpoint.pth /home/mlvcgpu/youmin/imagenet




You should change the code in MobileNetV2's resume_weight(), test_weight() functions' directory position and main.py's 100rows command for directory position