# Deblurring with Anomaly Detection

A project which aims to deblur the MVTec Anomaly Detection (AD) dataset where we deblur the images without removing the defects present in them.

## Installation

To set up the project, you need to install the required packages. You can do this by running the following command:

```bash
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

This will create a virtual environment and install the required packages.

## Usage

To run the project, you can use the following command:

```bash
jupyter notebook
```

Ensure the dataset is downloaded and present in the folder.
The code refers to paths as per kaggle, if run locally change the path accordingly.

## Sample Results

The following are the results of the project:

- Deep Multi-Patch Hierarchical Network (DMPHN) results:
![comparison_class_bottle_batch1_img1.png](DMPHN-Results/comparison_class_bottle_batch1_img1.png)
![comparison_class_bottle_batch1_img2.png](DMPHN-Results/comparison_class_bottle_batch1_img2.png)
![comparison_class_bottle_batch1_img3.png](DMPHN-Results/comparison_class_bottle_batch1_img3.png)
![comparison_class_bottle_batch1_img4.png](DMPHN-Results/comparison_class_bottle_batch1_img4.png)
![comparison_class_bottle_batch1_img5.png](DMPHN-Results/comparison_class_bottle_batch1_img5.png)
![comparison_class_bottle_batch1_img6.png](DMPHN-Results/comparison_class_bottle_batch1_img6.png)
![comparison_class_cable_batch1_img7.png](DMPHN-Results/comparison_class_cable_batch1_img7.png)
![comparison_class_cable_batch1_img8.png](DMPHN-Results/comparison_class_cable_batch1_img8.png)
![comparison_class_cable_batch1_img9.png](DMPHN-Results/comparison_class_cable_batch1_img9.png)
![comparison_class_cable_batch1_img10.png](DMPHN-Results/comparison_class_cable_batch1_img10.png)
![comparison_class_cable_batch1_img11.png](DMPHN-Results/comparison_class_cable_batch1_img11.png)
![comparison_class_cable_batch1_img12.png](DMPHN-Results/comparison_class_cable_batch1_img12.png)
![comparison_class_cable_batch1_img13.png](DMPHN-Results/comparison_class_cable_batch1_img13.png)
![comparison_class_cable_batch1_img14.png](DMPHN-Results/comparison_class_cable_batch1_img14.png)
![comparison_class_capsule_batch1_img15.png](DMPHN-Results/comparison_class_capsule_batch1_img15.png)
![comparison_class_capsule_batch1_img16.png](DMPHN-Results/comparison_class_capsule_batch1_img16.png)
![comparison_class_capsule_batch1_img17.png](DMPHN-Results/comparison_class_capsule_batch1_img17.png)
![comparison_class_capsule_batch1_img18.png](DMPHN-Results/comparison_class_capsule_batch1_img18.png)
![comparison_class_capsule_batch1_img19.png](DMPHN-Results/comparison_class_capsule_batch1_img19.png)
![comparison_class_carpet_batch1_img20.png](DMPHN-Results/comparison_class_carpet_batch1_img20.png)
![comparison_class_carpet_batch1_img21.png](DMPHN-Results/comparison_class_carpet_batch1_img21.png)
![comparison_class_carpet_batch1_img22.png](DMPHN-Results/comparison_class_carpet_batch1_img22.png)
![comparison_class_carpet_batch1_img23.png](DMPHN-Results/comparison_class_carpet_batch1_img23.png)
![comparison_class_carpet_batch1_img24.png](DMPHN-Results/comparison_class_carpet_batch1_img24.png)
![comparison_class_grid_batch1_img25.png](DMPHN-Results/comparison_class_grid_batch1_img25.png)
![comparison_class_grid_batch1_img26.png](DMPHN-Results/comparison_class_grid_batch1_img26.png)
![comparison_class_grid_batch1_img27.png](DMPHN-Results/comparison_class_grid_batch1_img27.png)
![comparison_class_grid_batch1_img28.png](DMPHN-Results/comparison_class_grid_batch1_img28.png)
![comparison_class_grid_batch1_img29.png](DMPHN-Results/comparison_class_grid_batch1_img29.png)
![comparison_class_hazelnut_batch1_img30.png](DMPHN-Results/comparison_class_hazelnut_batch1_img30.png)
![comparison_class_hazelnut_batch1_img31.png](DMPHN-Results/comparison_class_hazelnut_batch1_img31.png)
![comparison_class_hazelnut_batch1_img32.png](DMPHN-Results/comparison_class_hazelnut_batch1_img32.png)
![comparison_class_hazelnut_batch2_img1.png](DMPHN-Results/comparison_class_hazelnut_batch2_img1.png)
![comparison_class_hazelnut_batch2_img2.png](DMPHN-Results/comparison_class_hazelnut_batch2_img2.png)
![comparison_class_leather_batch2_img3.png](DMPHN-Results/comparison_class_leather_batch2_img3.png)
![comparison_class_leather_batch2_img4.png](DMPHN-Results/comparison_class_leather_batch2_img4.png)
![comparison_class_leather_batch2_img5.png](DMPHN-Results/comparison_class_leather_batch2_img5.png)
![comparison_class_leather_batch2_img6.png](DMPHN-Results/comparison_class_leather_batch2_img6.png)
![comparison_class_leather_batch2_img7.png](DMPHN-Results/comparison_class_leather_batch2_img7.png)
![comparison_class_metal_nut_batch2_img8.png](DMPHN-Results/comparison_class_metal_nut_batch2_img8.png)
![comparison_class_metal_nut_batch2_img9.png](DMPHN-Results/comparison_class_metal_nut_batch2_img9.png)
![comparison_class_metal_nut_batch2_img10.png](DMPHN-Results/comparison_class_metal_nut_batch2_img10.png)
![comparison_class_metal_nut_batch2_img11.png](DMPHN-Results/comparison_class_metal_nut_batch2_img11.png)
![comparison_class_metal_nut_batch2_img12.png](DMPHN-Results/comparison_class_metal_nut_batch2_img12.png)
![comparison_class_metal_nut_batch2_img13.png](DMPHN-Results/comparison_class_metal_nut_batch2_img13.png)
![comparison_class_pill_batch2_img14.png](DMPHN-Results/comparison_class_pill_batch2_img14.png)
![comparison_class_pill_batch2_img15.png](DMPHN-Results/comparison_class_pill_batch2_img15.png)
![comparison_class_pill_batch2_img16.png](DMPHN-Results/comparison_class_pill_batch2_img16.png)
![comparison_class_pill_batch2_img17.png](DMPHN-Results/comparison_class_pill_batch2_img17.png)
![comparison_class_pill_batch2_img18.png](DMPHN-Results/comparison_class_pill_batch2_img18.png)
![comparison_class_pill_batch2_img19.png](DMPHN-Results/comparison_class_pill_batch2_img19.png)
![comparison_class_pill_batch2_img20.png](DMPHN-Results/comparison_class_pill_batch2_img20.png)
![comparison_class_pill_batch2_img21.png](DMPHN-Results/comparison_class_pill_batch2_img21.png)
![comparison_class_pill_batch2_img22.png](DMPHN-Results/comparison_class_pill_batch2_img22.png)
![comparison_class_pill_batch2_img23.png](DMPHN-Results/comparison_class_pill_batch2_img23.png)
![comparison_class_pill_batch2_img24.png](DMPHN-Results/comparison_class_pill_batch2_img24.png)
![comparison_class_screw_batch2_img25.png](DMPHN-Results/comparison_class_screw_batch2_img25.png)
![comparison_class_screw_batch2_img26.png](DMPHN-Results/comparison_class_screw_batch2_img26.png)
![comparison_class_screw_batch2_img27.png](DMPHN-Results/comparison_class_screw_batch2_img27.png)
![comparison_class_screw_batch2_img28.png](DMPHN-Results/comparison_class_screw_batch2_img28.png)
![comparison_class_screw_batch2_img29.png](DMPHN-Results/comparison_class_screw_batch2_img29.png)
![comparison_class_screw_batch2_img30.png](DMPHN-Results/comparison_class_screw_batch2_img30.png)
![comparison_class_screw_batch2_img31.png](DMPHN-Results/comparison_class_screw_batch2_img31.png)
![comparison_class_screw_batch2_img32.png](DMPHN-Results/comparison_class_screw_batch2_img32.png)
![comparison_class_tile_batch3_img1.png](DMPHN-Results/comparison_class_tile_batch3_img1.png)
![comparison_class_tile_batch3_img2.png](DMPHN-Results/comparison_class_tile_batch3_img2.png)
![comparison_class_tile_batch3_img3.png](DMPHN-Results/comparison_class_tile_batch3_img3.png)
![comparison_class_tile_batch3_img4.png](DMPHN-Results/comparison_class_tile_batch3_img4.png)
![comparison_class_tile_batch3_img5.png](DMPHN-Results/comparison_class_tile_batch3_img5.png)
![comparison_class_toothbrush_batch3_img6.png](DMPHN-Results/comparison_class_toothbrush_batch3_img6.png)
![comparison_class_toothbrush_batch3_img7.png](DMPHN-Results/comparison_class_toothbrush_batch3_img7.png)
![comparison_class_toothbrush_batch3_img8.png](DMPHN-Results/comparison_class_toothbrush_batch3_img8.png)
![comparison_class_transistor_batch3_img9.png](DMPHN-Results/comparison_class_transistor_batch3_img9.png)
![comparison_class_transistor_batch3_img10.png](DMPHN-Results/comparison_class_transistor_batch3_img10.png)
![comparison_class_transistor_batch3_img11.png](DMPHN-Results/comparison_class_transistor_batch3_img11.png)
![comparison_class_transistor_batch3_img12.png](DMPHN-Results/comparison_class_transistor_batch3_img12.png)
![comparison_class_wood_batch3_img13.png](DMPHN-Results/comparison_class_wood_batch3_img13.png)
![comparison_class_wood_batch3_img14.png](DMPHN-Results/comparison_class_wood_batch3_img14.png)
![comparison_class_wood_batch3_img15.png](DMPHN-Results/comparison_class_wood_batch3_img15.png)
![comparison_class_wood_batch3_img16.png](DMPHN-Results/comparison_class_wood_batch3_img16.png)
![comparison_class_wood_batch3_img17.png](DMPHN-Results/comparison_class_wood_batch3_img17.png)
![comparison_class_zipper_batch3_img18.png](DMPHN-Results/comparison_class_zipper_batch3_img18.png)
![comparison_class_zipper_batch3_img19.png](DMPHN-Results/comparison_class_zipper_batch3_img19.png)
![comparison_class_zipper_batch3_img20.png](DMPHN-Results/comparison_class_zipper_batch3_img20.png)
![comparison_class_zipper_batch3_img21.png](DMPHN-Results/comparison_class_zipper_batch3_img21.png)
![comparison_class_zipper_batch3_img22.png](DMPHN-Results/comparison_class_zipper_batch3_img22.png)
![comparison_class_zipper_batch3_img23.png](DMPHN-Results/comparison_class_zipper_batch3_img23.png)
![comparison_class_zipper_batch3_img24.png](DMPHN-Results/comparison_class_zipper_batch3_img24.png)

- Encoder Decoder Results:

![comparison_class_bottle_batch1_img1.png](Encoder-Decoder-Results/comparison_class_bottle_batch1_img1.png)
![comparison_class_bottle_batch1_img2.png](Encoder-Decoder-Results/comparison_class_bottle_batch1_img2.png)
![comparison_class_bottle_batch1_img3.png](Encoder-Decoder-Results/comparison_class_bottle_batch1_img3.png)
![comparison_class_bottle_batch1_img4.png](Encoder-Decoder-Results/comparison_class_bottle_batch1_img4.png)
![comparison_class_bottle_batch1_img5.png](Encoder-Decoder-Results/comparison_class_bottle_batch1_img5.png)
![comparison_class_bottle_batch1_img6.png](Encoder-Decoder-Results/comparison_class_bottle_batch1_img6.png)
![comparison_class_cable_batch1_img7.png](Encoder-Decoder-Results/comparison_class_cable_batch1_img7.png)
![comparison_class_cable_batch1_img8.png](Encoder-Decoder-Results/comparison_class_cable_batch1_img8.png)
![comparison_class_cable_batch1_img9.png](Encoder-Decoder-Results/comparison_class_cable_batch1_img9.png)
![comparison_class_cable_batch1_img10.png](Encoder-Decoder-Results/comparison_class_cable_batch1_img10.png)
![comparison_class_cable_batch1_img11.png](Encoder-Decoder-Results/comparison_class_cable_batch1_img11.png)
![comparison_class_cable_batch1_img12.png](Encoder-Decoder-Results/comparison_class_cable_batch1_img12.png)
![comparison_class_cable_batch1_img13.png](Encoder-Decoder-Results/comparison_class_cable_batch1_img13.png)
![comparison_class_cable_batch1_img14.png](Encoder-Decoder-Results/comparison_class_cable_batch1_img14.png)
![comparison_class_capsule_batch1_img15.png](Encoder-Decoder-Results/comparison_class_capsule_batch1_img15.png)
![comparison_class_capsule_batch1_img16.png](Encoder-Decoder-Results/comparison_class_capsule_batch1_img16.png)
![comparison_class_capsule_batch1_img17.png](Encoder-Decoder-Results/comparison_class_capsule_batch1_img17.png)
![comparison_class_capsule_batch1_img18.png](Encoder-Decoder-Results/comparison_class_capsule_batch1_img18.png)
![comparison_class_capsule_batch1_img19.png](Encoder-Decoder-Results/comparison_class_capsule_batch1_img19.png)
![comparison_class_carpet_batch1_img20.png](Encoder-Decoder-Results/comparison_class_carpet_batch1_img20.png)
![comparison_class_carpet_batch1_img21.png](Encoder-Decoder-Results/comparison_class_carpet_batch1_img21.png)
![comparison_class_carpet_batch1_img22.png](Encoder-Decoder-Results/comparison_class_carpet_batch1_img22.png)
![comparison_class_carpet_batch1_img23.png](Encoder-Decoder-Results/comparison_class_carpet_batch1_img23.png)
![comparison_class_carpet_batch1_img24.png](Encoder-Decoder-Results/comparison_class_carpet_batch1_img24.png)
![comparison_class_grid_batch1_img25.png](Encoder-Decoder-Results/comparison_class_grid_batch1_img25.png)
![comparison_class_grid_batch1_img26.png](Encoder-Decoder-Results/comparison_class_grid_batch1_img26.png)
![comparison_class_grid_batch1_img27.png](Encoder-Decoder-Results/comparison_class_grid_batch1_img27.png)
![comparison_class_grid_batch1_img28.png](Encoder-Decoder-Results/comparison_class_grid_batch1_img28.png)
![comparison_class_grid_batch1_img29.png](Encoder-Decoder-Results/comparison_class_grid_batch1_img29.png)
![comparison_class_hazelnut_batch1_img30.png](Encoder-Decoder-Results/comparison_class_hazelnut_batch1_img30.png)
![comparison_class_hazelnut_batch1_img31.png](Encoder-Decoder-Results/comparison_class_hazelnut_batch1_img31.png)
![comparison_class_hazelnut_batch1_img32.png](Encoder-Decoder-Results/comparison_class_hazelnut_batch1_img32.png)
![comparison_class_hazelnut_batch2_img1.png](Encoder-Decoder-Results/comparison_class_hazelnut_batch2_img1.png)
![comparison_class_hazelnut_batch2_img2.png](Encoder-Decoder-Results/comparison_class_hazelnut_batch2_img2.png)
![comparison_class_leather_batch2_img3.png](Encoder-Decoder-Results/comparison_class_leather_batch2_img3.png)
![comparison_class_leather_batch2_img4.png](Encoder-Decoder-Results/comparison_class_leather_batch2_img4.png)
![comparison_class_leather_batch2_img5.png](Encoder-Decoder-Results/comparison_class_leather_batch2_img5.png)
![comparison_class_leather_batch2_img6.png](Encoder-Decoder-Results/comparison_class_leather_batch2_img6.png)
![comparison_class_leather_batch2_img7.png](Encoder-Decoder-Results/comparison_class_leather_batch2_img7.png)
![comparison_class_metal_nut_batch2_img8.png](Encoder-Decoder-Results/comparison_class_metal_nut_batch2_img8.png)
![comparison_class_metal_nut_batch2_img9.png](Encoder-Decoder-Results/comparison_class_metal_nut_batch2_img9.png)
![comparison_class_metal_nut_batch2_img10.png](Encoder-Decoder-Results/comparison_class_metal_nut_batch2_img10.png)
![comparison_class_metal_nut_batch2_img11.png](Encoder-Decoder-Results/comparison_class_metal_nut_batch2_img11.png)
![comparison_class_metal_nut_batch2_img12.png](Encoder-Decoder-Results/comparison_class_metal_nut_batch2_img12.png)
![comparison_class_metal_nut_batch2_img13.png](Encoder-Decoder-Results/comparison_class_metal_nut_batch2_img13.png)
![comparison_class_pill_batch2_img14.png](Encoder-Decoder-Results/comparison_class_pill_batch2_img14.png)
![comparison_class_pill_batch2_img15.png](Encoder-Decoder-Results/comparison_class_pill_batch2_img15.png)
![comparison_class_pill_batch2_img16.png](Encoder-Decoder-Results/comparison_class_pill_batch2_img16.png)
![comparison_class_pill_batch2_img17.png](Encoder-Decoder-Results/comparison_class_pill_batch2_img17.png)
![comparison_class_pill_batch2_img18.png](Encoder-Decoder-Results/comparison_class_pill_batch2_img18.png)
![comparison_class_pill_batch2_img19.png](Encoder-Decoder-Results/comparison_class_pill_batch2_img19.png)
![comparison_class_pill_batch2_img20.png](Encoder-Decoder-Results/comparison_class_pill_batch2_img20.png)
![comparison_class_pill_batch2_img21.png](Encoder-Decoder-Results/comparison_class_pill_batch2_img21.png)
![comparison_class_pill_batch2_img22.png](Encoder-Decoder-Results/comparison_class_pill_batch2_img22.png)
![comparison_class_pill_batch2_img23.png](Encoder-Decoder-Results/comparison_class_pill_batch2_img23.png)
![comparison_class_pill_batch2_img24.png](Encoder-Decoder-Results/comparison_class_pill_batch2_img24.png)
![comparison_class_screw_batch2_img25.png](Encoder-Decoder-Results/comparison_class_screw_batch2_img25.png)
![comparison_class_screw_batch2_img26.png](Encoder-Decoder-Results/comparison_class_screw_batch2_img26.png)
![comparison_class_screw_batch2_img27.png](Encoder-Decoder-Results/comparison_class_screw_batch2_img27.png)
![comparison_class_screw_batch2_img28.png](Encoder-Decoder-Results/comparison_class_screw_batch2_img28.png)
![comparison_class_screw_batch2_img29.png](Encoder-Decoder-Results/comparison_class_screw_batch2_img29.png)
![comparison_class_screw_batch2_img30.png](Encoder-Decoder-Results/comparison_class_screw_batch2_img30.png)
![comparison_class_screw_batch2_img31.png](Encoder-Decoder-Results/comparison_class_screw_batch2_img31.png)
![comparison_class_screw_batch2_img32.png](Encoder-Decoder-Results/comparison_class_screw_batch2_img32.png)
![comparison_class_tile_batch3_img1.png](Encoder-Decoder-Results/comparison_class_tile_batch3_img1.png)
![comparison_class_tile_batch3_img2.png](Encoder-Decoder-Results/comparison_class_tile_batch3_img2.png)
![comparison_class_tile_batch3_img3.png](Encoder-Decoder-Results/comparison_class_tile_batch3_img3.png)
![comparison_class_tile_batch3_img4.png](Encoder-Decoder-Results/comparison_class_tile_batch3_img4.png)
![comparison_class_tile_batch3_img5.png](Encoder-Decoder-Results/comparison_class_tile_batch3_img5.png)
![comparison_class_toothbrush_batch3_img6.png](Encoder-Decoder-Results/comparison_class_toothbrush_batch3_img6.png)
![comparison_class_toothbrush_batch3_img7.png](Encoder-Decoder-Results/comparison_class_toothbrush_batch3_img7.png)
![comparison_class_toothbrush_batch3_img8.png](Encoder-Decoder-Results/comparison_class_toothbrush_batch3_img8.png)
![comparison_class_transistor_batch3_img9.png](Encoder-Decoder-Results/comparison_class_transistor_batch3_img9.png)
![comparison_class_transistor_batch3_img10.png](Encoder-Decoder-Results/comparison_class_transistor_batch3_img10.png)
![comparison_class_transistor_batch3_img11.png](Encoder-Decoder-Results/comparison_class_transistor_batch3_img11.png)
![comparison_class_transistor_batch3_img12.png](Encoder-Decoder-Results/comparison_class_transistor_batch3_img12.png)
![comparison_class_wood_batch3_img13.png](Encoder-Decoder-Results/comparison_class_wood_batch3_img13.png)
![comparison_class_wood_batch3_img14.png](Encoder-Decoder-Results/comparison_class_wood_batch3_img14.png)
![comparison_class_wood_batch3_img15.png](Encoder-Decoder-Results/comparison_class_wood_batch3_img15.png)
![comparison_class_wood_batch3_img16.png](Encoder-Decoder-Results/comparison_class_wood_batch3_img16.png)
![comparison_class_wood_batch3_img17.png](Encoder-Decoder-Results/comparison_class_wood_batch3_img17.png)
![comparison_class_zipper_batch3_img18.png](Encoder-Decoder-Results/comparison_class_zipper_batch3_img18.png)
![comparison_class_zipper_batch3_img19.png](Encoder-Decoder-Results/comparison_class_zipper_batch3_img19.png)
![comparison_class_zipper_batch3_img20.png](Encoder-Decoder-Results/comparison_class_zipper_batch3_img20.png)
![comparison_class_zipper_batch3_img21.png](Encoder-Decoder-Results/comparison_class_zipper_batch3_img21.png)
![comparison_class_zipper_batch3_img22.png](Encoder-Decoder-Results/comparison_class_zipper_batch3_img22.png)
![comparison_class_zipper_batch3_img23.png](Encoder-Decoder-Results/comparison_class_zipper_batch3_img23.png)
![comparison_class_zipper_batch3_img24.png](Encoder-Decoder-Results/comparison_class_zipper_batch3_img24.png)

## PSNR and SSIM

- DMPHN Results:
    PSNR - Mean: 28.40, Std: 3.01
    SSIM - Mean: 0.8144, Std: 0.1002
- Encoder Decoder Results:
    PSNR - Mean: 31.62, Std: 3.51
    SSIM - Mean: 0.8757, Std: 0.0854
