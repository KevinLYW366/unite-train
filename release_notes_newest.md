⚠️ This is a public demo, and has not been validated. I am not affiliated with the UNITE team.

This is a classifier for [Unite v10.0](https://unite.ut.ee/repository.php) Version 04.04.2024 trained for use with [Qiime2 2024.5](https://docs.qiime2.org/2024.5/install/).

These can be used with `q2-feature-classifier` like those found on the [Data resources page](https://docs.qiime2.org/2024.5/data-resources/).

UNITE is licensed under CC BY-SA 4.0. If you use it, cite it! 🤝

>Abarenkov, Kessy; Zirk, Allan; Piirmann, Timo; Pöhönen, Raivo; Ivanov, Filipp; Nilsson, R. Henrik; Kõljalg, Urmas (2023): UNITE QIIME release for Fungi. Version 18.07.2023. UNITE Community **\<DOI GOES HERE>**
>
> DOIs for specific releases are listed here: https://unite.ut.ee/repository.php

---

Changes:

- Update to qiime-2024.5

---

There are three levels of classification provided here:

- "97", in which the database is clustered at 97% identity ([not recommended!](https://forum.qiime2.org/t/feature-classifier-classify-sklearn-all-rep-seqs-unassigned/5960/22))
- "99", in which the database is clustered at 99% identity
- "dynamic", which uses 97% to 99% identity as individually recommended by experts

There are two taxa scopes:

- "" Just Fungi
- "all" All eukaryotes

There two versions, with and without an "s":

- "" Includes singletons set as RefS (in dynamic files)
- "s" Includes global and 97% singletons.
  (I'm not sure what that means)

---

All feedback is welcome! Please [open an issue! ✅](https://github.com/colinbrislawn/unite-train/issues)
