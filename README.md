<p align="center">
  <img src="assets/header.svg" alt="Matheus Rodrigues Teixeira: Machine Learning Engineer, Software Engineer, Quantum Computing Researcher" width="100%"/>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/matheusrteixeira/"><img src="https://img.shields.io/badge/LinkedIn-matheusrteixeira-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://orcid.org/0009-0001-1816-632X"><img src="https://img.shields.io/badge/ORCID-0009--0001--1816--632X-A6CE39?style=for-the-badge&logo=orcid&logoColor=white" alt="ORCID"/></a>
  <a href="mailto:rmatheusteixeira@pm.me"><img src="https://img.shields.io/badge/Email-rmatheusteixeira%40pm.me-6D4AFF?style=for-the-badge&logo=protonmail&logoColor=white" alt="Email"/></a>
</p>

<p align="center">
I build reproducible machine learning pipelines and tested, production-quality software.<br/>
My research is in quantum machine learning and quantum error correction; my engineering work spans<br/>
Python, TypeScript, React and Rust compiled to WebAssembly.
</p>

## Right now

<table>
  <tr>
    <td width="33%" valign="top">
      <b>Ph.D. in Electrical Engineering</b><br/>
      <sub>Centro Universitário FEI · CAPES scholarship</sub><br/><br/>
      Enrolled; classes begin in February 2027. Quantum error correction and machine learning decoders, with a sandwich year planned at ETH Zurich (2028–2029).
    </td>
    <td width="33%" valign="top">
      <b>MBA in Data Science, AI and Analytics</b><br/>
      <sub>USP/Esalq · in progress</sub><br/><br/>
      Applied statistics, machine learning and analytics, alongside an M.Sc. in Electrical Engineering (AI) and a B.Sc. in Computer Science, both from FEI.
    </td>
    <td width="33%" valign="top">
      <b>Building for the browser</b><br/>
      <sub>Rust · WebAssembly · TypeScript · TensorFlow.js</sub><br/><br/>
      Interactive physics and music tools that run entirely client-side, backed by seven years of professional web, database and IT work.
    </td>
  </tr>
</table>

## Featured software

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://isaac3d.com"><img src="assets/isaac.svg" alt="Isaac: interactive 3D physics simulations" width="100%"/></a>
      <p>Students change parameters and watch physics respond, with live graphs and equations. Physics core in Rust compiled to WebAssembly; interface in React, TypeScript and Three.js; physics validated with <code>cargo test</code>, unit tests in Vitest and end-to-end tests in Playwright.</p>
      <p><a href="https://isaac3d.com"><b>isaac3d.com</b></a></p>
    </td>
    <td width="50%" valign="top">
      <a href="https://amadeosheets.com"><img src="assets/amadeo.svg" alt="Amadeo: from sound to sheet music" width="100%"/></a>
      <p>Transcribes recordings into editable scores without leaving the browser: neural pitch detection on TensorFlow.js, key and chord estimation, export to PDF, MusicXML and MIDI. React and TypeScript, nine languages, cross-browser Playwright tests.</p>
      <p><a href="https://amadeosheets.com"><b>amadeosheets.com</b></a></p>
    </td>
  </tr>
</table>

<details>
<summary><b>Also built</b> (private repositories, happy to walk through them in an interview)</summary>
<br/>

| Project | What it does | Stack |
| --- | --- | --- |
| **Allwinner** | Scores trading strategies with walk-forward, out-of-sample backtests and block-bootstrap significance tests | Python, pandas, FastAPI, SQLite, 221 pytest tests |
| **Brectus** | Desktop app that orchestrates AI coding agents per project, with encryption at rest and signed updates | Node.js, Electron |
| **Business websites** | Company sites with WCAG 2.2 AA accessibility tests and Lighthouse scores of 95 and above | Astro, TypeScript, Cloudflare Pages |

</details>

## Research

### [Quantum Machine Learning Applications in Healthcare](https://github.com/matheusrteixeira-dev/Quantum-Machine-Learning-Applications-in-Healthcare)

Reproducible hybrid quantum-classical pipeline for breast cancer histopathology classification on BreaKHis (M.Sc. dissertation).

```mermaid
flowchart LR
    A[BreaKHis<br/>histopathology images] --> B[ResNet-50<br/>feature extraction]
    B --> C[Patient-wise<br/>train / val / test splits]
    C --> D[Linear SVM]
    C --> E[RBF SVM]
    C --> F[QSVM<br/>quantum fidelity kernel]
    F --> G[IBM Quantum<br/>hardware run]
    D --> H[Accuracy · F1 · MCC]
    E --> H
    F --> H
    classDef q fill:#2a1650,stroke:#ff4fd8,color:#f2f5ff
    classDef c fill:#0b2233,stroke:#22e6ff,color:#f2f5ff
    class A,B,C,D,E,H c
    class F,G q
```

