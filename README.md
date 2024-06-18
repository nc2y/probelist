# Probelist
Probelist for PETS'24 paper by Tang et al.

## Overview
This repository contains the output of the Probelist that was generated in the PETS'24 paper by Tang et al.

## Test List
The test list is available in the `probelist.csv` file. The list is a one
column CSV file with URLs. The first line of the file is a header (`url`), with
the subsequent lines containing URLs. Some escaping of characters is done -
specifically, `'` is replaced with `\'`.

The format of the list is as follows:

```text
url
https://wp.wwu.edu/alisonmason/poem-analysis/
https://www.billboard.com/lists/best-latin-songs-2022-so-far/
https://www.reddit.com/r/MonsterHunter/comments/13oe8te/would_the_monster_hunters_be_able_to_fight_the/
https://unix.stackexchange.com/questions/127276/how-to-detect-imminent-mtd-device-failure
```

## Citation
If you use this probelist, please cite the following paper:

```bibtex
@inproceedings{probelist2024,
      title={Automatic Generation of Web Censorship Probe Lists},
      author={Jenny Tang, Léo Alvarez, Arjun Brar, Nguyen Phong Hoang, and Nicolas Christin},
      booktitle={Proceedings on Privacy Enhancing Technologies Symposium (PETS)},
      year={2024},
      month={july},
}
```

## PoPETS Artifact Evaluation
We provide a template for artifact evaluation in the [template.md](template.md)
file. file in the root of this repository.

## License
The code is released under the MIT License. The license file can be found in the root directory of this repository.
