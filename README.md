# Train

```python
cd train

# CST_S
python train.py --template cst_s --outf ./exp/cst_s/ --method cst_s 

# CST_M
python train.py --template cst_m --outf ./exp/cst_m/ --method cst_m  

# CST_L
python train.py --template cst_l --outf ./exp/cst_l/ --method cst_l
```



# Test

```python
cd test

# CST_S
python test.py --template cst_s --outf ./exp/cst_s/ --method cst_s --pretrained_model_path ./model_zoo/cst/cst_s.pth

# CST_M
python test.py --template cst_m --outf ./exp/cst_m/ --method cst_m --pretrained_model_path ./model_zoo/cst/cst_m.pth

# CST_L
python test.py --template cst_l --outf ./exp/cst_l/ --method cst_l --pretrained_model_path ./model_zoo/cst/cst_l.pth
```





