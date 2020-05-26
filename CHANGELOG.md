# Changelog

## 1.0.7

Vectors no longer extend Matrix, and each Vector's data is now an normal array instead of a multi-dimensional array. Vectors will still work the same in terms of the operations.

## 1.0.6

### Matrices

This is a big update to the vector system, as Vector now extends Matrix which stores rows and columns.
Vectors can now be any dimension, which gives much more freedom. This also means that you will now have to use `Vector.fromVector(coords)` instead of `new Vector(coords)` for specifying the coordinates. We will be removing the old vector asap. We have also added Vector.EMPTY for convience (make sure to clone it).

### New Features

- Matrices

- Easing functions