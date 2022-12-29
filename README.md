# support


## saliency cues refinement：

The code is for refinement cues

we drop the use of CRF(Par_CRF.py  line 95)

 
### Training：
```bash
python Code/DeepUSPS.py train -r /home/dxh/v2 -s 432 --arch drn_d_105 --batch-size 20
```

## weed out:

the code is for weed out negative samples



