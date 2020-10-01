# A Novel Challenge Set for Hebrew Morphological Disambiguation and Diacritics Restoration 

There are 21 Hebrew homographs covered in this dataset, with two possible analyses per homograph. There are approximately 500-2K sentences for each of the two possible analyses for each homograph.

This dataset is provided for research purposes (see License section below).

## Files
Currently the dataset contains sample sentences for 21 homographs. Each homograph is in its own directory, with two files inside the directory - one for each possible analysis. The name of the directory/file represents the homograph/diacritized form. 
For example, for the homograph `עמנו`:
```
----------------------------------------------
.
..
עמנו
    עִמָּנוּ.txt
    עַמֵּנוּ.txt
...
----------------------------------------------
```

## Format
Each file is a text document, containing the tagged examples for that diacritic form. 
Each example is a full sentence on it's own line, with the relevant homograph marked in between double-daggers (`U+2021`) correctly diacritized, marking the class.

For example:

    ידענו שוויתור על המנהג הזה יביא את הקץ על ‡עַמֵּנוּ‡ ועל היהדות כולה.


## License
We provide this dataset for research purposes and make no ownership claim on any part of it. 

## Citing
If you use this dataset in academic work, please cite as follows:

```bibtex
@inproceedings{shmidman-etal-2020-challenge,
  author    = {Avi Shmidman and
               Joshua Guedalia and
               Shaltiel Shmidman and
               Moshe Koppel and
               Reut Tsarfaty},
  title     = {A Novel Challenge Set for Hebrew Morphological Disambiguation and Diacritics Restoration},
  booktitle = "EMNLP 2020 Findings, forthcoming",
  publisher = "Association for Computational Linguistics",
  year      = {2020}
}
```