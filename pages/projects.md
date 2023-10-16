---
title: Projects - Anthony Fu
display: Projects
description: List of projects that I am proud of
plum: true
wrapperClass: 'text-center'
projects:
  
  Demo:
    - name: 'Project Name 1'
      link: 'https://github.com/xxxxx/xxxxx'
      desc: 'Project Description'
    - name: 'Project Name 2'
      link: 'https://github.com/xxxxx/xxxxx'
      desc: 'Project Description'
    - name: 'Project Name 3'
      link: 'https://github.com/xxxxx/xxxxx'
      desc: 'Project Description'
---

<!-- @layout-full-width -->

<ListProjects :projects="frontmatter.projects" />

