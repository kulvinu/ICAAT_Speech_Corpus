# Sinhala_Digits Speech Corpus
The Sinhala Digits Speech Corpus is an attempt to create a speech corpus for Sinhala digits (0-9) due to limited resources in this area. The corpus contains spoken recordings from both adults and children (years 7-9), though age groups were not explicitly considered for adults. This dataset was developed as part of my undergraduate project.

## Features
- Language: Sinhala
- Digits Covered: 0 to 9
- Speakers: Mixed (Adults and children)
- Recording Format: WAV (16kHz, mono, 16-bit PCM)
- Total Recordings: 1450
  - Adult Recordings: 850
  - Child Recordings: 650

## Data Structure
The dataset is structured as follows:
```
root/
│── Children_Dataset/
│   ├── 0.wav
│   ├── 1.wav
│   ├── ...
│── Sinhala_Recordings/
│   ├── 0.wav
│   ├── 1.wav
│   ├── ...
```

## Usage
This corpus can be used for:
- Training and evaluating speech recognition models
- Exploring phonetic and acoustic variations in Sinhala speech

## Citation
If you use this dataset, please cite:
```
@inproceedings{kahawanugoda2022development,
  title={Development of low resource machine learning models for child cognitive ability assessments},
  author={Kahawanugoda, Adithya and Gnanarathna, Kulanika and Meegoda, Nilan and Monarawila, Randika and Samarasinghe, Pradeepa and Lindamulage, Asiri Gawesha},
  booktitle={2022 4th International Conference on Advancements in Computing (ICAC)},
  pages={72--77},
  year={2022},
  organization={IEEE}
}
```
## License

## Contact
For questions, issues, or contributions, please open an issue in this repository:  
[GitHub Issues](https://github.com/kulvinu/ICAAT_Speech_Corpus/issues)
