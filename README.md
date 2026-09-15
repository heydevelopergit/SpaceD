# SpaceD
### SpaceDaemon — A containerized OS with firmware, recovery, and security.

---

## 🔥 What is SpaceD?

**SpaceD** is a lightweight, containerized operating system built on **Alpine Linux**.

---

## 🚀 Quick Start (Local Build) - Recommended

git clone https://github.com/heydevelopergit/SpaceD && cd SpaceD && mkdir release && cp release.zip release/ && cd release && unzip release.zip && rm -rf release.zip && docker build -t spaced:latest . && docker run -it --privileged -v ~/data:/dat spaced:latest

## 🚀 Quick Start (Docker Build)

docker pull heydevelopergit/spaced
