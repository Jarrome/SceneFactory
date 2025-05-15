# [SceneFactory](https://jarrome.github.io/SceneFactory)

[Yijun Yuan](https://jarrome.github.io/), [Michael Bleier](https://www.informatik.uni-wuerzburg.de/robotics/team/bleier/), [Andreas Nüchter](https://www.informatik.uni-wuerzburg.de/robotics/team/nuechter/)

[Preprint](https://arxiv.org/abs/2405.07847) |  [website](https://jarrome.github.io/SceneFactory/)


---

## Install
#### Modules
* Reconer: [SceneFactory-recon](https://github.com/Jarrome/SceneFactory-recon)
* MVDer: [SceneFactory-mvd](https://github.com/Jarrome/SceneFactory-mvd)
* Tracker: [SceneFactory-tracker](https://github.com/Jarrome/SceneFactory-tracker)
* 

```
git clone https://github.com/Jarrome/SceneFactory.git 
```

Install all with
```
source scripts/install_all.sh
```

Or 

to just use certain modules
```
#[module_name] can be `recon` `mvd` and `tracker`
source scripts/install_[module_name].sh
```

## Demo



## Data
Please find [link](https://robotik.informatik.uni-wuerzburg.de/telematics/3dscans/):
It contains livingroom (RGB), roboticshall (RGBD), castle (RGBL), ZfT (univ. land, RGBL).

## TODO
- [x] [track](https://github.com/Jarrome/SceneFactory-tracker)
- [x] [data](https://robotik.informatik.uni-wuerzburg.de/telematics/3dscans/)
- [x] [mvd](https://github.com/Jarrome/SceneFactory-mvd)
- [x] [nslf](https://github.com/Jarrome/SceneFactory-recon)
- [ ] flexion
- [ ] graph

---
## Citation
If you find this work useful, please cite us:
```bibtex
@article{yuan2025scenefactory,
  title={SceneFactory: A Workflow-centric and Unified Framework for Incremental Scene Modeling},
  author={Yuan, Yijun, Bleier, Michael and N{\"u}chter, Andreas},
  journal={IEEE Transactions on Robotics},
  year={2025},
  publisher={IEEE}
}
```
