---
{"publish":true,"created":"2024-11-21T06:17:22.000-05:00","modified":"2025-08-17T17:05:17.378-04:00","cssclasses":""}
---

#math/geometry #math/geometry/2d #math/geometry/2d/shape/circle , [[Circle]], [[Tangent of circle]], [[Chord]] 


- There are [[Circle]] [[Theorem\|theorems]] which are js facts or statements about every circle that have been proved.
	- [[Chord]]
	- [[Tangent of circle]]
	- [[major segment and major arc]]
	- [[minor segment and minor arc]] 
- [[Proving that all circles are similar]]
- [[radii and tangent lines are perpendicular]]
- [[Inscribed angles are half of central angles]] 
- [[central and circumscribed angles are supplementary]]
- [[intersecting chords of a circle]]

## Tangents that meet at the same point are the same length 
- When [[Tangent of circle\|tangent lines]]-[[Intersect\|intersect]] they both have the same [[Length and Width\|length]] from the [[circumference]] to the point they intersect. 
	![[Files/Pasted image 20240801153110.png|200]]
	- In diagram 1 the tangent meets the [[Circle]] at point $A$ which is [[Perpendicular]] to the [[radius]] of the circle at that point
	- In diagram 2, two tangents meet the circle at 2 different points ($B$ and $D$) and they intersect at point $A$. If the points $B$ and $D$ are linked by a [[Chord\|chord]] $AB$ and $AD$ are the same length so $ABD$ is an [[isosceles triangle]]
		- If points $B$ and $D$ join the center of the circle, $C$ they form a [[kite]] $ABCD$. This means we have 2 circle theorems:
			![[Files/Pasted image 20240801162751.png|200]]
- Proof:
	- Take an arbitrary point labeled $A$ (random [[point]] in [[plane\|space]]) outside of the [[Circle]]
	- The point $A$ can be connected to the [[Circle]] by 2 [[Tangent of circle\|tangents]]. One [[line]] touches the circle at $B$ the other at $C$ 
		![[Files/Pasted image 20240801163606.png|200]]
	- If we join $OA$ together and connect $OB$ and $OC$ we construct 2 triangles 
		![[Files/Pasted image 20240801163730.png|200]]
	- Angles ${} OBA {}$ and $OCA$ are $90^{\circ}$ since [[radius\|radii]] and tangents are [[Perpendicular]] when they share a point on the [[circumference]]. This means that ${} \triangle AOC {}$ and $\triangle AOB$ are [[Right Triangle\|right triangles]]. $OC$ and $OB$ are both [[radius\|radii]] so they must be the same length.
	- Triangles $AOB$ and $AOC$ are both [[Right Triangle\|right triangles]] meaning they both have a $90^{\circ}$ angle. They share side $AO$ and side $OC=OB$. This means that $\triangle AOB \cong \triangle AOC$ which means that $CA=BA$. 
## Alternate segment theorem

- The angle that lies between a [[Chord\|chord]] and a [[Tangent of circle\|tangent]] is equal to the [[Angles\|angle]] [[subtend\|subtended]] by the same [[Chord\|chord]]
	![[Files/Pasted image 20240801091518.png|200]]
	- Proof:
	- Let $ABC$ be a [[Triangle]] within a [[Circle]] with center $O$. The [[Tangent]] $DE$ passes through the point $A$ on the [[circumference]] of the circle only. The line $AB$ is a [[Chord\|Chord]] and point $C$ lies on the [[major segment and major arc\|major arc]] 
		![[Files/Pasted image 20240801093508.png|200]]
	- Draw 2 lines $OA$ and $OB$. They go from the center to the [[circumference]] of the [[Circle]]. Both lines are [[radius\|radii]]. Both $OA$ and $DE$ are [[Perpendicular]] since the [[Tangent of circle\|tangent of a circle]] and a [[radius]] meets at $90^{\circ}$
		![[Files/Pasted image 20240801100907.png|200]]
	- Since both $OA$ and $OB$ are [[radius\|radii]], $OAB$ is an [[isosceles triangle]] this means that angles $A$ and $B$ are equal. Here we labeled them as $x$
		![[Files/Pasted image 20240801103116.png|200]]
	- $AB$ is a chord which means the [[line]]-[[Perpendicular]] to the [[Chord\|chord]] from the center is a [[perpendicular bisectors\|Perpendicular Bisector]] of $AB$. This creates 2 [[Right Angle\|right angles]] and 2 [[congruent]] [[Triangle\|triangles]]
		![[Files/Pasted image 20240801104201.png|200]]
	- Triangles $OFA$ and $OFB$ are [[congruent]] so the angles $AOF$ and $BOF$ are also the same. We can label them both as $y$
		![[Files/Pasted image 20240801121852.png|200]]
	- We know that $OAE$ is a $90^{\circ}$ angle from a before step. $OAF$ is a [[Right Triangle]] which means that $x+y=90^{\circ}$. This means that angle $FAD$ is also equal to $y$ 
		![[Files/Pasted image 20240801122050.png|200]]
	- Angle $O$ is $2y$ since originally $AOB$ was made up of $y+y=2y$ 
		![[Files/Pasted image 20240801122217.png|200]]
	- As the angle at the center is twice the angle at the [[circumference]] we can say that angle $C$ is equal to $y$. This means that $\angle DAB=\angle ACB$ 
	- Since $AB$ is the chord the angle at $C$ is the alternate [[Line Segment\|segment]] to angle $DAB$ so we get that angles in the alternate segment are equal.


