# ISCA SIG RoSP webpage

- This is a GitHub repository for ISCA SIG RoSP webpage (ongoing). See https://isca-sig-rosp.github.io/ISCA-SIG-RoSP/
- Old RoSP webpage: https://wiki.inria.fr/rosp/ (gradually moving these contents to this page)
- RoSP pages in the ISCA site https://www.isca-speech.org/iscaweb/index.php/sigs?layout=edit&id=135

## Setup

This website is based on Jekyll. Install Jekyll using the Ruby gem installer instructions here: https://jekyllrb.com/docs/installation/. Then run the following to build locally.

```bash
$ bundle install
$ bundle update
$ bundle exec jekyll serve
```

The website should now be available at `127.0.0.1:4000`.

## App scripts

The Datasets and Software pages uses Google App scripts to interface with underlying data. 
Please contact Desh Raj at `r.desh26@gmail.com` to access these APIs.

* The `dataset` master spreadsheet is available [here](https://docs.google.com/spreadsheets/d/16U_v_HRW4KnAaNkBUtcgtwXNO1xArnvXg1ihRhBbMJo/edit?usp=sharing) (read-only).
* The `software` master spreadsheet is available [here](https://docs.google.com/spreadsheets/d/1TLB0TqtssE9bvOf2ByLMOMnkBHxphmOhqCcBE133t7s/edit?usp=sharing)
