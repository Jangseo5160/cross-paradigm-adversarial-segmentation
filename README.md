# cross-paradigm-adversarial-segmentation
This work investigates inter-paradigm transferability of white-box adversarial attacks, addressing a gap in understanding real-world vulnerabilities where attackers lack knowledge of the target paradigm.

## Repository Layout

```text
cross-paradigm-adversarial-segmentation/
├─ src/                
│  ├─ semantic_make_adv.py
│  ├─ instance_make_adv.py         
│  ├─ panoptic_make_adv.py       
│  ├─ all_make_adv.py                  
├─ scripts/
│  ├─ instance_load_min.py        
│  ├─ panoptic_load_min.py         
│  ├─ semantic_eval_coco.py     
│  ├─ instance_eval_coco.py        
│  ├─ panoptic_eval_coco.py
│  ├─ infer_image_viz.py
├─ notebooks/
│  ├─ environment.yml       
│  ├─ requirements.txt     
├─ configs/             
├─ checkpoints/       
└─ README.md
