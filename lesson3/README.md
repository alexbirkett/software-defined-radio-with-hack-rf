#Lesson 3

[Lesson 3 Video](https://greatscottgadgets.com/sdr/3/)

A decibel is typically described as a "logarithmic unit of ratio":

![10\log_{10}\frac{a}{b}](http://www.sciweavers.org/upload/Tex2Img_1409495829/render.png)

or

![20\log_{10}\frac{a}{b}](http://www.sciweavers.org/upload/Tex2Img_1409495939/render.png)


##homework
### Question
Make a column of whole decibels down the left side of the page. Fill in 0 dB, 1 dB, 2, 3, and so forth all the way to 30 dB.

Then fill in ratios in a second column in this order:

1. 1 dB (1:1), 3 dB (2:1), 6 dB (4:1), 9 dB (8:1), and so forth through 30 dB (1024:1)
2. 10 dB (10:1), 13 dB (Hint: It is 3 dB more than 10 dB.), 16 dB, and so forth through 28 dB
3. 20 dB (100:1), 23 dB, 26 dB, and 29 dB
4. 2 dB (Hint: It is 10 dB less than 12 dB.), 5 dB, 8 dB, and so forth through 17 dB
5. 1 dB (Hint: It is 10 dB less than 11 dB.), 4 dB, and 7 dB
Now you have a complete table of approximations! The worst approximation is 30 dB which should be exactly 1000:1.

Make a third column. This column will contain ratios just like the second column, but start at 30 dB instead of 0 dB. Fill in the ratios in this order:

1. 30 dB (1000:1), 27 dB (Hint: It is 3 dB less than 30 dB.), 24 dB, and so forth through 15 dB
2. 20 dB (100:1), 17 dB (Hint: It is 3 dB less than 20 dB.), 14 dB, and so forth through 5 dB
3. 10 dB (10:1), 7 dB (Hint: It is 3 dB less than 10 dB.), 4 dB, and 1 dB

It is possible to do more (for example, by starting with 12, 9, 6, and 3 dB) from this direction, but you start having to deal with more decimal places. It isn't as convenient as working with the powers of two that you used in the second column. However, just filling in a few values in the third column can give you a feeling for the amount of error introduced by using the 3 dB approximation. Notice, for example the discrepancy between the ratios in the second and third columns for 7 dB. The true value of the 7 dB ratio is between those two approximations.


### Answer

| dB | Ratio  | Question | Ratio | Question | Ratio | Question |
|----|--------|----------|-------|----------|-------|----------|
| 0  | 1:1    |          |       |          |       |          |
| 1  | 1.2:1  | 5        |       |          |       |          |
| 2  | 1.6:1  | 4        |       |          |       |          |
| 3  | 2:1    | 1        |       |          |       |          |
| 4  | 2.4:1  | 5        |       |          |       |          |
| 5  | 3.2:1  | 4        |       |          |       |          |
| 6  | 4:1    | 1        |       |          |       |          |
| 7  | 4.8    | 5        |       |          |       |          |
| 8  | 6.4:1  | 4        |       |          |       |          |
| 9  | 8:1    | 1        |       |          |       |          |
| 10 | 10:1   | 2        |       |          |       |          |
| 11 | 12.8:1 | 4        |       |          |       |          |
| 12 | 16:1   | 1        |       |          |       |          |
| 13 | 20:1   | 2        |       |          |       |          |
| 14 | 25.6:1 | 4        |       |          |       |          |
| 15 | 32:1   | 1        |       |          |       |          |
| 16 | 40:1   | 2        |       |          |       |          |
| 17 | 51.2:1 | 4        |       |          |       |          |
| 18 | 64:1   | 1        |       |          |       |          |
| 19 | 80:1   | 2        |       |          |       |          |
| 20 | 100:1  | 3        |       |          |       |          |
| 21 | 128:1  | 1        |       |          |       |          |
| 22 | 160:1  | 2        |       |          |       |          |
| 23 | 200:1  | 3        |       |          |       |          |
| 24 | 256:1  | 1        |       |          |       |          |
| 25 | 320:1  | 2        |       |          |       |          |
| 26 | 400:1  | 3        |       |          |       |          |
| 27 | 512:1  | 1        |       |          |       |          |
| 28 | 640:1  | 2        |       |          |       |          |
| 29 | 800:1  | 3        |       |          |       |          |
| 30 | 1024:1 | 1        |       |          |       |          |



### Question
Can you figure out a way to determine the precise amount of error introduced by the 3 dB approximation?
