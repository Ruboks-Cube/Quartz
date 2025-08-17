---
{"publish":true,"created":"2024-11-21T06:17:31.000-05:00","modified":"2025-08-17T17:05:35.684-04:00","cssclasses":""}
---

#math/geometry/2d/shape/Triangle , [[Triangle]].


We use the Pythagorean theorem to find the [[Hypotenuse]] of a [[Right Triangle]]

### Proving the Pythagorean Theorem

#### Square or not square?
![[Files/Images/Pasted image 20240219200701.png|200]]
- All triangles are identical/[[congruent]] and form to make a square. How do we know that the middle shape is a square? The angles in a [[Triangle]] have to be 180 degrees, and we know the 4 corners of the big blue square is 90 degrees. This means the other 2 angles must add up to 90 degrees.

- If you look at a vertex of the black square it must be 90 degrees because we know that it's [[Straight angles\|supplementary angle]], the angles of the blue triangles add up to 90 degrees so the little squares angles must be 90 degrees.
![[Files/Images/Pythagorean Theorem 2024-02-20 06.44.31.excalidraw]]

- Now that we have covered that the little square is in fact a square, we can move on to proving the Pythagorean theorem. 

-  We find why the Pythagorean theorem works by [[solving multi variable equations in terms of another variable]], in this case, we're solving for $c$ in terms of $a$ and $b$.
#### Actually proving it now
![[Files/Images/Pythagorean Theorem 2024-02-20 06.51.57.excalidraw]]
First, we find the area of the big square.

We can find it in 2 different ways, adding the side length and multiplying it out, or finding the area of each individual triangle.

To find the area of each triangle then the whole square we do this: (Multiplying the area of the triangles by 4, then adding the area of the little square)
$$4\left(\frac{ab}{2}\right)+c^2$$
This is finding the area of each triangle, but what we also know is that the above expression has to equal this as well:
$$\left(a+b\right)^2$$
Both find the [[Area]] of the big square.
$$\left(a+b\right)^2=\left(a+b\right)\left(a+b\right)$$
[[double distribution\|Double distributing]] this we get:
$$a^2+2ab+b^2$$
So now we have:
$$4\left(\frac{ab}{2}\right)+c^2=a^2+2ab+b^2$$
We can also simplify the left side:
$$4\left(\frac{ab}{2}\right)+c^2=\frac{4ab}{2}+c^2=2ab+c^2$$
Now we have:
$$2ab+c^2=a^2+2ab+b^2$$
Subtracting 2ab from the [[equations\|Equation]] and flipping it gives us:
$$a^2+b^2=c^2$$    
#### Proving it a second time
![[Files/Images/Pythagorean Theorem 2024-02-20 07.06.08.excalidraw]]
This time our [[Right Triangle]]s are positioned a bit differently.
We still make two squares, the sum of the [[Acute Angle]]s are 90.
We have sides b, a, and c, and we will also still find the area of the big square differently.

We have $$c^2$$
and $$4\left(\frac{ab}{2}\right)+\left(b-a\right)^2$$
Both of these equal the area of the whole thing so we have:
$$c^2=4\left(\frac{ab}{2}\right)+\left(b-a\right)^2$$
We can simpify (b-a) squared to
$$\left(b-a\right)\left(b-a\right)=b^2-ab-ab+a^2$$
This equals 
$$b^2-2ab_{}+a^2$$We can also simplify 4(ab/2) into
$$2ab$$
So now we have:
$$c^2=2ab+b^2-2ab+a^2$$
Which simplifies to...$$c^2=b^2+a^2$$
so now we have TWO proofs. 
### Pythagorean theorem problems
[[Finding Length of Hypotenuse with a and b]]
[[Finding Length of leg with a and c]]