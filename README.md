# PatchTST

## To Run

### Training

To train the minimal implementation of PatchTST from scratch on the ETTh1 dataset

```
python main.py
```

To fine-tune the minimal implementation of PatchTST (for LoRA use `--lora=True`)

```
python main.py --mode=finetune --ckpt=path/to/ckpt
```

To test the fine-tuned models

```
python main.py --mode=test --ckpt=path/to/ckpt
```


## TODO

1. Add logger
2. Clean-up model