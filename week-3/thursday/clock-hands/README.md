![GA Cog](https://camo.githubusercontent.com/6ce15b81c1f06d716d753a61f5db22375fa684da/68747470733a2f2f67612d646173682e73332e616d617a6f6e6177732e636f6d2f70726f64756374696f6e2f6173736574732f6c6f676f2d39663838616536633963333837313639306533333238306663663535376633332e706e67)
# WDIplus-ATX 
---
Title: Clock Hand Angle Calculator <br>
Type: Morning Exercise<br>
Duration: "0:45"<br>
Creator:<br>
    Original creators: GA Instructional Team<br>
Competencies: Logic, Javascript<br>
Prerequisites: Javascript <br>

---

# Morning Exercise

## Setup
1. Navigate into your warm ups folder for today.
2. Create a file called `clock_hands.js` file to write your code for this morning's exercise.
3. You will be running this file from your terminal using `$ node clockhands.js`

## CLOCK HAND ANGLE CALCULATOR

![clock](https://orpheogroup.com/wp-content/uploads/2014/10/grand-central-clock-crop.jpg)


Write a function `clock` that takes two integers, `hour` and `minute`. The function should calculate the two angles in degrees between the **hour hand** and **minute hand** on a twelve-hour analog clock face.

Note that the hour hand has 'drift'. If the time is **6:30**, the hour hand will be halfway through its travel between **6** and **7**. If the time is **9:45**, the hour hand will be three quarters of the way between **9** and **10**.

Return an "out of range" message if an input is greater than the clock's range.


Expected output:

```
clock(6, 00)

=> [180, 180]
```

```
clock(12, 00)

=> [360, 0]
```

```
clock(12, 15)

=> [277.5, 82.5]
```

```
clock(9, 45)

=> [22.5, 337.5]
```

```
clock(1, 59)

=> [294.5, 65.5]
```

```
clock(500, 34)

=> "out of range"
```

Hint: Drawing the outputs with pencil and paper may help you understand and solve the problem.
