# python-7
calendar 
# full calendar 
import calendar
year=int(input())
month=int(input())
print(calendar.calendar(year,month))

# month
import calendar
year=int(input())
month=int(input())
print(calendar.month(year,month))

# leapyear
import calendar
leap=calendar.leapdays(1947,2025)
print(leap)

# leap year or not
import calendar
print(calendar.isleap(2028))
