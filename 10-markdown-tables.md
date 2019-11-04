# Tables
We can create pretty decent looking tables using markdown. It's not the simpliest to grasp at first, but it works well and after a little practice it's very easy to get.

To create a table we basically have to have the data we'd like in the table and then we put pipes (```|```) between the different table cells.

This makes much more sense as seen visually in the code below. Once the table is setup/mocked-up and ready to be tweaked, we must enter in the colon (```:```) and dash (```-```) sections specific to our formating desires.

### Olais Family
| Name      | Sibling # | Sex   | Age |
|:---       |:---       |:---   |:--- |
| Papa      | N/A       | M     | 55  |
| Mama      | N/A       | F     | 51  |
| Melgine   | 1         | F     | 33  |
| Enes      | 2         | F     | 28  |
| Ares      | 3         | F     | 26  |
| Ame       | 4         | F     | 23  |
| Titing    | 5         | M     | 21  |
| Ynot      | 6         | F     | 19  |
| Eros      | 7         | F     | 17  |
| Ejay      | 8         | M     | 13  |

As for justification of the data, it's pretty particular, but once you get the concept, it's very simple.<br>

As mentioned above, the code that turns the above data into an actual displayed table in the markup is the second line with the colon (```:```) and dash(es) (```---```).

#### Left Justification
If we want the column data left justified we put the **colon** directly against the left pipe (```|```), as can be seen in the above table.

#### Right Justification
If we wanted the data justified right, we would take that **colon** and put it up against the right hand pipe **of the specific column we want this applied too**.

#### Center Justification
And as we could figure out based on the left/right rules, if we wanted center justification, we would put colons (```:```) on both **insides** of the pipes of the specific column we wanted it applied too.

***

Below I will take the same table as above, and apply some left, center and right jutification to it.

*_Note that the colons (```:```), whether set for left, right, or center justifications, must be up against the dashes to work. It's a bit of a picky system but it does work once you get it._

| Name      | Sibling # | Sex   | Age |
|:---:      |---:       |:--:   |:---:|
| Papa      | N/A       | M     | 55  |
| Mama      | N/A       | F     | 51  |
| Melgine   | 1         | F     | 33  |
| Enes      | 2         | F     | 28  |
| Ares      | 3         | F     | 26  |
| Ame       | 4         | F     | 23  |
| Titing    | 5         | M     | 21  |
| Ynot      | 6         | F     | 19  |
| Eros      | 7         | F     | 17  |
| Ejay      | 8         | M     | 13  |

*_Columns 1, 3 & 4 in the above table are center justified and column #2 ('Sibling #'), is right justified._

Note, that each markdown renderer will display certain aspects of markdown differently, and tables are definitely one of the 'aspects' affected.

In VSC's markdown preview tab, the table is displayed one way, in Github, it's displayed more like a 'Bootstrap' table.

The look of the actual tables can be controlled via CSS if access to the stylesheet is available.