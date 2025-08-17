---
{"publish":true,"created":"2024-11-21T06:17:35.000-05:00","modified":"2025-08-17T17:05:43.263-04:00","cssclasses":""}
---

#math/geometry/2d/shape #math/geometry/2d/Perimeter_Area 

## Introduction
https://artofproblemsolving.com/videos/prealgebra/chapter11/203

An [[isosceles triangle]]s sides have lengths 3 and 8, what is the third side? 

Using the fact that this is an isosceles triangle, we know the possible side lengths are 3 and 8.

So we can try making a diagram for 3 and 8, but you will notice when you have 2 side lengths with 3, and 1 with 8, the side lengths with 3 are too small. They are not long 
enough to reach!

The answer must be 8.

## Rule

For any 3 points of a [[Triangle]] A, B, and C,  we must have:
$$AB+BC\ge AC$$
We only have $$AB+BC=AC$$
if B is on line AC
![[Files/Images/The triangle Inequality 2024-02-13 19.15.26.excalidraw]]

In other words, the sum of the shortest side and the middle side must be equal to or more than the longest side. The only way that it is equal to is if it's a line, AB + BC will equal C if it's a [[Line Segment]]. 

This makes sense, because for the middle and shortest side to reach, they must be able to cover the distance of the longest side and reach at a point.

## Use cases

The triangle inequality tells us if a triangle with certain side lengths are possible. You only have to test the sum of the 2 smaller sides since the largest side is always going to have a sum greater than the other 2.
