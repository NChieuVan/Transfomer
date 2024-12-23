```bash
python train.py --epochs ${epochs} --input-lang en --target-lang vi --input-path ${path_to_en_text_file} --target-path ${path_to_vi_text_file}
```

Example: You want to build English-Vietnamese machine translation in 10 epochs

```bash
python train.py --epochs 10 --input-lang en --target-lang vi --input-path ./data/mock/train.en --target-path ./data/mock/train.vi
```
