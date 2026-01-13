# calendar-program-04
import datetime
import calendar

day = int(input("Enter today's date (day only): "))

now = datetime.datetime.now()
year = now.year
month = now.month

total_days = calendar.monthrange(year, month)[1]
remaining_days = total_days - day

print("Total remaining days in the current month are:", remaining_days)
