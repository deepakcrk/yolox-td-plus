Checkout yolox_base branch for base yolox code used
## Detection on COCO-Text dataset

### To reproduce results:

#### yolox-tiny-td-plus
_python3 tools/train.py -n yolox-tiny -d 4 -b 256 --fp16_

#### yolox-small-td-plus
_python3 tools/train.py -n yolox-s -d 4 -b 128 --fp16_


#### yolox-medium-td-plus
_python3 tools/train.py -n yolox-m -d 4 -b 64 --fp16_
