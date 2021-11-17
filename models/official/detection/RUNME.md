pip3 install Cython matplotlib opencv-python-headless pyyaml Pillow


python inference_fashionpedia.py --model="attribute_mask_rcnn" --image_size="640" --checkpoint_path="fashionpedia-spinenet-143/model.ckpt" --label_map_file="projects/fashionpedia/dataset/fashionpedia_label_map.csv" --image_file_pattern="cw.jpg" --output_html="out.html" --max_boxes_to_draw=8 --min_score_threshold=0.05 --config_file="projects/fashionpedia/configs/yaml/spinenet143_amrcnn.yaml" --output_file="output.npy"
