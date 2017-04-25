# Domain Transfer Network (DTN) 

TensorFlow implementation of [Unsupervised Cross-Domain Image Generation.](https://arxiv.org/abs/1611.02200)

Download MNIST and SHVN
Using
chmod +x download.sh
./download.sh 

Then run prepos.py

Then pretrain by
python main.py --mode='pretrain'

Then train
python main.py --mode='train'

Evaluate
python main.py --mode='eval'




