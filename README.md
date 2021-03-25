This repository contains all required data in order to set up a Feflow simulation of the numerical groundwater model for the Hainich Critical Zone Exploratory, CRC 1076 AquaDiva, built and published by RÖDIGER et al. 2021.

Feflow is commercial software developed and maintained [by MIKE Powered by DHI](https://www.mikepoweredbydhi.com/products/feflow).
In [Viewer mode](http://www.feflow.info/html/help71/feflow/mainpage.htm#t=14_References%2FPackages%2Fviewer.html%3Frhhlterm%3Dviewer%26rhsyns%3D%2520), FEFLOW does not need a license. Supermesh files (FEM), models, and results files (e.g. DAC) can be loaded and inspected. Further information can be found in the [Feflow 7.1 Documentation](http://www.feflow.info/html/help71/feflow/mainpage.htm#t=02_News%2Fnews.html).

The FEM-files contain all required information to load and run the simulation. Based on the FEM-files some additional information were exported (see list below).
The model output files (DAC) are much larger in size, thus can be found ON ZENODO.


List of Items
=============

```
.
├── LICENSE
├── README.md
├── steady_state
│   ├── Hainich_czo_num_model_steady.fem
│   ├── auxiliary
│   ├── boundary_conditions
│   │   ├── hydraulic_head_bc.dbf
│   │   ├── hydraulic_head_bc.shp
│   │   └── hydraulic_head_bc.shx
│   ├── geometry
│   │   ├── elevation.dbf
│   │   ├── elevation.shp
│   │   └── elevation.shx
│   └── material_properties
│       ├── K_xx.dbf
│       ├── K_xx.shp
│       ├── K_xx.shx
│       ├── K_yy.dbf
│       ├── K_yy.shp
│       ├── K_yy.shx
│       ├── K_zz.dbf
│       ├── K_zz.shp
│       └── K_zz.shx
└── transient_state
    ├── Hainich_czo_num_model_transient.fem
    ├── auxiliary
    │   ├── layer_thickness.dbf
    │   ├── layer_thickness.png
    │   ├── layer_thickness.shp
    │   ├── layer_thickness.shx
    │   ├── slice_distance.dbf
    │   ├── slice_distance.png
    │   ├── slice_distance.shp
    │   └── slice_distance.shx
    ├── boundary_conditions
    │   ├── hydraulic_head_bc.dbf
    │   ├── hydraulic_head_bc.shp
    │   ├── hydraulic_head_bc.shx
    │   ├── hydraulic_head_bc_layer1.png
    │   ├── hydraulic_head_bc_layer2.png
    │   ├── hydraulic_head_bc_layer3.png
    │   ├── hydraulic_head_bc_layer4.png
    │   ├── hydraulic_head_bc_layer5.png
    │   ├── hydraulic_head_bc_layer6.png
    │   └── hydraulic_head_bc_layer7.png
    ├── geometry
    │   ├── elevation.dbf
    │   ├── elevation.png
    │   ├── elevation.shp
    │   └── elevation.shx
    ├── initial_condition
    │   ├── hydraulic_head.dbf
    │   ├── hydraulic_head.shp
    │   ├── hydraulic_head.shx
    │   ├── hydraulic_head_layer1_a.png
    │   ├── hydraulic_head_layer1_b.png
    │   ├── hydraulic_head_layer2.png
    │   ├── hydraulic_head_layer3.png
    │   ├── hydraulic_head_layer4.png
    │   ├── hydraulic_head_layer5.png
    │   ├── hydraulic_head_layer6.png
    │   └── hydraulic_head_layer7.png
    ├── material_properties
    │   ├── K_xx.dbf
    │   ├── K_xx.png
    │   ├── K_xx.shp
    │   ├── K_xx.shx
    │   ├── K_yy.dbf
    │   ├── K_yy.png
    │   ├── K_yy.shp
    │   ├── K_yy.shx
    │   ├── K_zz.dbf
    │   ├── K_zz.png
    │   ├── K_zz.shp
    │   ├── K_zz.shx
    │   ├── drain_fillable_porosity.dbf
    │   ├── drain_fillable_porosity.png
    │   ├── drain_fillable_porosity.shp
    │   ├── drain_fillable_porosity.shx
    │   ├── in_outflow_top_bottom.png
    │   ├── specific_storage.dbf
    │   ├── specific_storage.png
    │   ├── specific_storage.shp
    │   └── specific_storage.shx
    └── time_series
        ├── 221_lateral_inflow.pow
        ├── 222_lateral_inflow.pow
        ├── 225_lateral_inflow.pow
        ├── 230_lateral_inflow.pow
        ├── 234_lateral_inflow.pow
        ├── 240_lateral_inflow.pow
        └── recharge.pow
```



Please contact [Timo Houben](mailto:timo.houben@ufz.de) for questions concerning this repository.