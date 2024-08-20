# Changelog

## [3.0.0](https://github.com/jccdigital/rna-seq-star-deseq2/compare/v2.1.2...v3.0.0) (2024-08-20)


### ⚠ BREAKING CHANGES

* generalize away condition ([#66](https://github.com/jccdigital/rna-seq-star-deseq2/issues/66))

### Features

* add release-please and use conventional commits ([8f16598](https://github.com/jccdigital/rna-seq-star-deseq2/commit/8f165989f690e8b2746f5d323bcdd921482b92ce))
* generalize away condition ([#66](https://github.com/jccdigital/rna-seq-star-deseq2/issues/66)) ([e103c1c](https://github.com/jccdigital/rna-seq-star-deseq2/commit/e103c1cc78feba97cc3cebe8d7f2a51c8958ab96))


### Bug Fixes

* Fixing workflow for single-end sequencing ([#70](https://github.com/jccdigital/rna-seq-star-deseq2/issues/70)) ([3380a05](https://github.com/jccdigital/rna-seq-star-deseq2/commit/3380a05a1883e6c5ec509ce764af975b1620fc02))
* make specification of SRA samples in samples.tsv work (common.smk) ([683c611](https://github.com/jccdigital/rna-seq-star-deseq2/commit/683c61126185e8ae16cc0ae010235e15739b5f8e)), closes [#52](https://github.com/jccdigital/rna-seq-star-deseq2/issues/52)
* release-please branch to `master` and set permissions ([#79](https://github.com/jccdigital/rna-seq-star-deseq2/issues/79)) ([4b781cf](https://github.com/jccdigital/rna-seq-star-deseq2/commit/4b781cfa14fb5474108594fbaefa0ac8519f19dc))
* update gffults & qc ([#69](https://github.com/jccdigital/rna-seq-star-deseq2/issues/69)) ([846693f](https://github.com/jccdigital/rna-seq-star-deseq2/commit/846693fa78a923c12e397e89c447816c70de097b))
* update to using storage plugin ftp ([#76](https://github.com/jccdigital/rna-seq-star-deseq2/issues/76)) ([0f18be7](https://github.com/jccdigital/rna-seq-star-deseq2/commit/0f18be7618a8dfb998455edf1da89b7cfb2e1301))
* use derived input for star_index ([#81](https://github.com/jccdigital/rna-seq-star-deseq2/issues/81)) ([87fffe6](https://github.com/jccdigital/rna-seq-star-deseq2/commit/87fffe6a1beaa86e95c3564061d2720cc73308c7))


### Performance Improvements

* update all wrapper to latest v3.5.3 ([#78](https://github.com/jccdigital/rna-seq-star-deseq2/issues/78)) ([bc9ab71](https://github.com/jccdigital/rna-seq-star-deseq2/commit/bc9ab713f7c11b04bae296a27970aceeb12ab1ae))

## [2.1.2](https://github.com/snakemake-workflows/rna-seq-star-deseq2/compare/v2.1.1...v2.1.2) (2024-06-05)


### Bug Fixes

* use derived input for star_index ([#81](https://github.com/snakemake-workflows/rna-seq-star-deseq2/issues/81)) ([87fffe6](https://github.com/snakemake-workflows/rna-seq-star-deseq2/commit/87fffe6a1beaa86e95c3564061d2720cc73308c7))

## [2.1.1](https://github.com/snakemake-workflows/rna-seq-star-deseq2/compare/v2.1.0...v2.1.1) (2024-03-25)


### Bug Fixes

* release-please branch to `master` and set permissions ([#79](https://github.com/snakemake-workflows/rna-seq-star-deseq2/issues/79)) ([4b781cf](https://github.com/snakemake-workflows/rna-seq-star-deseq2/commit/4b781cfa14fb5474108594fbaefa0ac8519f19dc))
* remove unused ftp RemoteProvider and require recent snakemake 8 ([#76](https://github.com/snakemake-workflows/rna-seq-star-deseq2/issues/76)) ([0f18be7](https://github.com/snakemake-workflows/rna-seq-star-deseq2/commit/0f18be7618a8dfb998455edf1da89b7cfb2e1301))


### Performance Improvements

* update all wrapper to latest v3.5.3 ([#78](https://github.com/snakemake-workflows/rna-seq-star-deseq2/issues/78)) ([bc9ab71](https://github.com/snakemake-workflows/rna-seq-star-deseq2/commit/bc9ab713f7c11b04bae296a27970aceeb12ab1ae))
