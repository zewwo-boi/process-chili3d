# Getting Started

## About

This project is used to process user-operations tracing data collected from "chli3d"

## Terminology

There are some confusing terms regarding how data is stored.

- Record - A block of data that can represent anything, including 3D objects (see "node"), properties of 3D objects, and arrays of other records.
  - Time Record - The root object that represents the state at a point in time. Contains other records.
  - Node Record - 3D object. Can also include properties in its record.
  - Property Record - Property of a node.
  - Array Record - Contains other records excluding time records.
