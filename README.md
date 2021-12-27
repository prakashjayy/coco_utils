# coco_utils
A set of utility functions to process object detection (coco) datasets.


## Summary
- **COCO wrapper**,  Use coco_utils COCO function which has extra properties like `label_counts`, `label_presence`, `img_wise_counts`, `label_names`, `label_names_available`, `count_images`. 

```python
from coco_utils.coco import COCO
x = COCO("data/annotations/instances_val2017.json")
```