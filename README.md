# example
simple sample files

## calendar.txt
Uses a Lazy Recursive Splitting Notation for storing data.
```
     all = [todolist <:todo:> calendar]
calendar = [month1 <:month:> month2 <:month:> month3 ...]
  month1 = [monthdate <:mdate:> weekdata]
weekdata = [week1 <:week:> week2 <:week:> week3 ...]
   week1 = [day1 <:day:> day2 <:day:> day3 ...]
    day1 = [daytext <:date:> daydata]
 daydata = [event1 <:event:> event2 <:event:> event3 ...]
  event1 = [icon <:> title <:> subtitle <:> colour]
```
