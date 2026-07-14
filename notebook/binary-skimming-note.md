# BINARY Quick Reading Note

## 1. Research question

Is complete gene-expression magnitude necessary for identifying spatial
domains?

## 2. Main observation

Binary expression retains considerable information about spatial tissue
structure.

## 3. Method

BINARY combines:

- binary gene-expression input;
- a spatial neighborhood graph;
- graph attention;
- a positive-aware reconstruction loss;
- embedding-based clustering.

## 4. Main contributions

1. It shows that binary expression is not necessarily inferior for spatial
   domain identification.
2. It proposes a model designed specifically for sparse binary expression.
3. It supports single-slice, multi-slice, and large-scale analysis.

## 5. Evaluation

The predicted clusters are compared with manual annotations using ARI and
NMI.

## 6. My current understanding

The scientific claim is that complete expression values are not always
necessary. The main technical contribution is BINARY, which extracts useful
spatial representations from binary data.