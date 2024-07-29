# dev_sandbox_ml.ajc

Technology-agnostic sandbox environment for developing implementations of Machine Learning.

## Table of Contents

Table of contents for the project.

## Overview

Overview of the project.

## Purpose Statement

This repo is a sandbox environment for developing implementations of Machine Learning. It is technology-agnostic, meaning that it is not tied to any specific technology stack. The purpose of this repo is to provide a place where developer AJC and contributing developers can experiment with different Machine Learning algorithms and techniques, without having to worry about the underlying technology. This repo is mainly personalized for developer AJC, as a categorical organizational repo but it is open to contributions from other developers if the code is worth reviewing.

## Initial Suggested Directory Structure Example

```plaintext
dev_sandbox-ml.ajc/
│
├── README.md
├── .gitignore
├── requirements.txt
│
├── projects/
│   ├── twitter-image-saver/
│   │   ├── README.md
│   │   ├── requirements.txt
│   │   ├── config/
│   │   │   └── config.yaml
│   │   ├── src/
│   │   │   ├── main.py
│   │   │   ├── twitter_api.py
│   │   │   ├── image_saver.py
│   │   │   └── utils.py
│   │   ├── scripts/
│   │   │   ├── run_script.bat
│   │   │   └── setup_env.bat
│   │   ├── logs/
│   │   │   └── .gitkeep
│   │   └── tests/
│   │       ├── test_twitter_api.py
│   │       ├── test_image_saver.py
│   │       └── test_utils.py
│   ├── project2/
│   └── project3/
│
├── categories/
│   ├── image-processing/
│   │   ├── README.md
│   │   ├── projectA/
│   │   └── projectB/
│   ├── natural-language-processing/
│   │   ├── README.md
│   │   ├── projectC/
│   │   └── projectD/
│   ├── data-analysis/
│   │   ├── README.md
│   │   ├── projectE/
│   │   └── projectF/
│   └── other-category/
│       ├── README.md
│       ├── projectG/
│       └── projectH/
│
└── scripts/
    ├── common_script.bat
    └── setup_common_env.bat
```