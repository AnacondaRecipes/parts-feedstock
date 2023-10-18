# parts-feedstock

This library provides a function for partitioning iterable data structure instances. When the number of parts is
specified explicitly, it is treated as a strict requirement and an exception is raised when it cannot be satisfied.
When a length for all parts (or each part) is specified explicitly, a best-effort approach is used: as many parts
of the specified length are retrieved as possible, with the possibility that some parts at the end of the partition
sequence have a shorter (but still non-zero) length.

## Home:
https://github.com/lapets/parts

## Upstream license:
MIT

## Feedstock license:
BSD-3

## Docs:
https://github.com/lapets/parts

## Dev repo:
https://github.com/lapets/parts