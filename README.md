# CMA-based-adversarial-example

Run:

1. Clone the repo
2. Download and untar the following checkpoint: `http://download.tensorflow.org/models/ens4_adv_inception_v3_2017_08_18.tar.gz` and move it into the `data/` folder
3. `cd` into the `data/` folder and run `python model_convert.py $CHECKPOINT_NAME model_v1.ckpt` (this just converts the checkpoint back to a Saver-v1 version because that's what the code is designed to read)
4. `cd` into `CMA-based-adversarial-example/` and run `python3 CMA-PB.py`

