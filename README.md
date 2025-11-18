# Final_Exam_Review

Question 1

There was an error in this command because the function AVG was not included when group by was used. 
Both boohbah_id and name needed to be in group by 

Question 2 

The link table was not used. It was to link boobah and stand_use directly. 

Question  3

There is no such thing as boobah_name in boohbah. There is a name though. 

Question 4

Some of the values did not use aliases when others did so I just implemented aliases to the ones that did not have them. 

Question 5

  WHERE boohbah_id = boohbah_id compares the column to itself so it is airways right. I just removed that

Question 6

The subquery outputs multiple rows and you cannot use > with multiple rows

Question 7

Missing the join created a cartesian result. The link table was needed to properly connect Boohbahs to their assigned Stands.

Question 8

A user can not directly use the AVG function in the WHERE clause. I fixed it by selecting the average syc_level from the link table.

Question 9 

The code was too long; it could have been more simple this whole time.

Question 10

The join condition b.boohbah_id = s.stand_id compares unrelated ID columns from different tables. 
