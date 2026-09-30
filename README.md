# Awesome Mammography

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/github/license/DH82/Awesome-Mammography)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/DH82/Awesome-Mammography/pulls)
[![GitHub stars](https://img.shields.io/github/stars/DH82/Awesome-Mammography?style=social)](https://github.com/DH82/Awesome-Mammography/stargazers)
[![Last Commit](https://img.shields.io/github/last-commit/DH82/Awesome-Mammography)](https://github.com/DH82/Awesome-Mammography/commits)
![Views](https://komarev.com/ghpvc/?username=DH82-Awesome-Mammography&label=Views&color=blue&style=flat)

![Datasets](https://img.shields.io/badge/Datasets-18-blue)
![Classification](https://img.shields.io/badge/Classification-19-orange)
![Detection & Segmentation](https://img.shields.io/badge/Detection%20%26%20Segmentation-16-red)
![Risk Prediction](https://img.shields.io/badge/Risk%20Prediction-20-purple)
![Foundation Model](https://img.shields.io/badge/Foundation%20Model-8-green)

A curated list of public datasets and key papers on deep learning for mammography.
It covers breast cancer classification, lesion detection and segmentation, risk prediction, and foundation models.
Each entry links to the paper, the code or data (if available), and a Public Venue entry.

- Papers are listed in their **published version** when one exists (not the preprint).
- Contributions are welcome. Please open an issue or a pull request.

## Contents
- [Mammography Dataset](#mammography-dataset)
- [Mammography Classification](#mammography-classification)
- [Mammography Detection, Segmentation](#mammography-detection-segmentation)
- [Mammography Risk Prediction](#mammography-risk-prediction)
- [Mammography Foundation Model](#mammography-foundation-model)

## Mammography Dataset

<table>
  <thead>
    <tr>
      <th>Dataset</th>
      <th>Data</th>
      <th>Info</th>
      <th>Public Venue</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>MIAS (Mammographic Image Analysis Society database)</td>
      <td><a href="https://www.kaggle.com/datasets/kmader/mias-mammography">Kaggle</a></td>
      <td>Digitized film · 161 subjects · UK</td>
      <td>
<details>
<summary>University of Cambridge Repository(2015)</summary>

```bibtex
@misc{suckling2015mammographic,
  title={Mammographic image analysis society (MIAS) database v1.21},
  author={Suckling, John and Parker, J and Dance, D and Astley, S and Hutt, I and Boggis, C and Ricketts, I and Stamatakis, E and Cerneaz, N and Kok, S and others},
  year={2015},
  publisher={University of Cambridge Repository}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td>DDSM (Digital Database for Screening Mammography)</td>
      <td><a href="http://www.eng.usf.edu/cvprg/mammography/database.html">USF</a></td>
      <td>Digitized film · 2,620 cases · USA</td>
      <td>
<details>
<summary>IWDM(2001)</summary>

```bibtex
@inproceedings{heath2001ddsm,
  title={The digital database for screening mammography},
  author={Heath, Michael and Bowyer, Kevin and Kopans, Daniel and Moore, Richard and Kegelmeyer, W Philip},
  booktitle={Proceedings of the 5th International Workshop on Digital Mammography (IWDM)},
  pages={212--218},
  year={2001},
  publisher={Medical Physics Publishing}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td><a href="https://doi.org/10.1016/j.acra.2011.09.014">INbreast</a></td>
      <td><a href="https://www.kaggle.com/datasets/tommyngx/inbreast2012">Kaggle</a></td>
      <td>FFDM · 115 subjects · Portugal</td>
      <td>
<details>
<summary>Academic Radiology(2012)</summary>

```bibtex
@article{moreira2012inbreast,
  title={INbreast: toward a full-field digital mammographic database},
  author={Moreira, In{\^e}s C and Amaral, Igor and Domingues, In{\^e}s and Cardoso, Ant{\'o}nio and Cardoso, Maria Jo{\~a}o and Cardoso, Jaime S},
  journal={Academic Radiology},
  volume={19},
  number={2},
  pages={236--248},
  year={2012},
  publisher={Elsevier},
  doi={10.1016/j.acra.2011.09.014}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td><a href="https://doi.org/10.1038/sdata.2017.177">CBIS-DDSM</a></td>
      <td><a href="https://www.cancerimagingarchive.net/collection/cbis-ddsm/">TCIA</a></td>
      <td>Digitized film · 6,775 subjects · USA</td>
      <td>
<details>
<summary>Scientific Data(2017)</summary>

```bibtex
@article{lee2017curated,
  title={A curated mammography data set for use in computer-aided detection and diagnosis research},
  author={Lee, Rebecca Sawyer and Gimenez, Francisco and Hoogi, Assaf and Miyake, Kanae Kawai and Gorovoy, Mia and Rubin, Daniel L},
  journal={Scientific Data},
  volume={4},
  number={1},
  pages={1--9},
  year={2017},
  publisher={Nature Publishing Group},
  doi={10.1038/sdata.2017.177}
}

@dataset{sawyerlee2016cbisddsm,
  author={Sawyer-Lee, Rebecca and Gimenez, Francisco and Hoogi, Assaf and Rubin, Daniel},
  title={Curated Breast Imaging Subset of Digital Database for Screening Mammography (CBIS-DDSM)},
  year={2016},
  publisher={The Cancer Imaging Archive},
  doi={10.7937/K9/TCIA.2016.7O02S9CY}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td>CSAW-S</td>
      <td><a href="https://zenodo.org/records/4030660">Zenodo</a></td>
      <td>FFDM · 281 subjects · Sweden</td>
      <td>
<details>
<summary>ICML(2020)</summary>

```bibtex
@inproceedings{matsoukas2020adding,
  title={Adding seemingly uninformative labels helps in low data regimes},
  author={Matsoukas, Christos and Hernandez, Albert Bou and Liu, Yue and Dembrower, Karin and Miranda, Gisele and Konuk, Emir and Haslum, Johan Fredin and Zouzos, Athanasios and Lindholm, Peter and Strand, Fredrik and others},
  booktitle={International Conference on Machine Learning},
  pages={6775--6784},
  year={2020},
  organization={PMLR}
}

@dataset{matsoukas2020csaws,
  author={Matsoukas, Christos and Hernandez, Albert Bou I and Liu, Yue and Dembrower, Karin and Miranda, Gisele and Konuk, Emir and Fredin Haslum, Johan and Zouzos, Athanasios and Lindholm, Peter and Strand, Fredrik and Smith, Kevin},
  title={CSAW-S},
  year={2020},
  publisher={Zenodo},
  version={1.0},
  doi={10.5281/zenodo.4030660}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td><a href="https://arxiv.org/abs/2112.01330">CSAW-M</a></td>
      <td><a href="https://figshare.scilifelab.se/articles/dataset/CSAW-M_An_Ordinal_Classification_Dataset_for_Benchmarking_Mammographic_Masking_of_Cancer/14687271">SciLifeLab Figshare</a></td>
      <td>FFDM · ~10,000 images · masking levels · Sweden</td>
      <td>
<details>
<summary>NeurIPS Datasets and Benchmarks(2021)</summary>

```bibtex
@inproceedings{sorkhei2021csawm,
  title={CSAW-M: An ordinal classification dataset for benchmarking mammographic masking of cancer},
  author={Sorkhei, Moein and Liu, Yue and Azizpour, Hossein and Azavedo, Edward and Dembrower, Karin and Ntoula, Dimitra and Zouzos, Athanasios and Strand, Fredrik and Smith, Kevin},
  booktitle={Proceedings of the Neural Information Processing Systems Track on Datasets and Benchmarks},
  year={2021}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td><a href="https://doi.org/10.1148/ryai.2020200103">OPTIMAM (OMI-DB, OPTIMAM Mammography Image Database)</a></td>
      <td><a href="https://medphys.royalsurrey.nhs.uk/omidb/">OMI-DB (access on request)</a></td>
      <td>FFDM (+ some DBT) · 172,282 subjects (as of May 2020) · UK</td>
      <td>
<details>
<summary>Radiology: Artificial Intelligence(2021)</summary>

```bibtex
@article{hallingbrown2021optimam,
  title={OPTIMAM Mammography Image Database: A Large-Scale Resource of Mammography Images and Clinical Data},
  author={Halling-Brown, Mark D and Warren, Lucy M and Ward, Dominic and Lewis, Emma and Mackenzie, Alistair and Wallis, Matthew G and Wilkinson, Louise S and Given-Wilson, Rosalind M and McAvinchey, Rita and Young, Kenneth C},
  journal={Radiology: Artificial Intelligence},
  volume={3},
  number={1},
  pages={e200103},
  year={2021},
  publisher={Radiological Society of North America},
  doi={10.1148/ryai.2020200103}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td><a href="https://doi.org/10.1001/jamanetworkopen.2021.19100">Breast Cancer Screening – DBT (BCS-DBT)</a></td>
      <td><a href="https://www.cancerimagingarchive.net/collection/breast-cancer-screening-dbt/">TCIA</a></td>
      <td>DBT · 5,060 subjects · USA</td>
      <td>
<details>
<summary>JAMA Network Open(2021)</summary>

```bibtex
@article{buda2021data,
  title={A data set and deep learning algorithm for the detection of masses and architectural distortions in digital breast tomosynthesis images},
  author={Buda, Mateusz and Saha, Ashirbani and Walsh, Ruth and Ghate, Sujata and Li, Nianyi and Swiecicki, Albert and Lo, Joseph Y and Mazurowski, Maciej A},
  journal={JAMA Network Open},
  volume={4},
  number={8},
  pages={e2119100},
  year={2021},
  publisher={American Medical Association},
  doi={10.1001/jamanetworkopen.2021.19100}
}

@dataset{buda2020dbt,
  author={Buda, M. and Saha, A. and Walsh, R. and Ghate, S. and Li, N. and Swiecicki, A. and Lo, J. Y. and Yang, J. and Mazurowski, M.},
  title={Breast Cancer Screening -- Digital Breast Tomosynthesis (BCS-DBT) (Version 5)},
  year={2020},
  publisher={The Cancer Imaging Archive},
  doi={10.7937/E4WT-CD02}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td>CMMD (Chinese Mammography Database)</td>
      <td><a href="https://www.cancerimagingarchive.net/collection/cmmd/">TCIA</a></td>
      <td>FFDM · 1,775 subjects · China</td>
      <td>
<details>
<summary>TCIA(2021)</summary>

```bibtex
@dataset{cui2021cmmd,
  author={Cui, Chunyan and Li, Li and Cai, Hongmin and Fan, Zhihao and Zhang, Ling and Dan, Tingting and Li, Jiao and Wang, Jinghua},
  title={The Chinese Mammography Database (CMMD): An online mammography database with biopsy confirmed types for machine diagnosis of breast},
  year={2021},
  publisher={The Cancer Imaging Archive},
  doi={10.7937/tcia.eqde-4b16}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td><a href="https://doi.org/10.3390/data6110111">KAU-BCMD</a></td>
      <td><a href="https://www.kaggle.com/datasets/orvile/kau-bcmd-mamography-dataset">Kaggle</a></td>
      <td>FFDM · 1,416 subjects · Saudi Arabia</td>
      <td>
<details>
<summary>Data(2021)</summary>

```bibtex
@article{alsolami2021king,
  title={King Abdulaziz University Breast Cancer Mammogram Dataset (KAU-BCMD)},
  author={Alsolami, Asmaa S and Shalash, Wafaa and Alsaggaf, Wafaa and Ashoor, Sawsan and Refaat, Haneen and Elmogy, Mohammed},
  journal={Data},
  volume={6},
  number={11},
  pages={111},
  year={2021},
  publisher={MDPI},
  doi={10.3390/data6110111}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td><a href="https://doi.org/10.1038/s41597-022-01238-0">CDD-CESM</a></td>
      <td><a href="https://www.cancerimagingarchive.net/collection/cdd-cesm/">TCIA</a></td>
      <td>CESM (low-energy + subtracted) · 326 subjects · Egypt</td>
      <td>
<details>
<summary>Scientific Data(2022)</summary>

```bibtex
@article{khaled2022categorized,
  title={Categorized contrast enhanced mammography dataset for diagnostic and artificial intelligence research},
  author={Khaled, Rana and Helal, Maha and Alfarghaly, Omar and Mokhtar, Omnia and Elkorany, Abeer and El Kassas, Hebatalla and Fahmy, Aly},
  journal={Scientific Data},
  volume={9},
  number={1},
  pages={122},
  year={2022},
  publisher={Nature Publishing Group},
  doi={10.1038/s41597-022-01238-0}
}

@dataset{khaled2021cddcesm,
  author={Khaled, Rana and Helal, Maha and Alfarghaly, Omar and Mokhtar, Omnia and Elkorany, Abeer and El Kassas, Hebatalla and Fahmy, Aly},
  title={Categorized Digital Database for Low energy and Subtracted Contrast Enhanced Spectral Mammography images},
  year={2021},
  publisher={The Cancer Imaging Archive},
  doi={10.7937/29kw-ae92}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td><a href="https://doi.org/10.1148/radiol.241447">RSNA Screening Mammography Breast Cancer Detection</a></td>
      <td><a href="https://www.kaggle.com/competitions/rsna-breast-cancer-detection/data">Kaggle</a></td>
      <td>FFDM · 8,000 subjects · USA</td>
      <td>
<details>
<summary>Kaggle(2022) / Radiology(2025)</summary>

```bibtex
@misc{rsna2022breastcancer,
  author={Carr, Chris and Kitamura, Felipe and Partridge, George and Kalpathy-Cramer, Jayashree and Mongan, John and Andriole, Katherine and Vazirabad, Maryam and Riopel, Michelle and Ball, Robyn and Dane, Sohier and Chen, Yan},
  title={RSNA Screening Mammography Breast Cancer Detection},
  year={2022},
  howpublished={\url{https://kaggle.com/competitions/rsna-breast-cancer-detection}},
  note={Kaggle}
}

@article{chen2025performance,
  title={Performance of Algorithms Submitted in the 2023 RSNA Screening Mammography Breast Cancer Detection AI Challenge},
  author={Chen, Yan and Partridge, George JW and Vazirabad, Maryam and Ball, Robyn L and Trivedi, Hari M and Kitamura, Felipe Campos and Frazer, Helen ML and Retson, Tara A and Yao, Luyan and Darker, Iain T and others},
  journal={Radiology},
  volume={316},
  number={2},
  pages={e241447},
  year={2025},
  publisher={Radiological Society of North America},
  doi={10.1148/radiol.241447}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td><a href="https://doi.org/10.1038/s41597-023-02100-7">VinDr-Mammo</a></td>
      <td><a href="https://www.physionet.org/content/vindr-mammo/1.0.0/">PhysioNet</a></td>
      <td>FFDM · 5,000 subjects · Vietnam</td>
      <td>
<details>
<summary>Scientific Data(2023)</summary>

```bibtex
@article{nguyen2023vindr,
  title={VinDr-Mammo: A large-scale benchmark dataset for computer-aided diagnosis in full-field digital mammography},
  author={Nguyen, Hieu T and Nguyen, Ha Q and Pham, Hieu H and Lam, Khanh and Le, Linh T and Dao, Minh and Vu, Van},
  journal={Scientific Data},
  volume={10},
  number={1},
  pages={277},
  year={2023},
  publisher={Nature Publishing Group UK London},
  doi={10.1038/s41597-023-02100-7}
}

@dataset{pham2022vindr,
  author={Pham, H. H. and Nguyen, Trung H. and Nguyen, H. Q.},
  title={VinDr-Mammo: A large-scale benchmark dataset for computer-aided detection and diagnosis in full-field digital mammography},
  year={2022},
  publisher={PhysioNet},
  doi={10.13026/br2v-7517}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td><a href="https://doi.org/10.1148/ryai.220047">EMBED (Emory Breast Imaging Dataset)</a></td>
      <td><a href="https://registry.opendata.aws/emory-breast-imaging-dataset-embed/">AWS Open Data</a></td>
      <td>FFDM · C-view · DBT · 110,000 subjects · USA</td>
      <td>
<details>
<summary>Radiology: Artificial Intelligence(2023)</summary>

```bibtex
@article{jeong2023emory,
  title={The EMory BrEast imaging Dataset (EMBED): A racially diverse, granular dataset of 3.4 million screening and diagnostic mammographic images},
  author={Jeong, Jiwoong J and Vey, Brianna L and Bhimireddy, Ananth and Kim, Thomas and Santos, Thiago and Correa, Ramon and Dutt, Raman and Mosunjac, Marina and Oprea-Ilies, Gabriela and Smith, Geoffrey and others},
  journal={Radiology: Artificial Intelligence},
  volume={5},
  number={1},
  pages={e220047},
  year={2023},
  publisher={Radiological Society of North America},
  doi={10.1148/ryai.220047}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td>DMID (Digital Mammography Dataset for Breast Cancer Diagnosis Research)</td>
      <td><a href="https://figshare.com/articles/dataset/_b_Digital_mammography_Dataset_for_Breast_Cancer_Diagnosis_Research_DMID_b_DMID_rar/24522883">Figshare</a></td>
      <td>FFDM · 510 subjects · India</td>
      <td>
<details>
<summary>Biomedical Engineering Letters(2024)</summary>

```bibtex
@article{oza2024digital,
  title={Digital mammography dataset for breast cancer diagnosis research (DMID) with breast mass segmentation analysis},
  author={Oza, Parita and Oza, Urvi and Oza, Rajiv and Sharma, Paawan and Patel, Samir and Kumar, Pankaj and Gohel, Bakul},
  journal={Biomedical Engineering Letters},
  volume={14},
  number={2},
  pages={317--330},
  year={2024},
  publisher={Springer}
}

@dataset{oza2023dmid,
  author={Oza, Parita and Oza, Rajiv and Oza, Urvi and Sharma, Paawan and Patel, Samir and Kumar, Pankaj and Gohel, Bakul},
  title={Digital Mammography Dataset for Breast Cancer Diagnosis Research (DMID)},
  year={2023},
  doi={10.6084/m9.figshare.24522883.v2}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td>Mammo-Bench</td>
      <td><a href="https://india-data.org/dataset-details/c86fb00c-0fb8-4e0e-85a2-4d415f9c1ada">IndiaAI</a></td>
      <td>FFDM (multi-source benchmark) · 6,500 subjects · India</td>
      <td>
<details>
<summary>medRxiv(2025)</summary>

```bibtex
@article{bhole2025mammo,
  title={Mammo-Bench: A Large-scale Benchmark Dataset of Mammography Images},
  author={Bhole, Gaurav and Suba, S and Parekh, Nita},
  journal={medRxiv},
  year={2025},
  publisher={Cold Spring Harbor Laboratory Press}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td>TOMPEI-CMMD</td>
      <td><a href="https://www.cancerimagingarchive.net/analysis-result/tompei-cmmd/">TCIA</a></td>
      <td>Extra annotations for CMMD (analysis result) · 1,363 subjects · China</td>
      <td>
<details>
<summary>TCIA(2025)</summary>

```bibtex
@dataset{kashiwada2025tompei,
  author={Kashiwada, Y. and Takaya, E. and Hiroya, M. and Matsuda, N. and Yashima, T. and Kobayashi, T. and Tamiya, G. and Ueda, T.},
  title={TOMPEI-CMMD Dataset (Version 1)},
  year={2025},
  publisher={The Cancer Imaging Archive},
  doi={10.7937/WEZW-BH22}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td><a href="https://openaccess.thecvf.com/content/CVPR2026/html/Pan_LUMINA_A_Multi-Vendor_Mammography_Benchmark_with_Energy_Harmonization_Protocol_CVPR_2026_paper.html">LUMINA</a></td>
      <td><a href="https://www.kaggle.com/datasets/phy710/lumina-mammography-dataset">Kaggle</a> · <a href="https://osf.io/b63jc/">OSF</a> · <a href="https://github.com/NUBagciLab/LUMINA">Github</a></td>
      <td>FFDM (6 vendors, high/low-energy) · 468 subjects · 1,824 images · Turkey</td>
      <td>
<details>
<summary>CVPR(2026)</summary>

```bibtex
@inproceedings{pan2026lumina,
  title={LUMINA: A Multi-Vendor Mammography Benchmark with Energy Harmonization Protocol},
  author={Pan, Hongyi and Durak, Gorkem and Aktas, Halil Ertugrul and Bejar, Andrea M. and Tutun, Baver and Uysal, Emre and Bulbul, Ezgi and Dogan, Mehmet Fatih and Erok, Berrin and Yildirim, Berna Akkus and Erturk, Sukru Mehmet and Bagci, Ulas},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
  pages={35301--35310},
  year={2026}
}
```
</details>
      </td>
    </tr>
  </tbody>
</table>

## Mammography Classification

<table>
  <thead>
    <tr>
      <th>Paper</th>
      <th>Code</th>
      <th>Public Venue</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="https://doi.org/10.1093/jnci/djy222">Stand-Alone Artificial Intelligence for Breast Cancer Detection in Mammography: Comparison With 101 Radiologists</a></td>
      <td>N/A</td>
      <td>
<details>
<summary>JNCI(2019)</summary>

```bibtex
@article{rodriguezruiz2019standalone,
  title={Stand-alone artificial intelligence for breast cancer detection in mammography: comparison with 101 radiologists},
  author={Rodriguez-Ruiz, Alejandro and L{\aa}ng, Kristina and Gubern-Merida, Albert and others},
  journal={Journal of the National Cancer Institute},
  volume={111},
  number={9},
  pages={916--922},
  year={2019},
  publisher={Oxford University Press},
  doi={10.1093/jnci/djy222}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td>[Density] <a href="https://doi.org/10.1148/radiol.2018180694">Mammographic Breast Density Assessment Using Deep Learning: Clinical Implementation</a></td>
      <td>N/A</td>
      <td>
<details>
<summary>Radiology(2019)</summary>

```bibtex
@article{lehman2019mammographic,
  title={Mammographic breast density assessment using deep learning: clinical implementation},
  author={Lehman, Constance D and Yala, Adam and Schuster, Tal and others},
  journal={Radiology},
  volume={290},
  number={1},
  pages={52--58},
  year={2019},
  publisher={Radiological Society of North America},
  doi={10.1148/radiol.2018180694}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td><a href="https://doi.org/10.1038/s41598-019-48995-4">Deep Learning to Improve Breast Cancer Detection on Screening Mammography</a></td>
      <td><a href="https://github.com/lishen/end2end-all-conv">Github</a></td>
      <td>
<details>
<summary>Scientific Reports(2019)</summary>

```bibtex
@article{shen2019deep,
  title={Deep learning to improve breast cancer detection on screening mammography},
  author={Shen, Li and Margolies, Laurie R and Rothstein, Joseph H and Fluder, Eugene and McBride, Russell and Sieh, Weiva},
  journal={Scientific Reports},
  volume={9},
  pages={12495},
  year={2019},
  publisher={Nature Publishing Group}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td><a href="https://doi.org/10.1038/s41586-019-1799-6">International evaluation of an AI system for breast cancer screening</a></td>
      <td>N/A</td>
      <td>
<details>
<summary>Nature(2020)</summary>

```bibtex
@article{mckinney2020international,
  title={International evaluation of an AI system for breast cancer screening},
  author={McKinney, Scott Mayer and Sieniek, Marcin and Godbole, Varun and others},
  journal={Nature},
  volume={577},
  pages={89--94},
  year={2020},
  publisher={Nature Publishing Group}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td><a href="https://doi.org/10.1016/S2589-7500(20)30003-0">Changes in cancer detection and false-positive recall in mammography using artificial intelligence: a retrospective, multireader study</a></td>
      <td>N/A</td>
      <td>
<details>
<summary>Lancet Digital Health(2020)</summary>

```bibtex
@article{kim2020changes,
  title={Changes in cancer detection and false-positive recall in mammography using artificial intelligence: a retrospective, multireader study},
  author={Kim, Hyo-Eun and Kim, Hak Hee and Han, Boo-Kyung and others},
  journal={The Lancet Digital Health},
  volume={2},
  number={3},
  pages={e138--e148},
  year={2020},
  publisher={Elsevier},
  doi={10.1016/S2589-7500(20)30003-0}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td><a href="https://doi.org/10.1001/jamanetworkopen.2020.0265">Evaluation of Combined Artificial Intelligence and Radiologist Assessment to Interpret Screening Mammograms (DREAM Challenge)</a></td>
      <td>N/A</td>
      <td>
<details>
<summary>JAMA Network Open(2020)</summary>

```bibtex
@article{schaffter2020evaluation,
  title={Evaluation of combined artificial intelligence and radiologist assessment to interpret screening mammograms},
  author={Schaffter, Thomas and Buist, Diana SM and Lee, Christoph I and others},
  journal={JAMA Network Open},
  volume={3},
  number={3},
  pages={e200265},
  year={2020},
  publisher={American Medical Association},
  doi={10.1001/jamanetworkopen.2020.0265}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td><a href="https://doi.org/10.1109/TMI.2019.2945514">Deep Neural Networks Improve Radiologists' Performance in Breast Cancer Screening</a></td>
      <td><a href="https://github.com/nyukat/breast_cancer_classifier">Github</a></td>
      <td>
<details>
<summary>IEEE TMI(2020)</summary>

```bibtex
@article{wu2020deep,
  title={Deep neural networks improve radiologists' performance in breast cancer screening},
  author={Wu, Nan and Phang, Jason and Park, Jungkyu and Shen, Yiqiu and Huang, Zhe and Zorin, Masha and Jastrz{\k{e}}bski, Stanis{\l}aw and F{\'e}vry, Thibault and Katsnelson, Joe and Kim, Eric and others},
  journal={IEEE Transactions on Medical Imaging},
  volume={39},
  number={4},
  pages={1184--1194},
  year={2020}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td><a href="https://doi.org/10.1038/s41591-020-01174-9">Robust breast cancer detection in mammography and digital breast tomosynthesis using an annotation-efficient deep learning approach</a></td>
      <td>N/A</td>
      <td>
<details>
<summary>Nature Medicine(2021)</summary>

```bibtex
@article{lotter2021robust,
  title={Robust breast cancer detection in mammography and digital breast tomosynthesis using an annotation-efficient deep learning approach},
  author={Lotter, William and others},
  journal={Nature Medicine},
  volume={27},
  pages={244--249},
  year={2021},
  publisher={Nature Publishing Group}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td><a href="https://doi.org/10.1016/j.media.2020.101908">An interpretable classifier for high-resolution breast cancer screening images utilizing weakly supervised localization (GMIC)</a></td>
      <td><a href="https://github.com/nyukat/GMIC">Github</a></td>
      <td>
<details>
<summary>Medical Image Analysis(2021)</summary>

```bibtex
@article{shen2021interpretable,
  title={An interpretable classifier for high-resolution breast cancer screening images utilizing weakly supervised localization},
  author={Shen, Yiqiu and Wu, Nan and Phang, Jason and Park, Jungkyu and Liu, Kangning and Tyagi, Sudarshini and Heacock, Laura and Kim, S Gene and Moy, Linda and Cho, Kyunghyun and Geras, Krzysztof J},
  journal={Medical Image Analysis},
  volume={68},
  pages={101908},
  year={2021},
  publisher={Elsevier},
  doi={10.1016/j.media.2020.101908}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td><a href="https://doi.org/10.1007/978-3-030-87199-4_10">Multi-view analysis of unregistered medical images using cross-view transformers</a></td>
      <td><a href="https://github.com/gvtulder/cross-view-transformers">Github</a></td>
      <td>
<details>
<summary>MICCAI(2021)</summary>

```bibtex
@inproceedings{vantulder2021multi,
  title={Multi-view analysis of unregistered medical images using cross-view transformers},
  author={van Tulder, Gijs and Tong, Yao and Marchiori, Elena},
  booktitle={Medical Image Computing and Computer Assisted Intervention -- MICCAI 2021},
  volume={12903},
  pages={104--113},
  year={2021},
  publisher={Springer Nature Switzerland}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td><a href="https://doi.org/10.1007/978-3-031-16437-8_1">Multi-view Local Co-occurrence and Global Consistency Learning Improve Mammogram Classification Generalisation (BRAIxMVCCL)</a></td>
      <td>N/A</td>
      <td>
<details>
<summary>MICCAI(2022)</summary>

```bibtex
@inproceedings{chen2022multi,
  title={Multi-view local co-occurrence and global consistency learning improve mammogram classification generalisation},
  author={Chen, Yuanhong and Wang, Hu and Wang, Chong and Tian, Yu and Liu, Fengbei and Liu, Yuyuan and Elliott, Michael and McCarthy, Davis J and Frazer, Helen and Carneiro, Gustavo},
  booktitle={Medical Image Computing and Computer Assisted Intervention -- MICCAI 2022},
  volume={13433},
  pages={3--13},
  year={2022},
  publisher={Springer Nature Switzerland}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td>[Clinical trial] <a href="https://doi.org/10.1016/S1470-2045(23)00298-X">Artificial intelligence-supported screen reading versus standard double reading in the Mammography Screening with Artificial Intelligence trial (MASAI)</a></td>
      <td>N/A</td>
      <td>
<details>
<summary>Lancet Oncology(2023)</summary>

```bibtex
@article{lang2023artificial,
  title={Artificial intelligence-supported screen reading versus standard double reading in the Mammography Screening with Artificial Intelligence trial (MASAI): a clinical safety analysis of a randomised, controlled, non-inferiority, single-blinded, screening accuracy study},
  author={L{\aa}ng, Kristina and Josefsson, Viktoria and Larsson, Anna-Maria and others},
  journal={The Lancet Oncology},
  volume={24},
  number={8},
  pages={936--944},
  year={2023},
  publisher={Elsevier},
  doi={10.1016/S1470-2045(23)00298-X}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td>[Clinical trial] <a href="https://doi.org/10.1016/S2589-7500(23)00153-X">Artificial intelligence for breast cancer detection in screening mammography in Sweden: a prospective, population-based, paired-reader, non-inferiority study (ScreenTrustCAD)</a></td>
      <td>N/A</td>
      <td>
<details>
<summary>Lancet Digital Health(2023)</summary>

```bibtex
@article{dembrower2023artificial,
  title={Artificial intelligence for breast cancer detection in screening mammography in Sweden: a prospective, population-based, paired-reader, non-inferiority study},
  author={Dembrower, Karin and Crippa, Alessio and Col{\'o}n, Eugenia and others},
  journal={The Lancet Digital Health},
  volume={5},
  number={10},
  pages={e703--e711},
  year={2023},
  publisher={Elsevier},
  doi={10.1016/S2589-7500(23)00153-X}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td><a href="https://doi.org/10.1109/TMI.2023.3306781">An Interpretable and Accurate Deep-Learning Diagnosis Framework Modeled With Fully and Semi-Supervised Reciprocal Learning (BRAIxProtoPNet++)</a></td>
      <td>N/A</td>
      <td>
<details>
<summary>IEEE TMI(2024)</summary>

```bibtex
@article{wang2024interpretable,
  title={An interpretable and accurate deep-learning diagnosis framework modeled with fully and semi-supervised reciprocal learning},
  author={Wang, Chong and Chen, Yuanhong and Liu, Fengbei and Elliott, Michael and Kwok, Chun Fung and Pe{\~n}a-Sol{\'o}rzano, Carlos A and Frazer, Helen and McCarthy, Davis James and Carneiro, Gustavo},
  journal={IEEE Transactions on Medical Imaging},
  volume={43},
  number={1},
  pages={392--404},
  year={2024},
  doi={10.1109/TMI.2023.3306781}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td><a href="https://doi.org/10.1109/ISBI56570.2024.10635578">MV-Swin-T: Mammogram Classification with Multi-view Swin Transformer</a></td>
      <td><a href="https://github.com/prithuls/MV-Swin-T">Github</a></td>
      <td>
<details>
<summary>ISBI(2024)</summary>

```bibtex
@inproceedings{sarker2024mvswint,
  title={MV-Swin-T: Mammogram classification with multi-view swin transformer},
  author={Sarker, Sushmita and Sarker, Prithul and Bebis, George and Tavakkoli, Alireza},
  booktitle={IEEE International Symposium on Biomedical Imaging (ISBI)},
  pages={1--5},
  year={2024},
  doi={10.1109/ISBI56570.2024.10635578}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td><a href="https://papers.miccai.org/miccai-2024/337-Paper1306.html">Follow the Radiologist: Clinically Relevant Multi-View Cues for Breast Cancer Detection from Mammograms (CEN)</a></td>
      <td><a href="https://github.com/Mammo-IITD-AIIMS/CEN">Github</a></td>
      <td>
<details>
<summary>MICCAI(2024)</summary>

```bibtex
@inproceedings{jain2024follow,
  title={Follow the radiologist: Clinically relevant multi-view cues for breast cancer detection from mammograms},
  author={Jain, Kshitiz and Rangarajan, Krithika and Arora, Chetan},
  booktitle={Medical Image Computing and Computer Assisted Intervention -- MICCAI 2024},
  volume={15001},
  pages={102--112},
  year={2024},
  publisher={Springer Nature Switzerland}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td><a href="https://doi.org/10.1016/j.media.2024.103320">Mammography classification with multi-view deep learning techniques: Investigating graph and transformer-based architectures</a></td>
      <td>N/A</td>
      <td>
<details>
<summary>Medical Image Analysis(2025)</summary>

```bibtex
@article{manigrasso2025mammography,
  title={Mammography classification with multi-view deep learning techniques: Investigating graph and transformer-based architectures},
  author={Manigrasso, Francesco and Milazzo, Rosario and Russo, Alessandro Sebastian and Lamberti, Fabrizio and Strand, Fredrik and Pagnani, Andrea and Morra, Lia},
  journal={Medical Image Analysis},
  volume={99},
  pages={103320},
  year={2025},
  publisher={Elsevier}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td>[Clinical study] <a href="https://doi.org/10.1038/s41591-024-03408-6">Nationwide real-world implementation of AI for cancer detection in population-based mammography screening (PRAIM)</a></td>
      <td>N/A</td>
      <td>
<details>
<summary>Nature Medicine(2025)</summary>

```bibtex
@article{eisemann2025nationwide,
  title={Nationwide real-world implementation of AI for cancer detection in population-based mammography screening},
  author={Eisemann, Nora and Bunk, Stefan and Mukama, Trasias and others},
  journal={Nature Medicine},
  volume={31},
  number={3},
  pages={917--924},
  year={2025},
  publisher={Nature Publishing Group},
  doi={10.1038/s41591-024-03408-6}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td><a href="https://arxiv.org/abs/2503.19945">Optimizing Breast Cancer Detection in Mammograms: A Comprehensive Study of Transfer Learning, Resolution Reduction, and Multi-View Classification</a></td>
      <td><a href="https://github.com/dpetrini/multiple-view">Github</a></td>
      <td>
<details>
<summary>arXiv(2025)</summary>

```bibtex
@article{petrini2025optimizing,
  title={Optimizing breast cancer detection in mammograms: A comprehensive study of transfer learning, resolution reduction, and multi-view classification},
  author={Petrini, Daniel G P and Kim, Hae Yong},
  journal={arXiv preprint arXiv:2503.19945},
  year={2025}
}
```
</details>
      </td>
    </tr>
  </tbody>
</table>

## Mammography Detection, Segmentation

<table>
  <thead>
    <tr>
      <th>Paper</th>
      <th>Code</th>
      <th>Public Venue</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>[Detection] <a href="https://doi.org/10.1016/j.media.2016.07.007">Large scale deep learning for computer aided detection of mammographic lesions</a></td>
      <td>N/A</td>
      <td>
<details>
<summary>Medical Image Analysis(2017)</summary>

```bibtex
@article{kooi2017large,
  title={Large scale deep learning for computer aided detection of mammographic lesions},
  author={Kooi, Thijs and Litjens, Geert and van Ginneken, Bram and others},
  journal={Medical Image Analysis},
  volume={35},
  pages={303--312},
  year={2017},
  publisher={Elsevier},
  doi={10.1016/j.media.2016.07.007}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td>[Detection] <a href="https://doi.org/10.1038/s41598-018-22437-z">Detecting and classifying lesions in mammograms with Deep Learning</a></td>
      <td><a href="https://github.com/riblidezso/frcnn_cad">Github</a></td>
      <td>
<details>
<summary>Scientific Reports(2018)</summary>

```bibtex
@article{ribli2018detecting,
  title={Detecting and classifying lesions in mammograms with deep learning},
  author={Ribli, Dezs{\H{o}} and Horv{\'a}th, Anna and Unger, Zsuzsa and Pollner, P{\'e}ter and Csabai, Istv{\'a}n},
  journal={Scientific Reports},
  volume={8},
  pages={4165},
  year={2018},
  publisher={Nature Publishing Group}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td>[Segmentation] <a href="https://doi.org/10.1109/ISBI.2018.8363704">Adversarial Deep Structured Nets for Mass Segmentation from Mammograms</a></td>
      <td><a href="https://github.com/wentaozhu/adversarial-deep-structural-networks">Github</a></td>
      <td>
<details>
<summary>ISBI(2018)</summary>

```bibtex
@inproceedings{zhu2018adversarial,
  title={Adversarial deep structured nets for mass segmentation from mammograms},
  author={Zhu, Wentao and Xiang, Xiang and Tran, Trac D and Hager, Gregory D and Xie, Xiaohui},
  booktitle={IEEE International Symposium on Biomedical Imaging (ISBI)},
  pages={847--850},
  year={2018},
  doi={10.1109/ISBI.2018.8363704}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td>[Detection] <a href="https://doi.org/10.1371/journal.pone.0203355">Detection of masses in mammograms using a one-stage object detector based on a deep convolutional neural network</a></td>
      <td>N/A</td>
      <td>
<details>
<summary>PLOS ONE(2018)</summary>

```bibtex
@article{jung2018detection,
  title={Detection of masses in mammograms using a one-stage object detector based on a deep convolutional neural network},
  author={Jung, Hwejin and Kim, Bumsoo and Lee, Inyeop and Yoo, Minhwan and Lee, Junhyun and Ham, Sooyoun and Woo, Okhee and Kang, Jaewoo},
  journal={PLOS ONE},
  volume={13},
  number={9},
  pages={e0203355},
  year={2018}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td>[Segmentation] <a href="https://doi.org/10.1088/1361-6560/ab5745">AUNet: Attention-guided dense-upsampling networks for breast mass segmentation in whole mammograms</a></td>
      <td>N/A</td>
      <td>
<details>
<summary>Physics in Medicine & Biology(2020)</summary>

```bibtex
@article{sun2020aunet,
  title={AUNet: attention-guided dense-upsampling networks for breast mass segmentation in whole mammograms},
  author={Sun, Hui and Li, Cheng and Liu, Boqiang and Liu, Zaiyi and Luo, Jianhua and Zheng, Hairong and Feng, David Dagan and Wang, Shanshan},
  journal={Physics in Medicine \& Biology},
  volume={65},
  number={5},
  pages={055005},
  year={2020},
  publisher={IOP Publishing},
  doi={10.1088/1361-6560/ab5745}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td>[Detection / Segmentation] <a href="https://doi.org/10.1109/ICCVW.2019.00047">DeepLIMa: Deep Learning Based Lesion Identification in Mammograms</a></td>
      <td>N/A</td>
      <td>
<details>
<summary>ICCV Workshops(2019)</summary>

```bibtex
@inproceedings{cao2019deeplima,
  title={DeepLIMa: Deep learning based lesion identification in mammograms},
  author={Cao, Zhenjie and Yang, Zhicheng and Zhuo, Xiaoyan and Lin, Ruei-Sung and Wu, Shibin and Huang, Lingyun and Han, Mei and Zhang, Yanbo and Ma, Jie},
  booktitle={IEEE/CVF International Conference on Computer Vision Workshops (ICCVW)},
  pages={362--370},
  year={2019}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td>[Detection / Segmentation] <a href="https://doi.org/10.1016/j.bbe.2021.03.005">Two-stage multi-scale breast mass segmentation for full mammogram analysis without user intervention</a></td>
      <td>N/A</td>
      <td>
<details>
<summary>Biocybernetics and Biomedical Engineering(2021)</summary>

```bibtex
@article{yan2021two,
  title={Two-stage multi-scale breast mass segmentation for full mammogram analysis without user intervention},
  author={Yan, Yutong and Conze, Pierre-Henri and Quellec, Gwenol{\'e} and Lamard, Mathieu and Cochener, B{\'e}atrice and Coatrieux, Gouenou},
  journal={Biocybernetics and Biomedical Engineering},
  volume={41},
  number={2},
  pages={746--757},
  year={2021},
  publisher={Elsevier},
  doi={10.1016/j.bbe.2021.03.005}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td>[Detection] <a href="https://doi.org/10.1109/CVPR42600.2020.00387">Cross-View Correspondence Reasoning Based on Bipartite Graph Convolutional Network for Mammogram Mass Detection (BG-RCNN)</a></td>
      <td>N/A</td>
      <td>
<details>
<summary>CVPR(2020)</summary>

```bibtex
@inproceedings{liu2020cross,
  title={Cross-view correspondence reasoning based on bipartite graph convolutional network for mammogram mass detection},
  author={Liu, Yuhang and Zhang, Fandong and Zhang, Qianyi and Wang, Siwen and Wang, Yizhou and Yu, Yizhou},
  booktitle={IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
  pages={3811--3821},
  year={2020}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td>[Detection] <a href="https://doi.org/10.1109/ICPR48806.2021.9413132">Cross-View Relation Networks for Mammogram Mass Detection (CVR-RCNN)</a></td>
      <td>N/A</td>
      <td>
<details>
<summary>ICPR(2020)</summary>

```bibtex
@inproceedings{ma2021cross,
  title={Cross-view relation networks for mammogram mass detection},
  author={Ma, Jiechao and Li, Xiang and Li, Hongwei and Wang, Ruixuan and Menze, Bjoern and Zheng, Wei-Shi},
  booktitle={International Conference on Pattern Recognition (ICPR)},
  pages={8632--8638},
  year={2021},
  doi={10.1109/ICPR48806.2021.9413132}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td>[Segmentation] <a href="https://doi.org/10.1002/mp.15017">SCU-Net: A deep learning method for segmentation and quantification of breast arterial calcifications on mammograms</a></td>
      <td><a href="https://github.com/XiaoyuanGuo/BAC_segmentation">Github</a></td>
      <td>
<details>
<summary>Medical Physics(2021)</summary>

```bibtex
@article{guo2021scunet,
  title={SCU-Net: A deep learning method for segmentation and quantification of breast arterial calcifications on mammograms},
  author={Guo, Xiaoyuan and others},
  journal={Medical Physics},
  volume={48},
  number={10},
  pages={5851--5861},
  year={2021},
  publisher={Wiley},
  doi={10.1002/mp.15017}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td>[Detection] <a href="https://doi.org/10.1001/jamanetworkopen.2021.19100">A Data Set and Deep Learning Algorithm for the Detection of Masses and Architectural Distortions in Digital Breast Tomosynthesis Images</a></td>
      <td><a href="https://github.com/mateuszbuda/duke-dbt-detection">Github</a></td>
      <td>
<details>
<summary>JAMA Network Open(2021)</summary>

```bibtex
@article{buda2021data,
  title={A data set and deep learning algorithm for the detection of masses and architectural distortions in digital breast tomosynthesis images},
  author={Buda, Mateusz and Saha, Ashirbani and Walsh, Ruth and Ghate, Sujata and Li, Nianyi and {\'S}wi{\k{e}}cicki, Albert and Lo, Joseph Y and Mazurowski, Maciej A},
  journal={JAMA Network Open},
  volume={4},
  number={8},
  pages={e2119100},
  year={2021},
  publisher={American Medical Association}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td>[Segmentation] <a href="https://doi.org/10.1038/s41523-021-00358-x">Connected-UNets: a deep learning architecture for breast mass segmentation</a></td>
      <td>N/A</td>
      <td>
<details>
<summary>npj Breast Cancer(2021)</summary>

```bibtex
@article{baccouche2021connected,
  title={Connected-UNets: a deep learning architecture for breast mass segmentation},
  author={Baccouche, Asma and Garcia-Zapirain, Begonya and Castillo Olea, Cristian and Elmaghraby, Adel S},
  journal={npj Breast Cancer},
  volume={7},
  pages={151},
  year={2021},
  publisher={Nature Publishing Group}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td>[Detection] <a href="https://doi.org/10.1109/TPAMI.2021.3085783">Act Like a Radiologist: Towards Reliable Multi-view Correspondence Reasoning for Mammogram Mass Detection (AG-RCNN)</a></td>
      <td>N/A</td>
      <td>
<details>
<summary>IEEE TPAMI(2022)</summary>

```bibtex
@article{liu2022act,
  title={Act like a radiologist: towards reliable multi-view correspondence reasoning for mammogram mass detection},
  author={Liu, Yuhang and Zhang, Fandong and Chen, Chaoqi and Wang, Siwen and Wang, Yizhou and Yu, Yizhou},
  journal={IEEE Transactions on Pattern Analysis and Machine Intelligence},
  volume={44},
  number={10},
  pages={5947--5961},
  year={2022}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td>[Detection] <a href="https://doi.org/10.1007/978-3-031-43904-9_75">M&amp;M: Tackling False Positives in Mammography with a Multi-view and Multi-instance Learning Sparse Detector</a></td>
      <td>N/A</td>
      <td>
<details>
<summary>MICCAI(2023)</summary>

```bibtex
@inproceedings{truongvu2023mm,
  title={M\&M: Tackling false positives in mammography with a multi-view and multi-instance learning sparse detector},
  author={Truong Vu, Yen Nhi and Guo, Dan and Taha, Ahmed and Su, Jason and Matthews, Thomas Paul},
  booktitle={Medical Image Computing and Computer Assisted Intervention -- MICCAI 2023},
  pages={778--788},
  year={2023},
  publisher={Springer Nature Switzerland},
  doi={10.1007/978-3-031-43904-9_75}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td>[Detection] <a href="https://doi.org/10.1016/j.media.2024.103192">BRAIxDet: Learning to Detect Malignant Breast Lesion with Incomplete Annotations</a></td>
      <td>N/A</td>
      <td>
<details>
<summary>Medical Image Analysis(2024)</summary>

```bibtex
@article{chen2024braixdet,
  title={BRAIxDet: Learning to detect malignant breast lesion with incomplete annotations},
  author={Chen, Yuanhong and Liu, Yuyuan and Wang, Chong and Elliott, Michael and Kwok, Chun Fung and Pe{\~n}a-Solorzano, Carlos and Tian, Yu and Liu, Fengbei and Frazer, Helen and McCarthy, Davis J and Carneiro, Gustavo},
  journal={Medical Image Analysis},
  volume={96},
  pages={103192},
  year={2024},
  publisher={Elsevier},
  doi={10.1016/j.media.2024.103192}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td>[Detection] <a href="https://doi.org/10.1007/978-3-032-05559-0_26">MM-DETR: Emulating the Diagnostic Clinical Workflow in Multi-view Multi-modal Mammography Mass Detection</a></td>
      <td>N/A</td>
      <td>
<details>
<summary>MICCAI Deep-Breast Workshop(2025)</summary>

```bibtex
@inproceedings{elbarbary2025mmdetr,
  title={MM-DETR: Emulating the diagnostic clinical workflow in multi-view multi-modal mammography mass detection},
  author={Elbarbary, K and Bhandary Panambur, A and Bhat, S and Bayer, S and Maier, A},
  booktitle={Artificial Intelligence and Imaging for Diagnostic and Treatment Challenges in Breast Care (Deep-Breast 2025)},
  volume={16142},
  pages={258--267},
  year={2025},
  publisher={Springer}
}
```
</details>
      </td>
    </tr>
  </tbody>
</table>

## Mammography Risk Prediction

<table>
  <thead>
    <tr>
      <th>Paper</th>
      <th>Code</th>
      <th>Public Venue</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="https://pubs.rsna.org/doi/pdf/10.1148/radiol.2019182716">A Deep Learning Mammography-based Model for Improved Breast Cancer Risk Prediction</a></td>
      <td>N/A</td>
      <td>
<details>
<summary>Radiology(2019)</summary>

```bibtex
@article{yala2019deep,
  title={A deep learning mammography-based model for improved breast cancer risk prediction},
  author={Yala, Adam and Lehman, Constance and Schuster, Tal and Portnoi, Tally and Barzilay, Regina},
  journal={Radiology},
  volume={292},
  number={1},
  pages={60--66},
  year={2019},
  publisher={Radiological Society of North America}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td><a href="https://doi.org/10.1002/mp.13886">Deep learning modeling using normal mammograms for predicting breast cancer risk</a></td>
      <td>N/A</td>
      <td>
<details>
<summary>Medical Physics(2020)</summary>

```bibtex
@article{arefan2020deep,
  title={Deep learning modeling using normal mammograms for predicting breast cancer risk},
  author={Arefan, Dooman and Mohamed, Aly A and Berg, Wendie A and Zuley, Margarita L and Sumkin, Jules H and Wu, Shandong},
  journal={Medical Physics},
  volume={47},
  number={1},
  pages={110--118},
  year={2020},
  publisher={Wiley}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td><a href="https://doi.org/10.1148/radiol.2019190872">Comparison of a Deep Learning Risk Score and Standard Mammographic Density Score for Breast Cancer Risk Prediction</a></td>
      <td>N/A</td>
      <td>
<details>
<summary>Radiology(2020)</summary>

```bibtex
@article{dembrower2020comparison,
  title={Comparison of a deep learning risk score and standard mammographic density score for breast cancer risk prediction},
  author={Dembrower, Karin and Liu, Yue and Azizpour, Hossein and Eklund, Martin and Smith, Kevin and Lindholm, Peter and Strand, Fredrik},
  journal={Radiology},
  volume={294},
  number={2},
  pages={265--272},
  year={2020},
  publisher={Radiological Society of North America}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td><a href="https://doi.org/10.1148/radiol.2020201620">Identification of Women at High Risk of Breast Cancer Who Need Supplemental Screening</a></td>
      <td>N/A</td>
      <td>
<details>
<summary>Radiology(2020)</summary>

```bibtex
@article{eriksson2020identification,
  title={Identification of women at high risk of breast cancer who need supplemental screening},
  author={Eriksson, Mikael and Czene, Kamila and Strand, Fredrik and Zackrisson, Sophia and Lindholm, Peter and L{\aa}ng, Kristina and F{\"o}rnvik, Daniel and Sartor, Hanna and Mavaddat, Nasim and Easton, Doug and Hall, Per},
  journal={Radiology},
  volume={297},
  number={2},
  pages={327--333},
  year={2020},
  publisher={Radiological Society of North America}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td><a href="https://www.science.org/doi/10.1126/scitranslmed.aba4373">Toward robust mammography-based models for breast cancer risk</a></td>
      <td><a href="https://github.com/reginabarzilaygroup/Mirai.git">Github</a></td>
      <td>
<details>
<summary>Science Translational Medicine(2021)</summary>

```bibtex
@article{yala2021toward,
  title={Toward robust mammography-based models for breast cancer risk},
  author={Yala, Adam and Mikhael, Peter G and Strand, Fredrik and Lin, Gigin and Smith, Kevin and Wan, Yung-Liang and Lamb, Leslie and Hughes, Kevin and Lehman, Constance and Barzilay, Regina},
  journal={Science translational medicine},
  volume={13},
  number={578},
  pages={eaba4373},
  year={2021},
  publisher={American Association for the Advancement of Science}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td><a href="https://doi.org/10.1148/radiol.2021203758">Deep Learning Predicts Interval and Screening-detected Cancer from Screening Mammograms: A Case-Case-Control Study in 6369 Women</a></td>
      <td>N/A</td>
      <td>
<details>
<summary>Radiology(2021)</summary>

```bibtex
@article{zhu2021deep,
  title={Deep learning predicts interval and screening-detected cancer from screening mammograms: a case-case-control study in 6369 women},
  author={Zhu, Xun and Wolfgruber, Thomas K and Leong, Lambert and Jensen, Matthew and Scott, Christopher and Winham, Stacey and Sadowski, Peter and Vachon, Celine and Kerlikowske, Karla and Shepherd, John A},
  journal={Radiology},
  volume={301},
  number={3},
  pages={550--558},
  year={2021},
  publisher={Radiological Society of North America}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td><a href="https://www.nature.com/articles/s41591-021-01599-w">Optimizing risk-based breast cancer screening policies with reinforcement learning</a></td>
      <td><a href="https://github.com/yala/Tempo">Github</a></td>
      <td>
<details>
<summary>Nature Medicine(2022)</summary>

```bibtex
@article{yala2022optimizing,
  title={Optimizing risk-based breast cancer screening policies with reinforcement learning},
  author={Yala, Adam and Mikhael, Peter G and Lehman, Constance and Lin, Gigin and Strand, Fredrik and Wan, Yung-Liang and Hughes, Kevin and Satuluru, Siddharth and Kim, Thomas and Banerjee, Imon and Gichoya, Judy and Trivedi, Hari and Barzilay, Regina},
  journal={Nature Medicine},
  volume={28},
  number={1},
  pages={136--143},
  year={2022},
  publisher={Nature Publishing Group}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td><a href="https://doi.org/10.1126/scitranslmed.abn3971">A risk model for digital breast tomosynthesis to predict breast cancer and guide clinical care</a></td>
      <td>N/A</td>
      <td>
<details>
<summary>Science Translational Medicine(2022)</summary>

```bibtex
@article{eriksson2022risk,
  title={A risk model for digital breast tomosynthesis to predict breast cancer and guide clinical care},
  author={Eriksson, Mikael and others},
  journal={Science Translational Medicine},
  volume={14},
  pages={eabn3971},
  year={2022},
  publisher={American Association for the Advancement of Science}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td><a href="https://doi.org/10.1016/j.patcog.2022.108919">Deep learning of longitudinal mammogram examinations for breast cancer risk prediction</a></td>
      <td>N/A</td>
      <td>
<details>
<summary>Pattern Recognition(2022)</summary>

```bibtex
@article{dadsetan2022deep,
  title={Deep learning of longitudinal mammogram examinations for breast cancer risk prediction},
  author={Dadsetan, Saba and others},
  journal={Pattern Recognition},
  volume={132},
  pages={108919},
  year={2022},
  publisher={Elsevier}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td><a href="https://doi.org/10.1007/978-3-031-43904-9_38">Enhancing Breast Cancer Risk Prediction by Incorporating Prior Images (PRIME+)</a></td>
      <td>N/A</td>
      <td>
<details>
<summary>MICCAI(2023)</summary>

```bibtex
@inproceedings{lee2023enhancing,
  title={Enhancing breast cancer risk prediction by incorporating prior images},
  author={Lee, Hyeonsoo and Kim, Junha and Park, Eunkyung and Kim, Minjeong and Kim, Taesoo and Kooi, Thijs},
  booktitle={Medical Image Computing and Computer Assisted Intervention -- MICCAI 2023},
  year={2023},
  publisher={Springer Nature Switzerland},
  doi={10.1007/978-3-031-43904-9_38}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td><a href="https://pubs.rsna.org/doi/pdf/10.1148/radiol.232780">AsymMirai: interpretable mammography-based deep learning model for 1–5-year breast cancer risk prediction</a></td>
      <td><a href="https://github.com/jdonnelly36/AsymMirai.git">Github</a></td>
      <td>
<details>
<summary>Radiology(2024)</summary>

```bibtex
@article{donnelly2024asymmirai,
  title={AsymMirai: interpretable mammography-based deep learning model for 1--5-year breast cancer risk prediction},
  author={Donnelly, Jon and Moffett, Luke and Barnett, Alina Jade and Trivedi, Hari and Schwartz, Fides and Lo, Joseph and Rudin, Cynthia},
  journal={Radiology},
  volume={310},
  number={3},
  pages={e232780},
  year={2024},
  publisher={Radiological Society of North America}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td><a href="https://doi.org/10.1148/radiol.232535">Use of an AI Score Combining Cancer Signs, Masking, and Risk to Select Patients for Supplemental Breast Cancer Screening (AISmartDensity)</a></td>
      <td>N/A</td>
      <td>
<details>
<summary>Radiology(2024)</summary>

```bibtex
@article{liu2024use,
  title={Use of an AI score combining cancer signs, masking, and risk to select patients for supplemental breast cancer screening},
  author={Liu, Yue and others},
  journal={Radiology},
  volume={311},
  pages={e232535},
  year={2024},
  publisher={Radiological Society of North America}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td><a href="https://doi.org/10.3390/diagnostics14121212">Artificial Intelligence-Powered Imaging Biomarker Based on Mammography for Breast Cancer Risk Prediction</a></td>
      <td>N/A</td>
      <td>
<details>
<summary>Diagnostics(2024)</summary>

```bibtex
@article{park2024artificial,
  title={Artificial intelligence-powered imaging biomarker based on mammography for breast cancer risk prediction},
  author={Park, Eun Kyung and Lee, Hyeonsoo and Kim, Minjeong and Kim, Taesoo and Kim, Junha and Kim, Ki Hwan and Kooi, Thijs and Chang, Yoosoo and Ryu, Seungho},
  journal={Diagnostics},
  volume={14},
  number={12},
  pages={1212},
  year={2024},
  publisher={MDPI}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td><a href="https://doi.org/10.1007/978-3-031-72086-4_41">Longitudinal Mammogram Risk Prediction (LoMaR)</a></td>
      <td><a href="https://github.com/batuhankmkaraman/LoMaR">Github</a></td>
      <td>
<details>
<summary>MICCAI(2024)</summary>

```bibtex
@inproceedings{karaman2024longitudinal,
  title={Longitudinal mammogram risk prediction},
  author={Karaman, Batuhan K and Dodelzon, Katerina and Akar, Gozde B and Sabuncu, Mert R},
  booktitle={Medical Image Computing and Computer Assisted Intervention -- MICCAI 2024},
  volume={15005},
  pages={437--446},
  year={2024},
  publisher={Springer Nature Switzerland}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td><a href="https://doi.org/10.1007/978-3-031-72378-0_15">Ordinal Learning: Longitudinal Attention Alignment Model for Predicting Time to Future Breast Cancer Events from Mammograms (OA-BreaCR)</a></td>
      <td><a href="https://github.com/xinwangxinwang/OA-BreaCR">Github</a></td>
      <td>
<details>
<summary>MICCAI(2024)</summary>

```bibtex
@inproceedings{wang2024ordinal,
  title={Ordinal learning: Longitudinal attention alignment model for predicting time to future breast cancer events from mammograms},
  author={Wang, Xin and Tan, Tao and Gao, Yuan and Marcus, Eric and Han, Luyi and Portaluri, Antonio and Zhang, Tianyu and Lu, Chunyao and Liang, Xinglong and Beets-Tan, Regina and Teuwen, Jonas and Mann, Ritse},
  booktitle={Medical Image Computing and Computer Assisted Intervention -- MICCAI 2024},
  volume={15001},
  pages={155--165},
  year={2024},
  publisher={Springer Nature Switzerland}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td><a href="https://doi.org/10.1200/CCI-24-00200">Development and Validation of Dynamic 5-Year Breast Cancer Risk Model Using Repeated Mammograms</a></td>
      <td>N/A</td>
      <td>
<details>
<summary>JCO Clinical Cancer Informatics(2024)</summary>

```bibtex
@article{jiang2024development,
  title={Development and validation of dynamic 5-year breast cancer risk model using repeated mammograms},
  author={Jiang, Shu and Bennett, Debbie L and Rosner, Bernard A and Tamimi, Rulla M and Colditz, Graham A},
  journal={JCO Clinical Cancer Informatics},
  volume={8},
  pages={e2400200},
  year={2024},
  publisher={American Society of Clinical Oncology}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td><a href="https://doi.org/10.1001/jamanetworkopen.2025.12681">Validation of a Dynamic Risk Prediction Model Incorporating Prior Mammograms in a Diverse Population</a></td>
      <td>N/A</td>
      <td>
<details>
<summary>JAMA Network Open(2025)</summary>

```bibtex
@article{jiang2025validation,
  title={Validation of a dynamic risk prediction model incorporating prior mammograms in a diverse population},
  author={Jiang, Shu and Bennett, Debbie L and Colditz, Graham A},
  journal={JAMA Network Open},
  volume={8},
  number={6},
  pages={e2512681},
  year={2025},
  publisher={American Medical Association}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td><a href="https://papers.miccai.org/miccai-2025/0756-Paper3852.html">Reconsidering Explicit Longitudinal Mammography Alignment for Enhanced Breast Cancer Risk Prediction</a></td>
      <td><a href="https://github.com/sot176/Longitudinal_Mammogram_Alignment.git">Github</a></td>
      <td>
<details>
<summary>MICCAI(2025)</summary>

```bibtex
@inproceedings{thrun2025reconsidering,
  title={Reconsidering explicit longitudinal mammography alignment for enhanced breast cancer risk prediction},
  author={Thrun, Solveig and Hansen, Stine and Sun, Zijun and Blum, Nele and Salahuddin, Suaiba A and Wickstr{\o}m, Kristoffer and Wetzer, Elisabeth and Jenssen, Robert and Stille, Maik and Kampffmeyer, Michael},
  booktitle={Medical Image Computing and Computer Assisted Intervention -- MICCAI 2025},
  volume={15961},
  pages={495--505},
  year={2025},
  publisher={Springer Nature Switzerland}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td><a href="https://doi.org/10.1007/978-3-032-05182-0_64">VMRA-MaR: An Asymmetry-Aware Temporal Framework for Longitudinal Breast Cancer Risk Prediction</a></td>
      <td><a href="https://github.com/Mortal-Suen/VMRA-MaR.git">Github</a></td>
      <td>
<details>
<summary>MICCAI(2025)</summary>

```bibtex
@inproceedings{sun2025vmra,
  title={VMRA-MaR: An asymmetry-aware temporal framework for longitudinal breast cancer risk prediction},
  author={Sun, Zijun and Thrun, Solveig and Kampffmeyer, Michael},
  booktitle={Medical Image Computing and Computer Assisted Intervention -- MICCAI 2025},
  volume={15974},
  pages={660--669},
  year={2025},
  publisher={Springer Nature Switzerland}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td><a href="https://doi.org/10.1038/s41523-025-00831-x">Predicting short- to long-term breast cancer risk from longitudinal mammographic screening history (MTP-BCR)</a></td>
      <td><a href="https://github.com/Netherlands-Cancer-Institute/MTP-BCR">Github</a></td>
      <td>
<details>
<summary>npj Breast Cancer(2025)</summary>

```bibtex
@article{wang2025predicting,
  title={Predicting short- to long-term breast cancer risk from longitudinal mammographic screening history},
  author={Wang, Xin and Tan, Tao and Gao, Yuan and Su, Ruisheng and Teuwen, Jonas and Kroes, Jaap and Zhang, Tianyu and D'Angelo, Anna and Han, Luyi and Drukker, Caroline A and Schmidt, Marjanka K and Beets-Tan, Regina and Karssemeijer, Nico and Mann, Ritse},
  journal={npj Breast Cancer},
  volume={11},
  pages={118},
  year={2025},
  publisher={Nature Publishing Group}
}
```
</details>
      </td>
    </tr>
  </tbody>
</table>


## Mammography Foundation Model

<table>
  <thead>
    <tr>
      <th>Paper</th>
      <th>Code</th>
      <th>Public Venue</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="https://doi.org/10.1002/mp.70261">Leveraging pretrained vision-language model for enhanced breast cancer diagnosis with multi-view mammography (Mammo-CLIP, Chen et al.)</a></td>
      <td>N/A</td>
      <td>
<details>
<summary>Medical Physics(2026)</summary>

```bibtex
@article{chen2026leveraging,
  title={Leveraging pretrained vision-language model for enhanced breast cancer diagnosis with multi-view mammography},
  author={Chen, Xuxin and Li, Yuheng and Hu, Mingzhe and Salari, Ella and Chen, Xiaoqian and Qiu, Richard LJ and Zheng, Bin and Yang, Xiaofeng},
  journal={Medical Physics},
  volume={53},
  number={1},
  pages={e70261},
  year={2026},
  publisher={Wiley},
  doi={10.1002/mp.70261}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td><a href="https://doi.org/10.1007/978-3-031-72390-2_59">Mammo-CLIP: A Vision Language Foundation Model to Enhance Data Efficiency and Robustness in Mammography</a></td>
      <td><a href="https://github.com/batmanlab/Mammo-CLIP">Github</a></td>
      <td>
<details>
<summary>MICCAI(2024)</summary>

```bibtex
@inproceedings{ghosh2024mammo,
  title={Mammo-CLIP: A vision language foundation model to enhance data efficiency and robustness in mammography},
  author={Ghosh, Shantanu and Poynton, Clare B and Visweswaran, Shyam and Batmanghelich, Kayhan},
  booktitle={Medical Image Computing and Computer Assisted Intervention -- MICCAI 2024},
  pages={632--642},
  year={2024},
  publisher={Springer Nature Switzerland}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td><a href="https://doi.org/10.1007/978-3-031-96625-5_17">MaMA: Multi-View and Multi-Scale Alignment for Contrastive Language-Image Pre-training in Mammography</a></td>
      <td><a href="https://github.com/XYPB/MaMA">Github</a></td>
      <td>
<details>
<summary>IPMI(2025)</summary>

```bibtex
@inproceedings{du2025mama,
  title={Multi-view and multi-scale alignment for contrastive language-image pre-training in mammography},
  author={Du, Yuexi and Onofrey, John A and Dvornek, Nicha C},
  booktitle={Information Processing in Medical Imaging -- IPMI 2025},
  pages={247--262},
  year={2025},
  publisher={Springer Nature Switzerland},
  doi={10.1007/978-3-031-96625-5_17}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td><a href="https://doi.org/10.1007/978-3-032-04978-0_29">GLAM: Geometry-Guided Local Alignment for Multi-View Visual Language Pre-Training in Mammography</a></td>
      <td><a href="https://github.com/XYPB/GLAM">Github</a></td>
      <td>
<details>
<summary>MICCAI(2025)</summary>

```bibtex
@inproceedings{du2025geometry,
  title={Geometry-guided local alignment for multi-view visual language pre-training in mammography},
  author={Du, Yuexi and Chen, Lihui and Dvornek, Nicha C},
  booktitle={Medical Image Computing and Computer Assisted Intervention -- MICCAI 2025},
  volume={15965},
  pages={299--310},
  year={2025},
  publisher={Springer Nature Switzerland}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td><a href="https://arxiv.org/abs/2509.20271">VersaMammo: A Versatile Foundation Model for AI-enabled Mammogram Interpretation</a></td>
      <td>N/A</td>
      <td>
<details>
<summary>arXiv(2025)</summary>

```bibtex
@article{huang2025versatile,
  title={A versatile foundation model for AI-enabled mammogram interpretation},
  author={Huang, Fuxiang and Zhu, Jiayi and Yu, Yunfang and Xie, Yu and Guo, Yuan and Kong, Qingcong and Wu, Mingxiang and Jiang, Xinrui and Yang, Shu and Ma, Jiabo and others},
  journal={arXiv preprint arXiv:2509.20271},
  year={2025}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td><a href="https://doi.org/10.1109/ICASSP55912.2026.11463730">MammoDINO: Anatomically Aware Self-Supervision for Mammographic Images</a></td>
      <td>N/A</td>
      <td>
<details>
<summary>ICASSP(2026)</summary>

```bibtex
@inproceedings{zhou2026mammodino,
  title={MammoDINO: Anatomically aware self-supervision for mammographic images},
  author={Zhou, Sicheng and Wu, Lei and Xiao, Cao and Bhatia, Parminder and Kass-Hout, Taha},
  booktitle={IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)},
  pages={8182--8186},
  year={2026},
  doi={10.1109/ICASSP55912.2026.11463730}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td><a href="https://doi.org/10.1109/ICCVW69036.2025.00131">MV-MLM: Bridging Multi-View Mammography and Language for Breast Cancer Diagnosis and Risk Prediction</a></td>
      <td>N/A</td>
      <td>
<details>
<summary>ICCV Workshops(2025)</summary>

```bibtex
@inproceedings{zheng2025mvmlm,
  title={MV-MLM: Bridging multi-view mammography and language for breast cancer diagnosis and risk prediction},
  author={Zheng, Shunjie-Fabian and Lee, Hyeonjun and Kooi, Thijs and Diba, Ali},
  booktitle={IEEE/CVF International Conference on Computer Vision Workshops (ICCVW)},
  pages={1224--1233},
  year={2025},
  doi={10.1109/ICCVW69036.2025.00131}
}
```
</details>
      </td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td><a href="https://arxiv.org/abs/2512.00198">Mammo-FM: Breast-specific foundational model for Integrated Mammographic Diagnosis, Prognosis, and Reporting</a></td>
      <td>N/A</td>
      <td>
<details>
<summary>arXiv(2025)</summary>

```bibtex
@article{ghosh2025mammo,
  title={Mammo-FM: Breast-specific foundational model for integrated mammographic diagnosis, prognosis, and reporting},
  author={Ghosh, Shantanu and Joshi, Vedant Parthesh and Syed, Rayan and Kassem, Aya and Varshney, Abhishek and Basak, Payel and Dai, Weicheng and Gichoya, Judy Wawira and Trivedi, Hari M and Banerjee, Imon and Visweswaran, Shyam and Poynton, Clare B and Batmanghelich, Kayhan},
  journal={arXiv preprint arXiv:2512.00198},
  year={2025}
}
```
</details>
      </td>
    </tr>
  </tbody>
</table>

---

<p align="center">Last updated: 2026-09-30</p>