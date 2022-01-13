# self-supervision-remote-sensing-abstraction
This repository contains the experiments for the paper "[Self-Supervision, Remote Sensing and Abstraction: Representation Learning Across 3 Million Locations](https://ieeexplore.ieee.org/document/9647061)"


# Results
| Experiment | Imagery | Workflow | Pretrain cities | test cities | Accuracy | Checkpoint |
| ------ | ------ | ------ | ------ | ------ | ------ | ------ |
|Generalizability|Satellite|MoCo V1|200|200|95%| - |
|Generalizability|Satellite|MoCo V2|200|200|99%| - |
|Generalizability|Satellite|MoCo V1|200|1690|81%| [checkpoint](https://mediaflux.researchsoftware.unimelb.edu.au:443/mflux/share.mfjp?_token=BfwEHkxMgFZH5EClMlpy1128215110&browser=true&filename=MOCO_V1_sat_200_cities.pth.tar) |
|Generalizability|Satellite|MoCo V2|200|1690|95%| [checkpoint](https://mediaflux.researchsoftware.unimelb.edu.au:443/mflux/share.mfjp?_token=QrqAsUYRhBIDiqhDHkqL1128215112&browser=true&filename=MOCO_V2_sat_200_cities.pth.tar) |
|Generalizability|Satellite|MoCo V2|1690|1690|98%| [checkpoint](https://mediaflux.researchsoftware.unimelb.edu.au:443/mflux/share.mfjp?_token=QzhZjnOMJa366t7i7uZQ1128215114&browser=true&filename=MOCO_V2_sat_1690_cities.pth.tar) |
|Abstraction|Maps|MoCo V1|1665|1665|67%| [checkpoint](https://mediaflux.researchsoftware.unimelb.edu.au:443/mflux/share.mfjp?_token=92u37NHEdbn8VmbROnmA1128215106&browser=true&filename=MOCO_V1_map.pth.tar) |
|Abstraction|Maps|MoCo V2|1665|1665|61%| [checkpoint](https://mediaflux.researchsoftware.unimelb.edu.au:443/mflux/share.mfjp?_token=eltFkFpE8CknbCtYy5oe1128215108&browser=true&filename=MOCO_V2_map.pth.tar) |
|Abstraction|Maps|DINO|1665|1665|36%| - |

# Citation
If you find these results/models useful please consider citing:

@inproceedings{seneviratne2021self,
  title={Self-Supervision. Remote Sensing and Abstraction: Representation Learning Across 3 Million Locations},
  author={Seneviratne, Sachith and Nice, Kerry A and Wijnands, Jasper S and Stevenson, Mark and Thompson, Jason},
  booktitle={2021 Digital Image Computing: Techniques and Applications (DICTA)},
  pages={01--08},
  organization={IEEE}
}
