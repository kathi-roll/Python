# Captcha Solving


## Introduction
This is captcha solver made for cracking 4 digit Captchas, given all 4 are numeric in nature. Working on incorporating Alphanumeric Captchas.

The accuracy of 4 digits version can be as high as 97.4%!

**Alexnet** is used as the Model.

Data Generator File used is that of Jackson Yang.
## Generate DataSet for Training

#### Usage

```bash
$ python datasets/gen_captcha.py  -h
usage: gen_captcha.py [-h] [-n N] [-t T] [-d] [-l] [-u] [--npi NPI]
                      [--data_dir DATA_DIR]

optional arguments:
  -h, --help           show this help message and exit
  -n N                 epoch number of character permutations.
  -t T                 ratio of test dataset.
  -d, --digit          use digits in dataset.
  -l, --lower          use lowercase in dataset.
  -u, --upper          use uppercase in dataset.
  --npi NPI            number of characters per image.
  --data_dir DATA_DIR  where data will be saved.


Do let me know your suggestions on the Project.

Open for Collaborations.

Happy Coding ;)