<p>
  <img src="https://img.shields.io/badge/QSVM%20accuracy-80.0%25-6929C4?style=flat-square" alt="QSVM accuracy 80.0%"/>
  <img src="https://img.shields.io/badge/F1--score-86.0%25-6929C4?style=flat-square" alt="F1-score 86.0%"/>
  <img src="https://img.shields.io/badge/MCC-0.520-6929C4?style=flat-square" alt="MCC 0.520"/>
  <img src="https://img.shields.io/badge/hardware-IBM%20Quantum-052FAD?style=flat-square&logo=ibm&logoColor=white" alt="IBM Quantum hardware"/>
</p>

### [Quantum Classifier for the Iris Dataset](https://github.com/matheusrteixeira-dev/Quantum-Classifier-for-Iris-Dataset)

B.Sc. final project: a Quantum Support Vector Machine for the Iris dataset, with quantum feature maps, kernel-based classification and model evaluation.

## Publication

> **Systematic Review of Quantum Machine Learning for Healthcare**<br/>
> Matheus Teixeira, Reinaldo A. C. Bianchi<br/>
> 36th Brazilian Conference on Intelligent Systems (BRACIS 2026), Cuiabá, Brazil, October 2026.

## Tech stack

#### Machine Learning and Data

<p align="left">
  <a href="https://www.python.org/" title="Python"><img src="https://cdn.simpleicons.org/python" alt="Python" width="40" height="40"/></a>
  <a href="https://pytorch.org/" title="PyTorch"><img src="https://cdn.simpleicons.org/pytorch" alt="PyTorch" width="40" height="40"/></a>
  <a href="https://www.tensorflow.org/" title="TensorFlow"><img src="https://cdn.simpleicons.org/tensorflow" alt="TensorFlow" width="40" height="40"/></a>
  <a href="https://keras.io/" title="Keras"><img src="https://cdn.simpleicons.org/keras" alt="Keras" width="40" height="40"/></a>
  <a href="https://scikit-learn.org/" title="scikit-learn"><img src="https://cdn.simpleicons.org/scikitlearn" alt="scikit-learn" width="40" height="40"/></a>
  <a href="https://pandas.pydata.org/" title="pandas"><img src="https://cdn.simpleicons.org/pandas" alt="pandas" width="40" height="40"/></a>
  <a href="https://numpy.org/" title="NumPy"><img src="https://cdn.simpleicons.org/numpy" alt="NumPy" width="40" height="40"/></a>
  <a href="https://scipy.org/" title="SciPy"><img src="https://cdn.simpleicons.org/scipy" alt="SciPy" width="40" height="40"/></a>
  <a href="https://matplotlib.org/" title="Matplotlib"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/matplotlib/matplotlib-original.svg" alt="Matplotlib" width="40" height="40"/></a>
  <a href="https://opencv.org/" title="OpenCV"><img src="https://cdn.simpleicons.org/opencv" alt="OpenCV" width="40" height="40"/></a>
  <a href="https://jupyter.org/" title="Jupyter"><img src="https://cdn.simpleicons.org/jupyter" alt="Jupyter" width="40" height="40"/></a>
</p>

#### Quantum Computing

<p align="left">
  <img src="https://img.shields.io/badge/Qiskit-6929C4?style=for-the-badge&logo=qiskit&logoColor=white" alt="Qiskit"/>
  <img src="https://img.shields.io/badge/IBM%20Quantum-052FAD?style=for-the-badge&logo=ibm&logoColor=white" alt="IBM Quantum"/>
  <img src="https://img.shields.io/badge/QSVM-Quantum%20Kernel-6929C4?style=for-the-badge" alt="QSVM and Quantum Kernels"/>
  <img src="https://img.shields.io/badge/NISQ-Experiments-6929C4?style=for-the-badge" alt="NISQ Experiments"/>
</p>

#### Programming Languages

<p align="left">
  <a href="https://www.python.org/" title="Python"><img src="https://cdn.simpleicons.org/python" alt="Python" width="40" height="40"/></a>
  <a href="https://www.typescriptlang.org/" title="TypeScript"><img src="https://cdn.simpleicons.org/typescript" alt="TypeScript" width="40" height="40"/></a>
  <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" title="JavaScript"><img src="https://cdn.simpleicons.org/javascript" alt="JavaScript" width="40" height="40"/></a>
  <a href="https://www.rust-lang.org/" title="Rust"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/rust/rust-original.svg" alt="Rust" width="40" height="40"/></a>
  <a href="https://www.cprogramming.com/" title="C"><img src="https://cdn.simpleicons.org/c" alt="C" width="40" height="40"/></a>
  <a href="https://isocpp.org/" title="C++"><img src="https://cdn.simpleicons.org/cplusplus" alt="C++" width="40" height="40"/></a>
  <a href="https://www.java.com/" title="Java"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="Java" width="40" height="40"/></a>
