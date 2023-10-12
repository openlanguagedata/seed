# Seed Machine Translation Data

This repository hosts the open source seed dataset described in the paper [Small Data, Big Impact: Leveraging Minimal Data for Effective Machine Translation](https://aclanthology.org/2023.acl-long.154). The data, which is licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/), is currently being managed by OLDI, the [Open Language Data Initiative](https://oldi.org).

## Data

The parallel corpus currently contains 6,193 sentences sampled from English Wikipedia and translated into 39 languages. It can be used to kick-start machine translation models for language directions which currently lack large-scale datasets.

## Download the dataset

The dataset is available under [`seed/`](seed/).

## Contributing

Fixes and new language contributions are most welcome. Please see the [Contribution guidelines](https://oldi.org/guidelines) for further information.

## Language coverage

| Language                       | Code       |
|--------------------------------|------------|
| Acehnese (Arabic script)       | `ace_Arab` |
| Acehnese (Latin script)        | `ace_Latn` |
| Moroccan Arabic                | `ary_Arab` |
| Egyptian Arabic                | `arz_Arab` |
| Bambara                        | `bam_Latn` |
| Balinese                       | `ban_Latn` |
| Bhojpuri                       | `bho_Deva` |
| Banjar (Arabic script)         | `bjn_Arab` |
| Banjar (Latin script)          | `bjn_Latn` |
| Buginese                       | `bug_Latn` |
| Crimean Tatar                  | `crh_Latn` |
| Southwestern Dinka             | `dik_Latn` |
| Dzongkha                       | `dzo_Tibt` |
| Friulian                       | `fur_Latn` |
| Nigerian Fulfulde              | `fuv_Latn` |
| Guarani                        | `grn_Latn` |
| Chhattisgarhi                  | `hne_Deva` |
| Kashmiri (Arabic script)       | `kas_Arab` |
| Kashmiri (Devanagari script)   | `kas_Deva` |
| Central Kanuri (Arabic script) | `knc_Arab` |
| Central Kanuri (Latin script)  | `knc_Latn` |
| Ligurian                       | `lij_Latn` |
| Limburgish                     | `lim_Latn` |
| Lombard                        | `lmo_Latn` |
| Latgalian                      | `ltg_Latn` |
| Magahi                         | `mag_Deva` |
| Meitei (Bengali script)        | `mni_Beng` |
| Maori                          | `mri_Latn` |
| Nko                            | `nqo_Nkoo` |
| Nuer                           | `nus_Latn` |
| Dari                           | `prs_Arab` |
| Southern Pashto                | `pbt_Arab` |
| Sicilian                       | `scn_Latn` |
| Shan                           | `shn_Mymr` |
| Sardinian                      | `srd_Latn` |
| Silesian                       | `szl_Latn` |
| Tamasheq (Latin script)        | `taq_Latn` |
| Tamasheq (Tifinagh script)     | `taq_Tfng` |
| Venetian                       | `vec_Latn` |
| Standard Moroccan Tamazight    | `zgh_Tfng` |

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