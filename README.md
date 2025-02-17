The final fine-tuned yolo11x based on VisDrone-DET is stored in google drive: [**Download here**](https://drive.google.com/file/d/1vejrx1ADroPLlVBl9SI0dqbsv-2X4wCW/view?usp=sharing)

Testing results of our fine-tuned yolo11x model:

| Class              | Images | Instances | Box(P) | R    | mAP50 | mAP50-95 |
|--------------------|--------|-----------|--------|------|-------|----------|
| all               | 1610   | 75102     | 0.613  | 0.54 | 0.539 | 0.333    |
| pedestrian        | 1197   | 21006     | 0.693  | 0.53 | 0.577 | 0.264    |
| people           | 797    | 6376      | 0.666  | 0.362 | 0.411 | 0.172    |
| bicycle          | 377    | 1302      | 0.471  | 0.337 | 0.32  | 0.164    |
| car              | 1530   | 28074     | 0.81   | 0.852 | 0.869 | 0.595    |
| van              | 1168   | 5771      | 0.602  | 0.553 | 0.564 | 0.408    |
| truck            | 750    | 2659      | 0.613  | 0.628 | 0.62  | 0.438    |
| tricycle         | 245    | 530       | 0.402  | 0.532 | 0.399 | 0.24     |
| awning-tricycle  | 233    | 599       | 0.459  | 0.349 | 0.317 | 0.214    |
| bus              | 838    | 2940      | 0.78   | 0.655 | 0.729 | 0.553    |
| motor            | 794    | 5845      | 0.636  | 0.605 | 0.585 | 0.284    |
