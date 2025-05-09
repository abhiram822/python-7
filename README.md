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

# first day and last day
import calendar
from datetime import date
year = 2025
month=5
fday=date(year,month,1)
lday=date(year,month,calendar.monthrange(year,month)[1])
print("firstday:",fday.strftime("%A,%Y-%M-%D"))
print("lastday:",lday.strftime("%A,%Y-%M-%D"))
