# Methods of creating a dataset for studies related to software evolution and mining software repositories

**Method 1**: _Wessel et al used in the Github actions study_
> We assembled a dataset of GitHub open-source projects that adopted GitHub Actions at some point in their history. To compose our study sample, we started by selecting repositories from GitHub. For this, we used the GitHub project metadata of [Munaiah et al.’s](https://link.springer.com/article/10.1007/s10664-017-9512-6) [RepoReapers data set](https://reporeapers.github.io/results/1.html), which contained 446,862 GitHub repositories classified as containing an engineered software project. We then filter this dataset to keep open-source software projects that at some point had adopted a GitHub Action. whether the repositories had files of yaml format in the ./github/workflows directory. This filtered dataset comprises 3,190 projects. [read more](https://arxiv.org/pdf/2103.12224.pdf)

[link to reporeaper dataset](https://reporeapers.github.io/static/downloads/dataset.csv.gz)

**Mehtod 2**: _the first 300,000 repositories returned by the GitHub API_ this method is used by [Bissyande ́ et al](https://ieeexplore.ieee.org/document/6649842).

**Method 3**: _Github public event stream_ _with combination of a filter used by some researchers like "popularity (measured as number of watchers or [stargazers](https://dl.acm.org/doi/10.1145/2635868.2635922) or [having at least 1 fork](https://dl.acm.org/doi/10.5555/2487085.2487127) on GitHub)"_

**Method 4** _[GHtorrent](https://www.gousios.gr/pub/ghtorrent-dataset-toolsuite.pdf)_
