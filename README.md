# Timetable Generator: with the use of Quantum Annealing

<div align="center">
Timetable Generator: with the use of Quantum Annealing @2023

[[paper (Korean)]](https://github.com/ysw421/QA-Timetable-generator/blob/main/tex/main.pdf)

</div>

### Abstract
This research solved the Timetable generation problem, well-known as an NP-hard problem, with quantum annealing(QA).
We created a cost function set by users necessary for a timetable with Python.
As a result, we used cases of a $2 \times 3$ shape table and found the operating value with a quantum annealing machine.

### Composition of research
```
\project
  |- code_for_make_formula.ipynb
  |- code_for_run_in_d-wave.ipynb
  |- code_for_test.ipynb
```

### Quick start
```bash
git clone https://github.com/ysw421/QA-Timetable-generator.git
# If you use the GitHub CLI,
# gh repo clone ysw421/QA-Timetable-generator
cd QA-Timetable-generator
pip install -r requirements.txt
# If you use the anaconda,
# conda install --yes --file requirements.txt
```

### Contect
+ Siwon Yun
  - [Email](mailto:yswysw421@gmail.com)
  - [Personal website](https://www.siwonsw.com)
+ Chaehwan Seol
  - [Email](seolchaehwan@gmail.com)
  - [Personal website](https://seolmango.github.io/)

### Citation
If you want to use our code or research useful, please reference us.
- [bibtex.txt](./bibtex.txt)
```bibtex
@article{siwonandchaehawn2023quantum,
  author = {Si-Won Yun, Chae-Hwan Seol},
  title = {양자 어닐링을 활용한 시간표 생성},
  year = {2023},
  URL = {https://github.com/ysw421/QA-Timetable-generator}
}
```

### License
[MIT License](./LICENSE)
