---
title: "Step by step, convertion from decimal to binary"
excerpt: "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Praesent elementum facilisis leo vel fringilla est ullamcorper eget. At imperdiet dui accumsan sit amet nulla facilities morbi tempus."
coverImage: "/assets/blog/preview/cover.jpg"
date: "2020-03-16T05:35:07.322Z"
author:
  name: Abrahan First
  picture: "/assets/blog/authors/one.jpeg"
ogImage:
  url: "/assets/blog/preview/cover.jpg"
---

## To convert a number from decimal to binary:

1.- Divide the original number by 2. The remainder becomes the least significant bit in the binary number.

2.- Divide the result of the division from Step 1 by 2. The remainder becomes the next most significant bit of the binary number.

3.- Repeat the division process until the result is 0. The remainders form the binary number.
Let's take the number 35 as an example:

35 divided by 2 = 17 Remainer 1
17 divided by 2 = 8 Remainer 1
8 divided by 2 = 4 Remainer 0
4 divided by 2 = 2 Remainer 0
2 divided by 2 = 1 Remainer 0
1 divided by 2 = 0 Remainer 1

The binary version of 35 would be 100011


## To convert a number from binary to decimal:

Let's now look at binary-to-decimal conversion. Here we simply multiply the binary digits by increasing powers of 2, starting from the right. Let's walk through the steps involved in converting the binary number 101 into decimal format:

1.- The rightmost digit is a 1, so you multiply it by 2 to the 0th power (or 1): 1 × 1 = 1.

2.- Multiply the next digit to the left (0) by 2 to the first power (or 2): 0 × 2 = 0.

3.- Multiply the next digit to the left (1) by 2 to the second power (or 4): 1 × 4 = 4.

4.- Now, to find the decimal number, you find the sum of these products: 1 + 0 + 4 = 5. 

Therefore, 101 in binary equals 5 in base 10. 
