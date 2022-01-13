# self-supervision-remote-sensing-abstraction
This repository contains the experiments for the paper "Self-Supervision, Remote Sensing and Abstraction: Representation Learning Across 3 Million Locations"


# Results
| Experiment | Imagery | Workflow | Pretrain cities | test cities | Accuracy |
|Generalizability|Satellite|MoCo V1|200|200|95%|
|Generalizability|Satellite|MoCo V2|200|200|99%|
|Generalizability|Satellite|MoCo V1|200|1690|81%|
|Generalizability|Satellite|MoCo V2|200|1690|95%|
|Generalizability|Satellite|MoCo V2|1690|1690|98%|
|Abstraction|Maps|MoCo V1|1665|1665|67%|
|Abstraction|Maps|MoCo V2|1665|1665|61%|
|Abstraction|Maps|DINO|1665|1665|36%|

# Citation
If you find these results/models useful please consider citing:

@inproceedings{seneviratne2021self,
  title={Self-Supervision. Remote Sensing and Abstraction: Representation Learning Across 3 Million Locations},
  author={Seneviratne, Sachith and Nice, Kerry A and Wijnands, Jasper S and Stevenson, Mark and Thompson, Jason},
  booktitle={2021 Digital Image Computing: Techniques and Applications (DICTA)},
  pages={01--08},
  organization={IEEE}
}
