# LEOPARD: Learning Elements of Operative Printed Arms Recognition Dataset

## Abstract
The rise of 3D-printed firearms poses a new security
challenge, as their plastic composition and modular design make
them difficult to detect even using X-ray scanning systems. There
are thousands of weapon designs freely available online, and
constantly evolving traditional datasets for training detection
models quickly become obsolete. This paper presents an auto-
mated synthetic data generation pipeline that rapidly converts
parts of 3D weapon models into highly realistic annotated
training datasets. Our approach combines procedural variations
in geometry and material properties with physics-based render-
ing to create diverse training samples that account for real-
world printing artifacts and scanning conditions. Experimental
results demonstrate that object detection models trained on these
synthetic data achieve ≥ 70% accuracy in identifying 3D-printed
weapon components, offering a scalable solution for the rapid
evolution of printable firearms. In addition to presenting a novel
methodology, we released a valuable dataset to the scientific
community to support the detection of this type of artifacts using
RGB images.

## Dataset
This study presents a new dataset called 'LEOPARD-Dataset'.

### LEOPARD-Dataset 

This sample dataset consists of 7,500 images generated procedurally using a synthetic data pipeline. The images have been automatically annotated following the class definitions introduced in the paper. All annotations are provided in YOLOv11 format. The generation process includes variations in geometry, material properties, and simulated printing artifacts to closely mimic real-world conditions. This subset is intended to support initial experimentation and validation tasks.


You can download the dataset [here](https://uses0-my.sharepoint.com/:u:/r/personal/jbenjumea4_us_es/Documents/Dataset_piezas_06.zip?csf=1&web=1&e=piJ8RM){:target="_blank" rel="noopener"}.

<table align="center">
  <tr>
    <td align="center">
      <img src="docs/assets/images/Dataset_muestra.png" alt="Image" width="400">
    </td>
    <td align="center">
      <img src="docs/assets/images/piezas.png" alt="Image" width="400">
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="docs/assets/images/deteccion.png" alt="Image" width="400">
    </td>
    <td align="center">
      <img src="docs/assets/images/workflow.png" alt="Image" width="400">
    </td>
  </tr>
</table>

</p>

## Terms of use
This subset can be used for academic research free of charge, citing the paper as we explain below. If you seek to use the data for commercial purposes please or gain access to the full dataset [contact us](mailto:jaalvarez@us.es).

## Citation
If you use our dataset, please kindly cite the following paper: coming soon.

This work is licensed under a
[Creative Commons Attribution-NonCommercial 4.0 International License][cc-by-nc]. Contact the authors of this work for commercial use. 

[![CC BY NC 4.0][cc-by-nc-image]][cc-by-nc]

[cc-by-nc]: http://creativecommons.org/licenses/by-nc/4.0/
[cc-by-nc-image]: https://i.creativecommons.org/l/by-nc/4.0/88x31.png
