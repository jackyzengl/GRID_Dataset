# GRID_Dataset

[Project Website](https://jackyzengl.github.io/GRID.github.io/)

## File structure

```
Dataset_Name
├── scene.1.graphs
│   ├── scene.1.instr.0.rg.0.json
│   ├── scene.1.instr.0.rg.1.json
|   ├── ...
│   ├── scene.1.instr.0.sg.0.json
│   ├── scene.1.instr.0.sg.1.json
|   ├── ...
│   ├── scene.1.instr.1.rg.0.json
│   ├── scene.1.instr.1.rg.1.json
|   ├── ...
│   ├── scene.1.instr.1.sg.0.json
│   ├── scene.1.instr.1.sg.1.json
|   ├── ...
├── scene.2.graphs
|   ├── ...
├── ...
├── scene.1.instr.json
├── scene.2.instr.json
├── ...
├── scene.1.scene_graph.json
├── scene.2.scene_graph.json
├── ...
├── scene.1.scene_graph.png
├── scene.2.scene_graph.png
├── ...

```


## TODO
- [x] Release Mini-Dataset for test.
- [ ] Release dataset with 70 objects in each scene.


## Citation
If you find the code useful, please consider citing:
```
@article{ni2023grid,
  title={GRID: Scene-Graph-based Instruction-driven Robotic Task Planning},
  author={Ni, Zhe and Deng, Xiao-Xin and Tai, Cong and Zhu, Xin-Yue and Wu, Xiang and Liu, Yong-Jin and Zeng, Long},
  journal={arXiv preprint arXiv:2309.07726},
  year={2023}
}
```
