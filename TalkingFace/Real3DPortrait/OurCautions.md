# 复现服务器
4090

# 环境搭建
conda create -n real3dportrait python=3.9
conda activate real3dportrait

# 环境安装
conda install pytorch==2.0.1 torchvision==0.15.2 torchaudio==2.0.2 pytorch-cuda=11.7 -c pytorch -c nvidia

# pytorch3d安装，下列二选一
conda install pytorch3d::pytorch3d

需要本地编译
pip install "git+https://github.com/facebookresearch/pytorch3d.git@stable" 

# MMCV安装
pip install cython
pip install openmim==0.3.9
mim install mmcv==2.1.0 # 使用mim来加速mmcv安装

 # 其他依赖项
pip install -r docs/prepare_env/requirements.txt -v

