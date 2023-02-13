# UJCricketBacklift
A dataset for cricket backlift classification that contains videos from YouTube of First-Class International Cricket Test Match highlights. The study specifically selected ten batsmen who exhibited the straight backlift and ten who demonstrated the lateral backlift. The specific batsman that was selected include::

Straight backlift; Babar Azam, Themba Bavuma, Rahul Dravid, JP Duminy, Dean Elgar, Mahela Jayawardene, Ajinkya Rahane, Joe Root, Rory Burns, Ben Stokes, and David Warner. 

Lateral backlift: AB de Villiers, Hashim Amla, Quintin de Kock, Faf du Plessis, Kevin Pieterson, Kumar Sangakkara, Brian Lara, Ricky Ponting, Steve Smith, and Virat Koli.

Using the Labelbox editor, each object within the scene is labelled with bounding boxes, allowing for easier isolation and extraction of the batsman in each frame. The key frame for constructing the dataset was when the bowler was about to release the ball towards the batsman. 

Data split: 80:20
Image size: 128x128

Please cite the following works:
@article{moodley2022automated,
  title={Automated recognition of the cricket batting backlift technique in video footage using deep learning architectures},
  author={Moodley, Tevin and van der Haar, Dustin and Noorbhai, Habib},
  journal={Scientific Reports},
  volume={12},
  number={1},
  pages={1895},
  year={2022},
  publisher={Nature Publishing Group UK London}
}

Shield: [![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
