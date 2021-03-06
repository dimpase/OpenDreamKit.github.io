---
layout: post
author: Nicolas M. Thiéry
title: 'Use case: Publishing reproducible notebooks (draft)'
tags:
    - use-case
    - best-practice
    - open-science
    - reproducibility
    - jupyter
    - binder
---

This document is part of a collection of [use cases](/tag/use-case).

## Scenario:

Jane has written a (math) paper based on experimentations. She would
like anyone to be able to reproduce her calculations.

## Suggestion of solution:

Describe the experimentation as Jupyter notebooks, mixing prose, code,
and outputs (think of them as logbooks). Publish them on a public
repository (e.g. on [GitHub](https://github.com), and make that
repository [binder-ready](/tag/binder). Make the paper itself active
(TODO: latexml+thebe?).

If executing the examples requires a non-trivial instal/build step,
also consider [using a
`Dockerfile`](http://mybinder.readthedocs.io/en/latest/dockerfile.html),
and auto-building the Docker image on <https://hub.docker.com/>.

## Instances

- TODO: links to favorite instances
  
  - <https://github.com/defeo/ffisom>


- TODO: estimate of the number of such instances.

## Time and expertise required

Assuming Jane is familiar with version control and Jupyter (basic lab
skills taught at Software Carpentry), and that the experiments were
prepared as notebooks, the publishing part could take two hours the
first time, and half an hour later on.

## What's new since OpenDreamKit started:

- SageMath packaged in Debian/Ubuntu
- expansion of the Jupyter technology
- apparition of binder

## OpenDreamKit contribution

- Uniform Jupyter interface to math software #xxx
- early adoption of binder
- advertising, training, providing a template (TODO!), ...

