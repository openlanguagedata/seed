# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/), and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

In particular:
1. Any updates to pre-existing files shall entail a major version bump.
2. The inclusion of a new language, without changes to other pre-existing data, shall only entail a minor version bump.

## [Unreleased]

### Added

- Added `nqo_Nkoo` from <https://github.com/common-parallel-corpora/common-parallel-corpora>.

### Changed

- Retranslated `ary_Arab` after community feedback and additional quality assessment. Data is now more closely aligned with Moroccan Arabic. Many thanks to @MedAymenF for pointing out the issues with the original NLLB-Seed data.
- Adopted the aligned version of datasets from <https://github.com/common-parallel-corpora/common-parallel-corpora>. Data is now aligned across all languages, i.e. all files use the same ordering of sentences.
- Data was NFC normalised.
- Updated `lij_Latn` after additional quality assessment. Data has undergone minor spelling and syntactic fixes.
- Relabeled `tzm_Tfng` to `zgh_Tfng` after additional quality assessment revealed the data was in Standard Moroccan Tamazight. Many thanks to @MedAymenF for pointing out the issues with the original NLLB-Seed data.
- Relabeled `grn_Latn` macrolanguage code to the correct code `gug_Latn`.

## [1.0] - 2022-07-11

The original release of the dataset – described by [NLLB Team et al. (2022)](https://arxiv.org/abs/2207.04672) and [Maillard et al. (2023)](https://aclanthology.org/2023.acl-long.154/) – can downloaded from <https://tinyurl.com/NLLBSeed>.