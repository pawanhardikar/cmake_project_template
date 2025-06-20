# Cpp DevOps Boilerplate

Powered by [Cookiecutter](https://github.com/cookiecutter/cookiecutter), cpp_devops_boilerplate is a framework for jumpstarting
production-ready CPP projects quickly.

- If you have problems with Cpp DevOps Boilerplate, please open [issues](https://github.com/pawanhardikar/cmake_project_template/issues) don't send
  emails to the maintainers.

# What Am I and why am I special?

  - I am a cookiecutter template and I am here to kickstart your CPP projects. I provide a defined structure on the directories that is usually present in a CPP project.(src/include/test). Then currently I provide build tools like CMake which can be modified/extended based on your specific needs, currently I am fully capable of building a simple cpp project and more functionalities will be added in coming days. I also provide CI/CD pipelines (Jenkins and GitHub Actions) as well. 
  - I consider myself special because there are a lot of cookiecutter templates available in the market for Python,Django, FastAPI, React, Postgre etc. but this I am the **First** one that is available for **CPP**.


## Features

- [x] Cmake Template for building CPP Code Base.
- [x] Conan as package manager with CMake to build CPP Code Base.
- [x] Support to Ctest.
- [ ] Support to Google test.
- [ ] Building up a Docker container for a dev environment.
- [x] Jenkins Declarative pipeline.
- [ ] GitHub Actions.
- [ ] Static Code Analysis using SonarQube.
- [ ] Artifcatory Workflow.
- [ ] Monitoring & Observability using ELK and Grafana.
- [ ] Documentation generation using sphinx.

## NOTE: 
- Please note that this repository is under active development and the features that are currently available are marked in README. More features will be added soon.


- I am using Renovate in my template so all the dependencies will be updated to the latest versions available in the market for public use. I suggest everyone using this template could also use renovate in their projects so that their tools remain updated as well.
  - Steps to use Renovate: 
    - Go to: 👉 https://github.com/apps/renovate
    -  Click "Configure"
    - Select your GitHub account/org    
    - You can choose any particular repos in your account or you can select all the repositories in your account.
    - Click "Install"
    - Once done a PR will be created that you can merge to your main branch and then renovate automatically handles the updates and create a PR that you can merge later if you are okay with the updates.
    - These updates can be done to docker base images in your dockerfile(If present).
    - Actions version in GitHub Actions(example: @v2, @v3 etc.)
    - If there's any requirements.txt file it can handle those or any pip files in python projects.
