# `mdAL` Demo Project

[![Gitpod ready-to-code](https://img.shields.io/badge/Gitpod-ready--to--code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/mdal-lang/mdal-demo)

This repository contains a demo project showcasing the features of [`mdAL`](https://github.com/mdal-lang/mdal). `mdAL` is a Domain Specific Language that enables a Model-Driven approach to extension module development for the ERP System Microsoft Dynamics 365 Business Central. `mdAL` stands for **m**odel-**d**riven **AL**.

## Try now

Try `mdAL` with this demo project inside the online IDE Gitpod. For more information on `mdAL` visit [mdal-lang.github.io](https://mdal-lang.github.io/#/).

[![Edit with Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/mdal-lang/mdal-demo)

## Contents

This repository holds the following contents:

* `src/seminar-management.mdal`: This `mdAL` model file defines an AL solution for seminar management (cf. Microsoft official training material: Course 80437 — C/SIDE Solution Development in Microsoft Dynamics® NAV 2013). Once opening this file inside VS Code with the [`mdAL` VS Code extension](https://github.com/mdal-lang/mdal-extension) installed you can generate the corresponding AL code by right-clicking inside the model file or using the command palette. After the code generator finished you will find the AL code in the `src-gen` folder. For more information on the features of the `mdAL` extension visit the [mdal-lang/mdal-extension](https://github.com/mdal-lang/mdal-extension) repository.
* `.github/workflows/build.yml`: This GitHub Actions workflow file showcases how `mdAL` can be used inside a CI/CD pipeline. In this project the [`mdAL` Action](https://github.com/mdal-lang/mdal-action) has been used to provide standalone AL code generation. On other CI environments you can also use the [`mdal/cli` docker image](https://hub.docker.com/r/mdal/cli) in order to call the code generator from the command line.

This project is complemented by the repository [`mdal-lang/mdal-demo-extension`](https://github.com/mdal-lang/mdal-demo-extension) which adds e. g. customizations to the generated posting routines through event subscribers.

## License

MIT (c) Jonathan Neugebauer
