---
title: Custom Edge
order: 3
---

The custom edge mechanism in G6 allows users to design their own edge when there are no appropriate built-in edges for their scenario. 

## Usage

The first two demos below show how to custom polyline edge. There are two ways to custom an edge:
1. Extend the line edge, rewrite `getPath` and `getShapeStyle`;
2. Rewrite `draw`.

Updating the control points of polyline while dragging the end nodes is an important problem of polyline edge. For this situation, we recommend users to use built-in `polyline` edge.

The third demo shows how to custom an edge with multiple labels.


For more information, please refer to the document [Custom Edge](/zh/docs/manual/advanced/custom-edge).