![thumbnail](https://user-images.githubusercontent.com/17642762/216278305-9fc9e81b-ade8-406e-8ae6-4fda9e5c2cea.png)

# Welcome to "readme-template"

> readme-template is a template that makes it easier to create files that introduce and describe projects. It includes all the contents necessary to explain the project as a mock-up.

# Table of Content

- [Project Goal](#project-goal)
- [Tech Stack](#tech-stack)
- [Download](#download-optional)
- [Example](#example-optional)
- [Quick Start](#quick-start)
- [Overview](#overview-optional)

# Project Goal

이러이러한 문제가 있어서 이 프로젝트를 통해 해결하려고 함.

# Tech Stack

Here's a brief high-level overview of the tech stack the Well app uses:

* This project uses the Flutter app development framework. Flutter is a cross-platform hybrid app development platform which allows us to use a single codebase for apps on mobile, desktop, and the web.
* For persistent storage (database), the app uses the Hive package which allows the app to create a custom storage schema and save it to a local database.
* To send local push notifications, the app uses the flutter_local_notifications package which supports Android, iOS, and macOS.
* The app uses the font "Work Sans" as its main font, and the design of the app adheres to the material design guidelines.

# Download (Optional)

You can download the latest readme-template in the following link.

**Android**
- https://play.google.com/store/apps/details?id=com.github.android&hl=ko&gl=US

**iOS**
- https://apps.apple.com/kr/app/github-wiki-search/id1594190145?mt=12

# Example (Optional)

You can try the latest readme-template example in the following link.

* https://enjoy301.vercel.app/

# Quick Start

You can start readme-template by executing following command.

1. 머시기 머시기

```bash
docker-compose up -d --build
```

2. 저시기 저시기

```bash
docker-compose down -v
```

And then access it by using a browser. http://localhost:8080

# Folder Structure

```
client
├── Dockerfile.dev                   # Dockerfile for development
├── docker-compose.yml               # Docker compose for development
└── src
    ├── index.tsx                    # Entry point
    ├── components                   # 컴포넌트 디렉토리
    │   └── Root                     # 컴포넌트는 Page 단위로 관리
    │   │   └── style.ts             # Styled-components
    │   └── ...
    ├── hooks                        # Custom Hooks
    ├── images                       # 이미지
    └── pages                        # Page 단위로 관리
        ├── root.tsx                 # Root Page
        └── ...
```

# Overview (Optional)

서비스 디테일 사진들
