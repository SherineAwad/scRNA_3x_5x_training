# Training Dataset: scRNA-seq Data from 3x and 5x Amputated Mouse Digit Tips

[Click here to download the data (you will need to log in with your University of Cambridge credentials)](https://drive.google.com/drive/folders/1xFSFhso0atJtTVNzQtSWkT2popfzkdIB?usp=sharing)

| Sample ID | Condition |
|---|---|
| SITTF8 | 3x |
| SITTC1 | 5x |


## Summary Statistics by Sample

| orig.ident | Total_Droplets | Mean_nCount | Median_nCount | Mean_nFeature | Median_nFeature | Mean_percent.mt |
|------------|---------------:|------------:|--------------:|--------------:|----------------:|----------------:|
| 3x         | 25,703         | 3,427.728   | 2,674.0       | 1,544.487     | 1,455.0         | 3.917964        |
| 5x         | 5,230          | 13,618.667  | 11,956.5      | 2,823.443     | 3,274.5         | 4.666826        | 



#### Pre filtering 

![](figures/DigitTips_preFilter2.png?v=1) 


#### Post filtering 
![](figures/DigitTips_postFilter2.png?v=1) 

### UMAP and clustered UMAP  

![](figures/DigitTips_UMAP2.png?v=1)


#### QC per cluster 

![](figures/DigitTips_QC_per_cluster.png?v=1) 


### Marker genes 
```
marker_genes = {
    "Fibroblast": ["Prrx1", "Pdgfra", "Col1a1", "Dcn", "Pi16", "Cd34"],
    "Endothelial": ["Esam", "Flt1", "Vwf", "Plvap","Cdh5", "Pecam1", "Kdr", "Emcn", "Erg", "Cd34"],
    "Macrophage": ["Adgre1", "Csf1r", "Cd68", "Mrc1", "Cd163"],
    "Keratinocyte": ["Krt14", "Krt5", "Epcam", "Cdh1", "Krt17", "Dsg3"],
    "Osteoblast": ["Runx2", "Postn", "Mmp13", "Spp1", "Dmp1","Sp7", "Bglap", "Alpl", "Ibsp", "Col1a1"],
    "Pericyte": ["Cspg4", "Pdgfrb", "Kcnj8", "Abcc9", "Rgs5"],
    "SMC": ["Myh11", "Tagln", "Acta2", "Cnn1", "Des"],
    "Chondrocyte": ["Col2a1", "Acan", "Sox9", "Matn1", "Col9a1", "Comp"],
    "Schwann": ["Mbp", "Plp1", "Sox10", "S100b", "Pmp22"],
    "T-cell": ["Cd3d", "Cd3e", "Cd4", "Cd8a", "Cd28"],
    "Osteoclast": ["Ctsk", "Acp5", "Calcr", "Oscar", "Nfatc1", "Dcstamp", "Tnfrsf11a"],
    "Synoviocyte": ["Prg4", "Ucma", "Gdf5", "Cilp2", "Frzb"],
    "Neutrophil": ["Ly6g", "S100a8", "S100a9", "Mpo", "Csf3r"],
    "Lymphatic_Endothelial": ["Prox1", "Lyve1", "Pdpn", "Flt4", "Pecam1"],
    "B-cell": ["Cd79a", "Cd19", "Ms4a1", "Ighm", "Pax5", "Cd22"],
    "Rspo3_Col23a1": ["Rspo3", "Col23a1"],
    "MSC": ["Lepr", "Cxcl12", "Ngfr", "Nes", "Cd44", "Scf"],
    "Osteosarcoma": ["EGFP"],
    "Nail_Epithelium": ["Lgr6", "Sp6", "Sp8"],
    "Sweat_glands": ["Aqp5","Scnn1a","Scnn1b","Scnn1g","Krt19","Krt7","Krt8","Krt18","Krt5","Krt14","Foxa1"],
    "Mast cell": ["Kit", "Cpa3", "Tpsab1", "Tpsb2", "Ms4a2", "Hdc", "Hpgds", "Mcpt8", "Cd200r3", "Ccr3"]
}
```
#### MESENCHYMAL
* **Fibroblasts**
* **Osteoprogenitors / Osteoblasts**
* **Chondrocytes**

#### IMMUNE
* **Macrophages**
* **Neutrophils**
* **Monocytes**
* **Dendritic cells**
* **Mast cells**
* **T-cells & B-cells**


### Feature Plots 

<img src="figures/FeaturePlot_Mast_cell.png?v=1" width="100%" />

<img src="figures/FeaturePlot_Sweat_glands.png?v=1" width="100%" />

<img src="figures/FeaturePlot_Nail_Epithelium.png?v=1" width="100%" />

<img src="figures/FeaturePlot_MSC.png?v=1" width="100%" />

<img src="figures/FeaturePlot_B-cell.png?v=1" width="100%" />

<img src="figures/FeaturePlot_Lymphatic_Endothelial.png?v=1" width="100%" />

<img src="figures/FeaturePlot_Neutrophil.png?v=1" width="100%" />

<img src="figures/FeaturePlot_Synoviocyte.png?v=1" width="100%" />

<img src="figures/FeaturePlot_Osteoclast.png?v=1" width="100%" />

<img src="figures/FeaturePlot_T-cell.png?v=1" width="100%" />

<img src="figures/FeaturePlot_Chondrocyte.png?v=1" width="100%" />

<img src="figures/FeaturePlot_Osteoblast.png?v=1" width="100%" />

<img src="figures/FeaturePlot_Keratinocyte.png?v=1" width="100%" />

<img src="figures/FeaturePlot_Macrophage.png?v=1" width="100%" />

<img src="figures/FeaturePlot_Fibroblast.png?v=1" width="100%" />

<img src="figures/FeaturePlot_Schwann.png?v=1" width="100%" />

<img src="figures/FeaturePlot_SMC.png?v=1" width="100%" />

<img src="figures/FeaturePlot_Pericyte.png?v=1" width="100%" />

<img src="figures/FeaturePlot_Melanocyte.png?v=1" width="100%" />

<img src="figures/FeaturePlot_Skeletal_Muscle.png?v=1" width="100%" />

<img src="figures/FeaturePlot_Erythroid.png?v=1" width="100%" />

<img src="figures/FeaturePlot_Cycling.png?v=1" width="100%" />

<img src="figures/FeaturePlot_Endothelial_Broad.png?v=1" width="100%" />

<img src="figures/FeaturePlot_Epithelial_Broad.png?v=1" width="100%" />

<img src="figures/FeaturePlot_Mesenchymal_Broad.png?v=1" width="100%" />

<img src="figures/FeaturePlot_Immune_Broad.png?v=1" width="100%" />


#### Annotations

![](figures/DigitTips_Annotated_UMAP.png?v=1) 
