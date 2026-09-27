        # CALFW

        [![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-green?logo=creativecommons&logoColor=white)](https://creativecommons.org/licenses/by/4.0/)
        [![GitHub](https://img.shields.io/badge/GitHub-biometric--community%2FCALFW-181717?logo=github)](https://github.com/biometric-community/CALFW)
        [![Access: public](https://img.shields.io/badge/access-public-0e8a16.svg)](http://www.whdeng.cn/CALFW/index.html)

        Cross-Age LFW (**CALFW**) — age-gap face verification pairs built on LFW identities.

        - **Dataset repository**: https://github.com/biometric-community/CALFW
        - **Upstream source**: http://www.whdeng.cn/CALFW/index.html
        - **License (helpers / docs)**: CC BY 4.0 (see [`LICENSE`](LICENSE))
        - **License (data)**: upstream terms — this packaging does **not** relicense the data


        | Field | Value |
        |-------|-------|
        | Catalog id (tbiom) | `calfw` |
        | Category | `face-recog` |
        | Access | `public` |
        | Upstream homepage | http://www.whdeng.cn/CALFW/index.html |

        ## TL;DR

        - **Task**: face verification (cross-age pairs)
        - **Access**: **public**
        - **This mirror**: documentation + download helpers only (no bulk payload in git)
        - **Notes**: Official zip links change often; place archives under this folder after download from the project page or InsightFace packs.

        ## Table of contents

        - [Download](#download)
        - [Dataset structure](#dataset-structure)
        - [Known issues and caveats](#known-issues-and-caveats)
        - [License](#license)
        - [Citation](#citation)
        - [Contact](#contact)

        ## Download

        ### Clone this repository

        ```bash
        git clone git@github.com:biometric-community/CALFW.git
        cd CALFW
        ```

        ### tbiom monorepo helper

        ```bash
        bash projects/datasets/scripts/download_calfw.sh
        ```

        Then follow the printed upstream steps and place archives under `projects/datasets/calfw/`.

        ## Dataset structure

        ```text
        CALFW/
        ├── README.md
        ├── LICENSE                 # helpers / docs (CC BY 4.0)
        ├── .gitignore
        └── extracted/              # local only after you download (gitignored)
        ```

        ## Known issues and caveats

        - Upstream hosts / Drive quotas often block fully automated downloads.
        - Do not commit multi-GB payloads to this GitHub mirror.

        ## License

        Helpers/docs: CC BY 4.0. Dataset files: upstream license / access agreement.

        ## Citation

        ```bibtex
        @inproceedings{zheng2017cross,
  title={Cross-Age LFW: A Database for Studying Cross-Age Face Recognition in Unconstrained Environments},
  author={Zheng, Tianyue and Deng, Weihong and Hu, Jiani},
  booktitle={arXiv:1708.08197},
  year={2017}
}
        ```

        ## Contact

        - Upstream: http://www.whdeng.cn/CALFW/index.html
        - Packaging: https://github.com/biometric-community/CALFW/issues