</p>

#### Web, Apps and Backend

<p align="left">
  <a href="https://react.dev/" title="React"><img src="https://cdn.simpleicons.org/react" alt="React" width="40" height="40"/></a>
  <a href="https://vite.dev/" title="Vite"><img src="https://cdn.simpleicons.org/vite" alt="Vite" width="40" height="40"/></a>
  <a href="https://astro.build/" title="Astro"><img src="https://cdn.simpleicons.org/astro" alt="Astro" width="40" height="40"/></a>
  <a href="https://threejs.org/" title="Three.js"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/threejs/threejs-original.svg" alt="Three.js" width="40" height="40"/></a>
  <a href="https://webassembly.org/" title="WebAssembly"><img src="https://cdn.simpleicons.org/webassembly" alt="WebAssembly" width="40" height="40"/></a>
  <a href="https://nodejs.org/" title="Node.js"><img src="https://cdn.simpleicons.org/nodedotjs" alt="Node.js" width="40" height="40"/></a>
  <a href="https://www.electronjs.org/" title="Electron"><img src="https://cdn.simpleicons.org/electron" alt="Electron" width="40" height="40"/></a>
  <a href="https://fastapi.tiangolo.com/" title="FastAPI"><img src="https://cdn.simpleicons.org/fastapi" alt="FastAPI" width="40" height="40"/></a>
  <a href="https://www.cloudflare.com/" title="Cloudflare"><img src="https://cdn.simpleicons.org/cloudflare" alt="Cloudflare" width="40" height="40"/></a>
  <a href="https://www.w3.org/html/" title="HTML5"><img src="https://cdn.simpleicons.org/html5" alt="HTML5" width="40" height="40"/></a>
  <a href="https://www.w3.org/Style/CSS/" title="CSS3"><img src="https://cdn.simpleicons.org/css" alt="CSS3" width="40" height="40"/></a>
</p>

#### Databases

<p align="left">
  <a href="https://www.sqlite.org/" title="SQLite"><img src="https://cdn.simpleicons.org/sqlite" alt="SQLite" width="40" height="40"/></a>
  <a href="https://www.mysql.com/" title="MySQL"><img src="https://cdn.simpleicons.org/mysql" alt="MySQL" width="40" height="40"/></a>
  <a href="https://www.postgresql.org/" title="PostgreSQL"><img src="https://cdn.simpleicons.org/postgresql" alt="PostgreSQL" width="40" height="40"/></a>
  <a href="https://www.mongodb.com/" title="MongoDB"><img src="https://cdn.simpleicons.org/mongodb" alt="MongoDB" width="40" height="40"/></a>
</p>

#### Testing and Tools

<p align="left">
  <a href="https://playwright.dev/" title="Playwright"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/playwright/playwright-original.svg" alt="Playwright" width="40" height="40"/></a>
  <a href="https://vitest.dev/" title="Vitest"><img src="https://cdn.simpleicons.org/vitest" alt="Vitest" width="40" height="40"/></a>
  <a href="https://docs.pytest.org/" title="pytest"><img src="https://cdn.simpleicons.org/pytest" alt="pytest" width="40" height="40"/></a>
  <a href="https://git-scm.com/" title="Git"><img src="https://cdn.simpleicons.org/git" alt="Git" width="40" height="40"/></a>
  <a href="https://github.com/features/actions" title="GitHub Actions"><img src="https://cdn.simpleicons.org/githubactions" alt="GitHub Actions" width="40" height="40"/></a>
  <a href="https://www.linux.org/" title="Linux"><img src="https://cdn.simpleicons.org/linux" alt="Linux" width="40" height="40"/></a>
  <a href="https://www.microsoft.com/windows/" title="Windows"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/windows11/windows11-original.svg" alt="Windows" width="40" height="40"/></a>
  <a href="https://www.latex-project.org/" title="LaTeX"><img src="https://cdn.simpleicons.org/latex" alt="LaTeX" width="40" height="40"/></a>
  <a href="https://www.mathworks.com/products/matlab.html" title="MATLAB"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/matlab/matlab-original.svg" alt="MATLAB" width="40" height="40"/></a>
</p>

## Coursework

[M.Sc. Artificial Intelligence](https://github.com/matheusrteixeira-dev/MSc-Artificial-Intelligence) · [Computer Science](https://github.com/matheusrteixeira-dev/Computer-Science-FEI)

## Research interests

`Quantum Error Correction` · `Machine Learning Decoders` · `Quantum Machine Learning` · `Healthcare AI` · `Computer Vision` · `Reproducible Research`

<p align="center">
  <img src="assets/footer.svg" alt="" width="100%"/>
</p>
