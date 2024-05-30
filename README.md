# Two-Dimensional Laplace NMR Reconstruction through Deep Learning Enhancement
This is the origin Pytorch implementation of DLEMLR in the following paper: Two-Dimensional Laplace NMR Reconstruction through Deep Learning Enhancement. 

## Requirements

Dependencies can be installed using the following command:
```bash
pip3 install torch==1.11.0 --extra-index-url https://download.pytorch.org/whl/cu113
pip3 install -r requirements.txt
```

## Reproducibility

#### Test

- test_result.ipynb 

#### Train

```shell
# generate synthetic data
python3 ./Dataset/generate_dataset.py

# train
python3 train.py

```

## Contact
If you have any questions, please contact us through Email (chenbo@stu.xmu.edu.cn) or Github issues. Pull requests are highly welcomed!
