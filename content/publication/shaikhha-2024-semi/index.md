---
title: A semi-ring dictionary query language for data science
authors:
- Amir Shaikhha
- Mathieu Huot
- Shideh Hashemian
- Amirali Kaboli
- admin
- Milos Nikolic
- Jaclyn Smith
- Dan Olteanu
date: '2024-07-01'
publishDate: '2024-09-07T21:51:25.804016Z'
publication_types: ['article']

featured: false

abstract: |
  This article introduces semi-ring dictionaries, a powerful class of compositional and purely functional collections that subsume other collection types such as sets, multisets, arrays, vectors, and matrices.
  
  We developed SDQL (Semi-ring Dictionary Query Language), a statically typed language that can express relational algebra with aggregations, linear algebra, and functional collections over data such as relations and matrices using semi-ring dictionaries. Furthermore, thanks to the algebraic structure underlying these dictionaries, SDQL unifies a wide range of optimizations commonly used in databases (DB) and linear algebra (LA). As a result, SDQL enables efficient processing of hybrid DB and LA workloads, by putting together optimizations that are otherwise confined to either DB systems or LA frameworks.
  
  We show experimentally that a handful of DB and LA workloads can take advantage of the SDQL language and optimizations. SDQL can compete with or outperform a host of systems that are state of the art in their own domain: in-memory DB system DuckDB for (flat, non-nested) relational data using both traditional query operators and worst-case optimal joins; SciPy for LA workloads; sparse tensor compiler TACO; the Trance nested relational engine; and the in-DB ML engines LMFAO and Morpheus for hybrid DB/LA workloads over relational data.

links:
- name: Benchmarks
  url: https://github.com/edin-dal/sdql-benchmark
url_pdf: https://www.research.ed.ac.uk/en/publications/a-semi-ring-dictionary-query-language-for-data-science
url_code: https://github.com/edin-dal/sdql
---
