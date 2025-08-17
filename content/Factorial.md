---
{"publish":true,"created":"2024-11-21T06:17:25.000-05:00","modified":"2025-08-17T17:05:23.745-04:00","cssclasses":""}
---

#math/Probability_Permutations_Counting [[Counting]] 


So we know that we can [[Counting with Multiplication\|Count With Multiplication]] to represent how many possible choices we have, but what about using [[Multiplication]] to represent how many combinations, or [[counting permutations\|permutations]] there are? The use case is very very similar.

# Key ideas
- A factorial is used to [[Counting with Multiplication]] to find how many different combinations there are possible.
- We do factorials by doing a!, where a represents the number
- A factorial means multiplying all the integers within a and 1. (Both included)


# Problems
## How many ways to stack a book?

This guy has 4 books, and he wants to know how many possible combinations the books can be in when they are stacked.

- Any one of the books can be the first book
	- We have 4 possible choices for the first book
	- 3 possible choices for the second book
	- 2 possible choices for the third book
	- 1 possible choice for the last book
![[Files/Images/factoral 2024-03-24 13.08.03.excalidraw\|300]]
This is what the diagram would look like for this problem.

For the first choice, we have 4, for the 2nd choice, 3, for the 3rd, 2, and for the last choice, 1, showing the order of these books is just a [[Counting with Multiplication]] problem.
![[Files/Images/Pasted image 20240324131405.png|200]]
This image here is a better representation of the problem. If each color represents a book, this represents the amount of choices.
This gives us 24 ways to stack the books.

The main difference between [[Counting with Multiplication]] and this problem is that with the other problems in counting with multiplication, they were independent events, but for this one it is not an independent event. Once you choose a book you cannot choose it again, thats the difference.

What matters however is that the *number* of choices is independent, no matter what book you choose first, you have 3 books for the 2nd choice.

Adding more and more books means multiplying the largest number, then largest number -1 and so on until you reach 1.

This is called a factorial