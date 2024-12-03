# DDPM on MNIST and SVHN

The model is trained to generate digit 0~9 on MNIST (class 0~9) and SVHN (class 10~19).

## Usage

### Training
Go to `ddpm.py `, uncomment the `train_combined()` line in `__main__`

### Inferencing
Pretrained model:
```bash
hw2_download_ckpt.sh
```

Inference:
```bash
hw2_1.sh <output_path>
```

## Reference
[DDPM on MNIST](https://github.com/TeaPearce/Conditional_Diffusion_MNIST)

