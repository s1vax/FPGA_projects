# 📟 This repository contains several projects I've completed on various FPGAs, including code, help files, and results.

---

### 🙌 Pueden traducir este y los demas repositorios, con el traductor de google de su navegador web o con alguna otra extensión 🙌

---

### 📌 Some abbreviations (like "C_V", "C_IV", "X_N_3", etc.) are for the following FPGAs:
 - C --> Altera Cyclone / V, IV (Board model)
 - X --> Xilinx / N --> Nexys (Board model) / N° [e.g: 3] (Version number of the board model)
 - X --> Xilinx / Z --> Zedboard (Board model) 

### 🗃️ Project structure
```
⚜️ FPGA_projects/
├── 📌 FIR_Filter_C_V  
│   ├──🔻Octave Images/
│   │   ├── street_A.bmp
│   │   └── street_AA.bmp
│   │
│   ├──🔻Octave testing/
│   │   ├── prueba1.m
│   │   ├── sharp_generate_testbench_images.m
│   │   ├── sharp_image_filter.m
│   │   └── write_ascii_ppm.m
│   │
│   ├──🔻VHD Files/
│   │   ├── sharp.vhd
│   │   ├── sharp_arith.vhd
│   │   ├── sharp_control.vhd
│   │   ├── sharp_linemem.vhd
│   │   ├── sharp_slice.vhd
│   │   ├── sim_sharp.vhd
│   │   └── sim_sharp_self-checking.vhd
│   │ 
│   ├──🔹README.md
│   │
│   ├──🔹sharp.sdc
│   │
│   └──🔹sharp_default_Cyclone_V.qsf
│
│
│
├── 📌 Image_Generator_C_IV/         
│   ├──🔻Lane_detection_VHD_Files/
│   │   ├── lane.vhd
│   │   ├── lane_g_matrix.vhd
│   │   ├── lane_g_root.mif
│   │   ├── lane_g_root_IP.vhd
│   │   ├── lane_linemem.vhd
│   │   ├── lane_sobel.vhd
│   │   └── lane_sync.vhd
│   │
│   ├──🔻Street_image_VHD_Files/
│   │   ├── sim_street_image.vhd
│   │   └── street_image.vhd
│   │
│   ├──🔹README.md
│   │
│   └──🔹lane_default_Cyclone_IV
│       
│
│
├── 📌 Lane_detection_C_V/         
│   ├──🔻C files/
│   │   ├── bmp24_io.c
│   │   ├── bmp2sim.c
│   │   ├── lane_fixed.c
│   │   ├── lane_float.c
│   │   ├── lane_testbench.c
│   │   └── simp2bmp.c
│   │
│   ├──🔻Images/
│   │   ├──🔻Simulation Looks like
│   │   │   ├── VHDL Simulation 2.png
│   │   │   └── VHDL Simulation.png
│   │   │     
│   │   ├── Street_A_edge_fixed.bmp
│   │   ├── Street_C_edge_float.bmp
│   │   ├── street_A.bmp
│   │   ├── street_A_edge_float.bmp
│   │   ├── street_B.bmp
│   │   ├── street_B_edge_float.bmp
│   │   └── street_C.bmp
│   │
│   ├──🔻Input and Output images txt (self-testbench)/
│   │   ├── street_0_expected.txt
│   │   └── street_0_stimuli.txt
│   │
│   ├──🔻VHD Files/
│   │   ├── lane.vhd
│   │   ├── lane_g_matrix.vhd
│   │   ├── lane_g_root.mif
│   │   ├── lane_g_root_IP.vhd
│   │   ├── lane_linemem.vhd
│   │   ├── lane_sobel.vhd
│   │   ├── lane_sync.vhd
│   │   └── sim_lane.vhd
│   │
│   ├──🔹README.md
│   │
│   └──🔹a.exe
│
│
│
├── 📌 Projects_results
│   ├──🔻FIR Filter Cyclone V/
│   │   ├── FIRFilter_CV_screenshot_1.png
│   │   ├── FIRFilter_CV_screenshot_2.png
│   │   ├── FIRFilter_remotelab_inputimage.png
│   │   └── FIRFilter_remotelab_outputimage.png
│   │
│   ├──🔻Image Generator Cyclone IV/
│   │   ├── ImageGenerator_CIVE_video.mp4
│   │   ├── ImageGenerator_CIVvideo_screenshot_1.png
│   │   └── ImageGenerator_CIVvideo_screenshot_2.png
│   │
│   ├──🔻Lane detection Cyclone V/
│   │   ├── Lane_detector_CIVE_screenshot_1.png
│   │   ├── Lane_detector_CIVE_screenshot_2.png
│   │   ├── Lane_detector_CV_screenshot_1.png
│   │   └── Lane_detector_CV_screenshot_2.png
│   │
│   ├──🔻Test Images/
│   │   ├── rutasanluis_1280x720.jpg
│   │   ├── rutasanluis_originalformat.jpg
│   │   ├── street_A.png
│   │   ├── street_B.png
│   │   └── street_C.png
│   │
│   ├──🔹Machine Learning Result.png
│   │
│   └──🔹README.md
│
│
│
└── 📌 README.md
```

¡I hope you find it useful!


🙌 Credits to: 
- *Prof. Dr. Marco Winzker* from Bonn-Rhein-Sieg University of Applied Sciences
- *Andrea Schwandt* from Bonn-Rhein-Sieg University of Applied Sciences
- *Alejandro Enrique Nuñez Manquez* from Universidad Nacional de San Luis
