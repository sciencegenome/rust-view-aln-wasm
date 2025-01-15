# rust-view-multi-aln

- started a webassembly approach for genomic alignments for plants and metagenomes.
- will convert this with additional svelte into a complete biowasm web assembly, so give any BAM, CRAM, SAM file and it will show the genome.
- from reads to entire genome and metagenome visualization.
- please see the last commit message and if it says compiled binary then it is completed or else still in development version.

![](https://github.com/applicativesystem/rust-view-aln-wasm/blob/main/metagenome_alignment.png)

```
cargo build

```
```
λ gauravsablok rust-view-multi-aln → λ git master* → ./target/debug/rust-view-multi-aln -h
Usage: rust-view-multi-aln <ALIGNMENT_ARG>

Arguments:
  <ALIGNMENT_ARG>  please provide the path to the alignment file

Options:
  -h, --help     Print help
  -V, --version  Print version

```

Gaurav Sablok
