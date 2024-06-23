---
title: Enhancing recursive graph querying on RDBMS with data clustering approaches
authors:
- L. C. Scabora
- Gabriel Spadon
- Paulo H. Oliveira
- José F. Rodrigues
- C. Traina
date: '2020-01-01'
publishDate: '2024-06-23T19:22:55.337872Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 35th Annual ACM Symposium on Applied Computing*'
doi: 10.1145/3341105.3375770
abstract: Recursive queries are one of the main mechanisms in Relational Database
  Management Systems to process topology-aware, or graph-like, queries. However, existing
  works focus only on optimizing the recursive query statements and processing, disregarding
  the potential physical arrangements that might improve performance. In this work,
  we propose to use an approach based on adjacent-list storage to physically organize
  the graph-like data aiming at both reducing the recursive query time and the number
  of I/O operations. By using Clustered Tables, we tied the adjacency list in chunks
  for (i) storing both vertex and edge tables together in a Combined Tables approach;
  and (ii) reordering the edge table with the Edge Clustered Table approach using
  20% and 80% of the total adjacency list size. The clustered approaches enabled a
  faster recursive query processing (up to 22%) and a reduction of up to 61% in the
  number of page accesses when compared to the Conventional approach. When starting
  from multiple vertices, the Combined Tables approach achieved a query reduction
  time of up to 50% in the first join operation, and Edge Clustered Table 20% provided
  an overall time reduction of up to 20%. The results show that our physical design
  is effective and allows one to use recursive queries without adaptations.
links:
- name: URL
  url: https://www.semanticscholar.org/paper/0fab5869fe9f31cfc16a13e259e6cde2bd7af26d
---