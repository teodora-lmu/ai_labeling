
This is an AI labeling script that adds a label to a given image. The labels are .svg formats that are created in FIGMA., 
whose size is relative to the image and comes in the bottom right corner. If you want to label the image as human, then the label should be changed to "label_human". 

The important values to be changed : 

INPUT_DIR = "ai-validated" --- the directory folder where the images you want to label are coming from
OUTPUT_DIR = "ai_labeled_human" ------ the directory folder where the labeled images are stored after labeling
SVG_LABEL_PATH = "label_human.svg" ---- the label you want to use, either human made or ai made. 
