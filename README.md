# tesseract-languages
ESB AI Lab repo of released trained tesseract-ocr languages for language preservation

Our New Hawaiian Model! We trained this using [tesseract-ocr](https://github.com/tesseract-ocr/tesseract) on 2 books with 234 pages total - O Kamehameha (136 pages) and O Lunalilo (98 pages). This resulted in a BCER of 1.275% after 20K Iterations.
Training data and details coming soon! In the meantime please test our model on your own Hawaiian texts. 

## Hawaiian Language Notes
### Hawaiian Alphabet
The Hawaiian alphabet consists of 13 letters:
H, K, L, M, N, P, W, A, E, I, O, U, ʻ (ʻokina) and with vowels that can contain kahako's (ā, ē, ī, ō, ū).

Data scraping, data labeling and model training done by:
- [Edwin Solares, PhD Lead PI](http://edwinsolares.com/)
- [Anthony Tong](https://github.com/atong28)
- [Welo Gosline-Niheu](https://github.com/weloniheu)
- [Andrew Pan](https://github.com/pandrew99)
- [Sadrac Santa-Cruz](https://github.com/SadracSantacruz)
- [Doanh Nguyen](https://github.com/doanhandonly)
- [Yashil Vora](https://github.com/yashilvora19)

We used [LabelStudio](https://labelstud.io/guide) community edition and [Docker](https://www.docker.com/) for assisting in data labeling and the [San Diego Super Computing Cluster](https://www.sdsc.edu/) for training.
