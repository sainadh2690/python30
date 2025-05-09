# print first and last date of a month
import calendar
from datetime import date
year= 2025
month= 5
fday= date(year, month, 1)
lday= date(year, month, calendar.monthrange(year,month)[1])
print("Firstday:", fday.strftime("%A, %Y-%m-%d"))
print("Lastday:", lday.strftime("%A, %y-%m-%d"))
