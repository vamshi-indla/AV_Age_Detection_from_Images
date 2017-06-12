# AV_Age_Detection_from_Images




### Scripts

All these python scripts can be invoked with --help to display a brief help message. They are meant to be executed in the order,
convert.py crops and resizes images


convert.py

Example usage:

#%%
python convert.py --crop_size 128 --convert_directory data/train_tiny --extension tiff --directory data/train
python convert.py --crop_size 128 --convert_directory data/test_tiny --extension tiff --directory data/test
Usage: convert.py [OPTIONS]
#%%

#%%
Options:
  --directory TEXT          Directory with original images.  [default: data/train]
  --convert_directory TEXT  Where to save converted images.  [default: data/train_res]
  --test                    Convert images one by one and examine them on screen.  [default: False]
  --crop_size INTEGER       Size of converted images.  [default: 256]
  --extension TEXT          Filetype of converted images.  [default: tiff]
  --help                    Show this message and exit
#%%
