<p align="center">
  <img src="assets/header.svg" alt="Matheus Rodrigues Teixeira: Machine Learning Engineer, Software Engineer, Quantum Computing Researcher. Animated banner with a black hole and orbiting planets." width="100%"/>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/matheusrteixeira/"><img src="assets/btn-linkedin.svg" alt="LinkedIn: in/matheusrteixeira" width="32%"/></a>
  <a href="https://orcid.org/0009-0001-1816-632X"><img src="assets/btn-orcid.svg" alt="ORCID: 0009-0001-1816-632X" width="32%"/></a>
  <a href="mailto:rmatheusteixeira@pm.me"><img src="assets/btn-email.svg" alt="Email: rmatheusteixeira@pm.me" width="32%"/></a>
</p>

<p align="center">
  <img src="assets/terminal.svg" alt="Terminal: whoami prints Matheus Rodrigues Teixeira, machine learning engineer, software engineer, quantum computing researcher. Status: Ph.D. in Electrical Engineering at FEI on quantum error correction, enrolled with classes from February 2027; MBA in Data Science, AI and Analytics at USP/Esalq in progress; M.Sc. in Electrical Engineering (AI) and B.Sc. in Computer Science at FEI. Shipped: isaac3d.com, amadeosheets.com, Allwinner, Brectus, quantum ML for healthcare. Languages: Portuguese (native), English (C2, EF SET 92/100)." width="100%"/>
</p>

I work on machine learning and software. My research is in quantum machine learning and quantum error correction, and most of my code is in Python, TypeScript, React and Rust.

<p align="center">
  <img src="assets/worldline.svg" alt="Worldline, a spacetime diagram of my path: web developer and IT support at Orion Benefícios from 2016 to 2023; B.Sc. in Computer Science at FEI 2019 to 2023; M.Sc. in Electrical Engineering (AI) at FEI 2024 to 2026; MBA at USP/Esalq from August 2026; BRACIS 2026 paper in October 2026; Ph.D. classes begin February 2027; planned sandwich year at ETH Zurich from September 2028; planned thesis defence in February 2030." width="100%"/>
</p>

## Featured software

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://isaac3d.com"><img src="assets/isaac.svg" alt="Isaac: a chaotic double pendulum drawing its own trajectory" width="100%"/></a>
      <p>Interactive physics simulations for students, with live graphs and equations. Physics core in Rust compiled to WebAssembly; interface in React, TypeScript and Three.js; physics validated with <code>cargo test</code>, unit tests in Vitest and end-to-end tests in Playwright.</p>
      <p><a href="https://isaac3d.com"><b>isaac3d.com</b></a></p>
    </td>
    <td width="50%" valign="top">
      <a href="https://amadeosheets.com"><img src="assets/amadeo.svg" alt="Amadeo: a spectrogram resolving into notes on a staff" width="100%"/></a>
      <p>Turns audio recordings into editable sheet music, all in the browser: neural pitch detection on TensorFlow.js, key and chord estimation, export to PDF, MusicXML and MIDI. React and TypeScript, nine languages, cross-browser Playwright tests.</p>
      <p><a href="https://amadeosheets.com"><b>amadeosheets.com</b></a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <img src="assets/allwinner.svg" alt="Allwinner: walk-forward windows, each fit followed by an out-of-sample test" width="100%"/>
      <p>Backtests trading strategies on out-of-sample data with walk-forward windows, fees and slippage, and uses block-bootstrap tests to check that results are not due to chance. Python, pandas, FastAPI and SQLite, with 221 pytest tests.</p>
      <p><sub>Private repository.</sub></p>
    </td>
    <td width="50%" valign="top">
      <img src="assets/brectus.svg" alt="Brectus: a router dispatching requests to per-project coding agents" width="100%"/>
      <p>Desktop app that sends requests to a separate AI coding agent for each project. Data is encrypted at rest, updates are signed, and CI runs on Windows, macOS and Linux. Node.js and Electron.</p>
      <p><sub>Private repository.</sub></p>
    </td>
  </tr>
</table>

<p align="center">
  <img src="assets/websites.svg" alt="Company websites for Orion Benefícios and LÍDER Plus Telemedicina: Lighthouse 95 on mobile and 100 on desktop, WCAG 2.2 AA accessibility tests, built with Astro, TypeScript and Cloudflare Pages." width="100%"/>
</p>

## Research

<p align="center">
  <a href="https://github.com/matheusrteixeira-dev/Quantum-Machine-Learning-Applications-in-Healthcare"><img src="assets/research.svg" alt="Quantum-kernel SVM on breast cancer histopathology: 80.0% accuracy, 86.0% F1-score, 0.520 MCC, with an animated Bloch sphere" width="100%"/></a>
</p>

**[Quantum Machine Learning Applications in Healthcare](https://github.com/matheusrteixeira-dev/Quantum-Machine-Learning-Applications-in-Healthcare)**: code for my M.Sc. dissertation. A hybrid quantum-classical pipeline for breast cancer histopathology, with the data split by patient so that no patient appears in both training and test sets.

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

**[Quantum Classifier for the Iris Dataset](https://github.com/matheusrteixeira-dev/Quantum-Classifier-for-Iris-Dataset)**: my B.Sc. final project, a quantum support vector machine for the Iris dataset.

### Publication

<p align="center">
  <img src="assets/publication.svg" alt="Publication: Systematic Review of Quantum Machine Learning for Healthcare. Matheus Teixeira, Reinaldo A. C. Bianchi. 36th Brazilian Conference on Intelligent Systems (BRACIS 2026), Cuiabá, Brazil, October 2026." width="100%"/>
</p>

## Skills

<p align="center">
  <img src="assets/constellations.svg" alt="Skills constellation map. Machine learning: Python, PyTorch, TensorFlow, TensorFlow.js, scikit-learn, pandas, NumPy, OpenCV. Quantum: Qiskit, IBM Quantum, QSVM, quantum kernels, quantum error correction. Web and apps: TypeScript, React, Three.js, Astro, Node.js, Electron, FastAPI, Cloudflare. Systems and quality: SQL, C and C++, Rust, WebAssembly, Playwright, Vitest, pytest, GitHub Actions, Linux, LaTeX." width="100%"/>
</p>

<details>
<summary><b>All tools</b></summary>
<br/>

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

</details>

## Coursework

<p align="center">
  <a href="https://github.com/matheusrteixeira-dev/MSc-Artificial-Intelligence"><img src="assets/btn-msc.svg" alt="M.Sc. Artificial Intelligence coursework repository" width="49%"/></a>
  <a href="https://github.com/matheusrteixeira-dev/Computer-Science-FEI"><img src="assets/btn-cs.svg" alt="Computer Science coursework repository" width="49%"/></a>
</p>

<p align="center">
  <img src="assets/interests.svg" alt="Research interests orbiting quantum error correction: machine learning decoders, quantum machine learning, healthcare AI, computer vision and reproducible research." width="100%"/>
</p>

<p align="center">
  <img src="assets/footer.svg" alt="" width="100%"/>
</p>
