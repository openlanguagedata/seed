# Seed Machine Translation Data

This repository hosts the open source seed dataset described in the paper [Small Data, Big Impact: Leveraging Minimal Data for Effective Machine Translation](https://aclanthology.org/2023.acl-long.154). The data, which is licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/), is currently being managed by OLDI, the [Open Language Data Initiative](https://oldi.org).

## Data

The parallel corpus currently contains 6,193 sentences sampled from English Wikipedia and translated into 39 languages. It can be used to kick-start machine translation models for language directions which currently lack large-scale datasets.

## Download the dataset

The dataset is available under [`seed/`](seed/).

## Contributing

Fixes and new language contributions are most welcome. Please see the [Contribution guidelines](https://oldi.org/guidelines) for further information.

## Language coverage

|    Code    |  Variety   |               Name                |                           Notes                            |
|------------|------------|-----------------------------------|------------------------------------------------------------|
| `ace_Arab` | `achi1257` |      Acehnese (Arabic script)     |                                                            |
| `ace_Latn` | `achi1257` |      Acehnese (Latin script)      |                                                            |
| `ary_Arab` | `moro1292` |          Moroccan Arabic          |                                                            |
| `arz_Arab` | `egyp1253` |          Egyptian Arabic          |                                                            |
| `bam_Latn` | `bamb1269` |              Bambara              |                                                            |
| `ban_Latn` | `bali1278` |              Balinese             |                                                            |
| `bho_Deva` | `bhoj1244` |              Bhojpuri             |                                                            |
| `bjn_Arab` | `banj1239` |        Banjar (Jawi script)       |                                                            |
| `bjn_Latn` | `banj1239` |       Banjar (Latin script)       |                                                            |
| `bug_Latn` | `bugi1244` |              Buginese             |                                                            |
| `crh_Latn` | `crim1257` |           Crimean Tatar           |                                                            |
| `dik_Latn` | `sout2832` |         Southwestern Dinka        |                                                            |
| `dzo_Tibt` | `dzon1239` |              Dzongkha             |                                                            |
| `eng_Latn` | `stan1293` |              English              |                                                            |
| `fur_Latn` | `east2271` |              Friulian             |                                                            |
| `fuv_Latn` | `nige1253` |         Nigerian Fulfulde         |                                                            |
| `gug_Latn` | `para1311` |         Paraguayan Guaraní        |                                                            |
| `hne_Deva` | `chha1249` |           Chhattisgarhi           |                                                            |
| `kas_Arab` | `kash1277` |      Kashmiri (Arabic script)     |                                                            |
| `kas_Deva` | `kash1277` |    Kashmiri (Devanagari script)   |                                                            |
| `knc_Arab` | `cent2050` |   Central Kanuri (Arabic script)  |                                                            |
| `knc_Latn` | `cent2050` |   Central Kanuri (Latin script)   |                                                            |
| `lij_Latn` | `geno1240` |         Ligurian (Genoese)        |                                                            |
| `lim_Latn` | `limb1263` |             Limburgish            |                                                            |
| `lmo_Latn` | `lomb1257` |              Lombard              | [[1]](https://github.com/openlanguagedata/flores/issues/5) |
| `ltg_Latn` | `east2282` |             Latgalian             |                                                            |
| `mag_Deva` | `maga1260` |               Magahi              |                                                            |
| `mni_Beng` | `mani1292` | Meitei (Manipuri, Bengali script) |                                                            |
| `mri_Latn` | `maor1246` |               Maori               |                                                            |
| `nqo_Nkoo` | `nkoa1234` |                Nko                |                                                            |
| `nus_Latn` | `nuer1246` |                Nuer               |                                                            |
| `pbt_Arab` | `sout2649` |          Southern Pashto          |                                                            |
| `prs_Arab` | `dari1249` |                Dari               |                                                            |
| `scn_Latn` | `sici1248` |              Sicilian             |                                                            |
| `shn_Mymr` | `shan1277` |                Shan               |                                                            |
| `srd_Latn` | `sard1257` |             Sardinian             | [[1]](https://github.com/openlanguagedata/flores/issues/6) |
| `szl_Latn` | `sile1253` |              Silesian             |                                                            |
| `taq_Latn` | `tama1365` |      Tamasheq (Latin script)      |                                                            |
| `taq_Tfng` | `tama1365` |     Tamasheq (Tifinagh script)    |                                                            |
| `vec_Latn` | `vene1259` |              Venetian             |                                                            |
| `zgh_Tfng` | `stan1324` |    Standard Moroccan Tamazight    |                                                            |

## Citation

This dataset is based upon the work originally described in the following paper:

```bibtex
@inproceedings{seed-23,
    title = {Small Data, Big Impact: Leveraging Minimal Data for Effective Machine Translation},
    author = {Maillard, Jean and Gao, Cynthia and Kalbassi, Elahe and Sadagopan, Kaushik Ram and Goswami, Vedanuj and Koehn, Philipp and Fan, Angela and Guzmán, Francisco},
    booktitle = {Proceedings of the 61st Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)},
    year = {2023},
    address = {Toronto, Canada},
    publisher = {Association for Computational Linguistics},
    pages = {2740--2756},
    url = {https://aclanthology.org/2023.acl-long.154},
}
```

Other authors have since contributed to the dataset:
* Re-aligned datasets and Nko language support: Moussa Koulako Bala Doumbouya, Baba Mamadi Diané, Solo Farabado Cissé, Djibrila Diané, Abdoulaye Sow, Séré Moussa Doumbouya, Daouda Bangoura, Fodé Moriba Bayo, Ibrahima Sory 2. Condé, Kalo Mory Diané, Chris Piech, Christopher Manning. [Paper](https://arxiv.org/abs/2310.15612), [repository](https://github.com/common-parallel-corpora/common-parallel-corpora).

If you use this dataset in your work, please cite the papers listed in [bibliography.bib](bibliography.bib).

## Changelog

See [CHANGELOG.md](CHANGELOG.md) for information about the latest changes.