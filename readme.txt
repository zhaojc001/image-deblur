要求：
- Python3.6
- Scipy
- Scikit-image
- numpy
- Tensorflow 1.4 with NVIDIA GPU or CPU (cpu testing is very slow)

python run_model.py --input_path=input --output_path=output --gpu=0
说明：
    --input_path图像输入路径
    --output_path图像输出路径
    --gpu -1表示使用cpu，0表示使用id为0的gpu，0,1,2表示同时使用id为0,1,2的gpu



