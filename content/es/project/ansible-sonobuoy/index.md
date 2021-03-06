---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Rol de Ansible para Sonobuoy"
summary: "Ansible role that installs Sonobuoy"
authors: [ luis ]
tags: [ Ansible, Galaxy, Code, Kubernetes, Python, Cloud Native]
categories: [ Ansible, Kubernetes ]
date: 2019-10-24T01:42:23-05:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Sonobuoy Logo"
  focal_point: "Center"
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: Ansible Role
  url: https://github.com/k4ch0/ansible-sonobuoy-ubuntu
  icon_pack: fab
  icon: github

- name: Sonobuoy
  url: https://github.com/vmware-tanzu/sonobuoy
  icon_pack: fab
  icon: github

url_code: "https://galaxy.ansible.com/k4ch0/sonobuoy"
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

Rol de Ansible que instala la herramienta que valida la configuración de Kubernetes, [sonobuoy](https://sonobuoy.io/) en su servidor/workstation.

[![Build Status](https://travis-ci.com/k4ch0/ansible-sonobuoy-ubuntu.svg?branch=master)](https://travis-ci.com/k4ch0/ansible-sonobuoy-ubuntu)