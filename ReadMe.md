# Fuzzing Broadcom/Cypress Bluetooth Firmware

In this project I tried to fuzz bluetooth firmware from Broadcom. 
This firmware is widely used in many phones and laptops including iPhones and Androids.
Through fuzzing I wanted test exploiting two vulnerabilites in firmware. Reproduced 2 CVEs (CVE-2019-11516 and CVE-2019-11916).
My project report and slide in added in this repository.

Originally this work is done in this USENIX paper cited bellow.

## Frankenstein: Advanced Wireless Fuzzing to Exploit New Bluetooth Escalation Targets 

```
@inproceedings {255232,
author = {Jan Ruge and Jiska Classen and Francesco Gringoli and Matthias Hollick},
title = {Frankenstein: Advanced Wireless Fuzzing to Exploit New Bluetooth Escalation Targets},
booktitle = {29th USENIX Security Symposium (USENIX Security 20)},
year = {2020},
isbn = {978-1-939133-17-5},
pages = {19--36},
url = {https://www.usenix.org/conference/usenixsecurity20/presentation/ruge},
publisher = {USENIX Association},
month = aug
}
```

## Original Paper Repo: https://github.com/seemoo-lab/frankenstein