# This code is typed by VS code
# Example file for Helloworld
#


#def main():
    #print("Hello World")
    #name = input("What is your name? ")
    #print("Nice to meet you,", name)


    #if __name__ == "__main__":
        #main()

 x = "hello"   
print(x)
#print("Hello World")

#f=0
#print(f)
#f="abc"
#print(f)
#print("This is a string " + str(123))

#def someFunction(): 
    #global f
    #f="def"

#someFunction()
#print(f)

# define a basic function

#def func1():
    #print("I am a Mathematician")

#func1()
#print(func1())
#print(func1)
 
# defin function that takes argument

# def func2(arg1, arg2):
#     print(arg1, " ", arg2)

#define function that returns a value

# def cube(x):
#     return x*x*x

# func2(10,20)
# print(func2(10,20))
# print(cube(3))

#define function with default value for an argument

# def power(num, x=1):
#     result = 1 
#     for i in range(x):
#         result = result*num
#     return result

# print(power(2))
# print(power(2,3))
# print(power(x=3, num=2))

#define function with variable number for an argument
# def multi_add(*args):
#     result = 0 
#     for x in args:
#         result = result + x
#     return result

# print(multi_add(4, 5, 10, 20))

#
# Example file for working with conditional statements

# conditional flow uses if, elif, else


# x= 100
# y= 100
# if (x < y):
#  st = "x is lss than y"
# elif (x == y):
#     st = "x is the same as y"
# else:
#     st = "x is greater than y"
# print(st)

# # conditional statements let you use "a if C else b"
# st = "x is less than y" if (x<y) else "x is greater than or the same as y"
# print(st)

# define a wh1le loop
# x = 1
# while x < 5:
#   print(x)
#   x += 1

# define a for loop

# for x in range(5, 10):
#     print(x)

#  use a for loop over a collection

# days=["Mon", "Tue", "Wed", "Thu", "Fri", "Sat", "Sun"]
# for d in days:
#     print(d)

# use the break and continue statements
# for x in range(5,10):
#     #if (x==7): break
#     if x % 2 == 0: continue
#     print(x)

# using the enumerate() function to get index

# days=["Mon", "Tue", "Wed", "Thu", "Fri", "Sat", "Sun"]
# for i, d in enumerate(days):
#     print(i, d)

# Example file for working with classes

#

# class myClass():
#   def method1(self):
#     print("myClass method1")

#   def method2(self, someString):
#     print("myClass method2" + someString)


    
# class anotherClass(myClass):
#   def method1(self):
#     myClass.method1(self)
#     print("anotherClass method1")

#   def method2(self, someSrring):
#     print("anotherClass method2")
      
#   def main():
#    c = myClass()
#    c.method1()
#    c.method2("This is a string")  

#    c2=anotherClass
#    c2.method1()
#    c2.method2("This is a string ")    

# import math module, which contains features for working with math

#import math

# # the math module contains lots of pre-built functions

# print("The squre root of 16 is ", math.sqrt(16))

# # in addition to functions, some modules contain useful constants

# print("Pi is:", math.pi)

# # try some of the math function for yoursel here:

# # This is  correct
# def Calc(currency, *rates):
#      for i in rates:
#        print(currency*i)

# # This is  wrong

# def Calc(*currency, rates):
#       for i in rates:
#        print(currency*i)
    
# # This is  wrong

# def Calc(currency, rates):
#       for i in rates:
#        print(i*currency)

# #This is  wrong

# def Calc(*rates, currency):
#   for i in rates:
#     print(currency+i)


# What code will you need to place instead of the ??? placeholder for the script to print '3'?
 

# a=1
# b=2
# def func():
#         ???
# func()
# print(b)


# 1. global a
# b=3

# 2. b=b+1

# 3. global b
# b=a+b

# 4. b=a+a+a

# the answer is 

# a=1
# b=2
# def func():
#        global b
#        b= a+b
# func()
# print(b)


# You have an existing class Simple() that returns the sum of two numbers using its Add(x,y) method. How can you leverage it to build another class that calculates the inverse of the sum of two numbers?

# This is  wrong

# class Advanced(Simple):
#   def Inverse(x,y):
#     sum=Simple.Add(x,y)
#     return (1/sum)

# This is correct 

# class Advanced(Simple):
#   def Inverse(self,x,y):
#     return (1/Simple.Add(self,x,y))

# This is  wrong

# class Advanced():
#   def Inverse(self,x,y):
#     return (1/Simple.Add(x,y))

# This is  wrong

# class Advanced():
#   def Inverse(x,y):
#     return (1/(x+y))

#This code has three critical issues. Which is not actually an issue

# def main:
#    print(hello!)

# 1. The function must be defined with the keyword 'func', not 'def'
# 2. The string to print is missing quotes before and after it
# 3. The print statement needs to be indented using spaces or a tab
# 4. The function definition is missing parentheses that define the argument list

# the answer is 1.

# In Python, what is the correct way to develop a class called Person that has parameters in the initialize function called name, age, and sex?

#This is  wrong
# class initialize:
#   def __Person__(self, name, age, sex):
#     self.name = name
#     self.age = age
#     self.sex = sex     

#This is the answer

# class Person:
#   def __initialize__(self, name, age, sex):
#     self.name = name
#     self.age = age
    # self.sex = sex  


#This is  wrong

# class def Person:
#   (self, name, age, sex):
#     self.name = name
#     self.age = age
#     self.sex = sex        

#This is  wrong

# class Person{
#   def __initialize__(self, name, age, sex):
#     self.name = name
#     self.age = age
#     self.sex = sex
# }      

# What will the following script print?
 

# def inc(a,b=1):
#     return(a+b)
# a=inc(1)
# a=inc(a,a)
# print(a)

# The answer is 4.

# You need to set the annual payment in one function and print the respective monthly payment in a separate function. How would you fix the suggested code to work properly?
 

# def SetAnnual():
#   annual=10000
# def PrintMonthly():
#   print("Your monthly payment is "+annual/12+" USD.")
# SetAnnual()
# PrintMonthly()


# annual=0
# def SetAnnual():
#   annual=10000
# def PrintMonthly():
#   print("Your monthly payment is "+annual/12+" USD.")
# SetAnnual()
# PrintMonthly()

# annual=0
# def SetAnnual():
#   annual=10000
# def PrintMonthly():
#   print("Your monthly payment is "+str(annual/12)+" USD.")
# SetAnnual()
# PrintMonthly()

# annual=0
# def SetAnnual():
#   global annual=10000
# def PrintMonthly():
#   print("Your monthly payment is "+annual/12+" USD.")
# SetAnnual()
# PrintMonthly()

# this is the answer:

# def SetAnnual():
#   global annual
#   annual=10000
# def PrintMonthly():
#   print("Your monthly payment is "+str(annual/12)+" USD.")
# SetAnnual()
# PrintMonthly()

# Which code snippet can you use to print the number of digits in the number variable? You can assume this number is always positive and always less than 10,000.


# if (a>=0):
#   print(1)
# elif (number>=10):
#   print(2)
# elif (number>=100):
#   print(3)
# else:
#   print(4)

# if (number<=10):
#   print(1)
# elif (number<=100):
#   print(2)
# elif (number<=1000):
#   print(3)
# else:
#   print(4)

# this is the answer

# if (number>=1000):
#   print(4)
# elif (number>=100):
#   print(3)
# elif (number>=10):
#   print(2)
# else:
#   print(1)

# if (number<10000):
#   print(4)
# elif (number<1000):
#   print(3)
# elif (number<10):
#   print(2)
# else:
#   print(1)


# Which alternative code is logically equivalent to the code below?
 

# max=x if (x>y) else y


# if (x>y):
#     max=y
# elif (x==y):
#     max=y
# else:
#     max=x

# if (x>=y):
#     max=x
# elif:
#     max=y

#This is the ansewer

# max=y
# if (x>y):
#     max=x

# if (y>x):
#     y
# else:
#     x

# Why is the code below often added to a Python program file?
 

# if __name__ == "__main__":
#   main()


# (This is the answer) It executes the main() function only if this file is executed as the main program.

# It assures that the program will run correctly when executed from either an IDE or command line.

# It confirms that it is an actual Python program before starting the interpreter.

# It allows us to skip calling the main() function by defining an environment variable.



# Which function will return the sum of the first item in the data list and every tenth item after?


# def Sum10th(data):
#   sum=0
#   for i,d in enumerate(data):
#     if (i % 10 != 0): sum=sum+d
#   return sum

# this is the answer

# def Sum10th(data):
#   sum=0
#   for i,d in enumerate(data):
#     if (i % 10 == 0): sum=sum+d
#   return sum

# def Sum10th(data):
#   sum=0
#   for i,d in enumerate(data):
#     if (i % 10 == 0): continue
#     sum=sum+d
#   return sum

# def Sum10th(data):
#   sum=0
#   for i,d in enumerate(data):
#     if (i % 10 == 0): return sum
#     sum=sum+d


# Example file for working with date information

# from datetime import date
# from datetime import time
# from datetime import datetime

# DTETIME OBJECTS
# Get today's date from the smaple toady() method from the date calss

# today = date.today()
# print("Today's date is ", today)

# # print out the date's individual compenents 
# print("Date compenets:", today.day, today.month, today.year)

# # retriev today's weekday (0=Monday, 6=Sunday)
# print("Today;s wweekday # is", today.weekday())
# days = ["mon", "tue", "wed", "thu", "fri", "sat", "sun"]
# print("Which is a:", days[today.weekday()])


# Get today's date from the datetime class
# today=datetime.now()
# print("The current date and time is", today)

# # Get the current time 
# t = datetime.time(datetime.now())
# print(t)

# Example for formating time and date output

# Time and dates can be formatted using a set of predefined string
# control codes

#now = datetime.now() 
# print(now.strftime("The current year is: %Y"))
# print(now.strftime("%a, %d, %B, %Y"))
# print(now.strftime("%a, %B, %d, %y"))
# print(now.strftime("%a,  %B %d, %Y"))

# Date Formatting

# %c - locale's date and time, %x - locale's date, %X - locale's time
# print(now.strftime("Local date and time: %c"))
# print(now.strftime("Local date: %x"))
# print(now.strftime("Local time: %X"))

# Time Formattng
# %I/%H - 12/24 Hour, %M - minute, %S - second, %p - locate's AM/PM
# print(now.strftime("Current time: %I:%M:%S %p"))
# print(now.strftime("24-hours time: %H:%M"))
# print(now.strftime("Local time: %X"))  

# Example file for working with timedelta objects
#from datetime import _date, timedelta

# construct a basic timedelta and print it
# print(timedelta(days=365, hours=5, minutes=1))

# # print today's date
# now = datetime.now()
# print("today is: " + str(now))

# # print today's date one year from now 
# print("one year from now will be: " + str(now + timedelta(days=365)))

# # create a timedelta that uses more than one argument
# print("In 2 days and 3 weeks, it will be " + 
# str(now +timedelta(days=2, weeks=3)))

# # calculate the date 1 week ago, formatted as string
# t1=datetime.now() - timedelta(weeks=1)
# s1=t1.strftime("%A %B %d, %Y")
# t2=datetime.now() - timedelta(days=5, weeks=1)
# s2=t2.strftime("%A %B %d, %Y")
# print("one week days ago it was: " + s1)
# print("one week and five days ago it was: " + s2)

# How many days untill April Fool's Day?
# today=date.today()
# afd=date(today.year, 4, 1)

# # use date comparsion to see if April Fool's has already gone for this year
# # if it has, us ethe rplace() function to get the date for next year
# if afd < today:
#       print("April Fool's day already went by %d days ago" % ((today-afd).days))
#       afd = afd.replace(year = today.year+1)

# # Now calculate the amount of time untile Aplril Fool's Day
# time_to_afd = afd-today
# print("It is just ", time_to_afd.days, "days until April Fool's Day")

 
 # How many days untill January 1, 2022?
# today=date.today()
# fj22=date(today.year, 1, 1)

# # use date comparsion to see if January 1, 2022 has already gone for this year
# if fj22 < today:
#       print("January 1, 2022 already went by %d days ago" % ((today-fj22).days))

# # if it has, use  the rplace() function to get the date for next year
# fj22 = fj22.replace(year = today.year+1)

# # Now calculate the amount of time untile Aplril Fool's Day
# time_to_fj22 = fj22-today
# print("It is just ", time_to_fj22.days, "days until January 1, 2022")

# Example file for working with calendars

# import the calendar module
#import calendar

# create a plan text calendar 
#c = calendar.TextCalendar(calendar.MONDAY)
# st = c.formatmonth(2021, 11, 0, 0)
# print(st)

# create an HTML formatted calendar 
# hc = calendar.HTMLCalendar(calendar.MONDAY)
# st = hc.formatmonth(2021, 12)
# print(st)

# loop over the days of month
# zeroes mean that the day of the week is in an overlapping month
# for i in c.itermonthdays(2021, 11):
#       print(i)

# The Calendar module provides useful utilities for the given locale,
# such as the names of days and months in both full and abbreviated forms
# for name in calendar.month_name:
#        print(name)

# for day in calendar.day_name:
#       print(day)

 # Calculate days based on a rule: For example, consider 
 # a team meeting on the first Friday of every month.
 # To figure out what days that would be for each month
 # we can use this script:
# print("Team meeting will be on: ")
# for m in range(1,13):
#     cal = calendar.monthcalendar(2022, m)
#     weekone= cal[0]
#     weektwo=cal[1]

#     if weekone[calendar.FRIDAY] !=0:
#             meetday= weekone[calendar.FRIDAY]
#     else:
#       meeday=weektwo[calendar.FRIDAY]
      
#       print("%10s %2d" % (calendar.month_name[m], meeday))

########################################################

# Chapter Quiz:

# Given that now=datetime.now(), which call may produce different results on different computers?

# print(now.strftime("%d"))
# Incorrect


# print(now.strftime("%Y"))

# print(now.strftime("%M"))
# print(now.strftime("%c"))
# Correct

# Question 2 of 5
# Which code will you use to generate a date and time output in the following format?
 

# 13-Mar-2020 16:42:58


# from datetime import date
# now=date.now()
# print(now.strftime("%B-%D-%Y %H:%M:%S"))

# from datetime import datetime
# now=datetime.now()
# print(now.strftime("%d-%b-%Y %h:%m:%S"))
# from datetime import datetime
# now=datetime.now()
# print(now.strftime("%d-%b-%Y %H:%M:%S"))
# Correct


# from datetime import datetime
# print(datetime("%d-%B-%Y %H:%m:%S"))

# Question 3 of 5
# What should come instead of the ??? placeholders for this code to correctly print the number of days until your birthday on Jun 30? Hint: the number of days in a timedelta object can be returned using its days attribute.
 

# today=date.today()
# bday=date(today.year,6,30)
# diff=???
# if diff>0:
#   print("Birthday in %d days" % diff)
# else:
#   print("Birthday in %d days" % (???))

# (bday-today).days; diff+365
# Correct


# (bday-today).days+365; diff

# bday-today; 365-diff

# bday.days-today.days; diff+365


# Question 4 of 5
# You create a simple calendar program that needs to print tomorrow's day of the week. Which code will work under all circumstances?

# today=date.today()
# days=["Sun","Mon","Tue","Wed","Thu","Fri","Sat"]
# print("Tomorrow will be "+days[(today.weekday()+1])
# Incorrect

# today=date.today()
# days=["Mon","Tue","Wed","Thu","Fri","Sat","Sun"]
# print("Tomorrow will be "+days[(today.weekday()+1)%7])
# Correct

# today=date.today()
# days=["Mon","Tue","Wed","Thu","Fri","Sat","Sun"]
# print("Tomorrow will be "+days[today.weekday()+1])
# Incorrect

# If today is Sunday, this code will fail because it will attempt to refer to a non-existing 8th item in the days[] array.


# today=date.today()
# days=["Sun","Mon","Tue","Wed","Thu","Fri","Sat"]
# print("Tomorrow will be "+days[(today.weekday()+1)/7])

# Question 5 of 5
# Which call will return the same result like date.today()?


# datetime(date.today())
# datetime.date(datetime.now())
# Correct


# datetime.time(datetime.now)

# datetime.date()

#############################################

# Chapter 4
# open a file for writing and create it if it doesn't exit
#f = open("textfile.txt", "w+")

# open the file for appending text to the end
# f = open("textfile.txt", "r")

# write some lines of data to the file 
# for i in range(10):
#   f.write("This is line" + str(i)+ "\r\n")

# close the file when done
#f.close

# open the file back up and read the contents
# if f.mode== 'r':
#       #contents = f.read()
#       fl =f.readlines()
#       for x in fl:
#         print(x)

      #print(contents)

#Example file for working with os.path module

#

# import os
# from os import get_blocking, path
# import datetime
# from datetime import date, time, timedelta
# import time
# import shutil
# from shutil import make_archive
# from zipfile import ZipFile

# Print the name of the OS
#print(os.name)

# Check for item existence and type 
# print("Item exists: " +str(path.exists("textfile.txt")))
# print("ITem is a file: " + str(path.isfile("textfile.txt")))
# print("Item is a directory: " + str(path.isdir("textfile.txt")))

# Work with file paths
# print("Item path: " + str(path.realpath("textfile.txt")))
# print("Item path and name: " +str(path.split(path.realpath("textfile.txt"))) )

# Get the modification time
# t = time.ctime(path.getmtime("textfile.txt"))
# print(t)
# print(datetime.datetime.fromtimestamp(path.getmtime("textfile.txt")))

# Calculate how long ago the item was modified
# td = datetime.datetime.now() - datetime.datetime.fromtimestamp(
#   path.getmtime("textfile.txt"))
# print("It has been " + str(td) + " since the file was modified")
# print("Or, " + str(td.total_seconds())+ " seconds")

#

# Example file for working with filesystem shell methods

# make a duplicate of an existing file
# if path.exists("textfile.txt"):
      
# # get the pathto the file in the current directory
#   src=path.realpath("textfile.txt")
# # Let's make a bakup copy by appending "bak" to the name
#   dst = src + ".bak"

# copy over the permissions, modification items, and other info
# shutil.copy(src, dst)
# shutil.copystat(src, dst)
#rename the original file
#os.rename("textfile.txt", "newfile.txt")

# now put things into a ZIP archive
# root_dir, tail = path.split(src)
# shutil.make_archive("archive", "zip")

# more fine-grained control over ZIP files
# with ZipFile("textzip.zip", "w") as newzip:
#   newzip.write("textfile.txt") 
#   newzip.write("textfile.txt.bak")

##################################
#Chapter 4:  Quiz
#Question 1 of 5
# You need to print the content of the "list.txt" file to the console. Which code can you use, assuming the file must already exist and must not be overwritten or created?


# f=open("read","list.txt")
# f.print()

# f=open("list.txt",'w+')
# f.read()

# f=open('r+',"list.txt")
# print(f.read())
# f=open("list.txt",'r')
# print(f.read())
# Correct

# Question 2 of 5
# While _____ checks whether a path exists, _____ checks whether a path is a file.


# path.exists(); path.realpath()

# path.exists(); path.isfile()

# path.isdir(); path.isfile()

# path.realpath(); path.exists()

# Question 2 of 5
# While _____ checks whether a path exists, _____ checks whether a path is a file.

# path.exists(); path.realpath()
# Incorrect

# path.exists(); path.isfile()
# Correct


# path.isdir(); path.isfile()

# path.realpath(); path.exists()


# Question 3 of 5
# How would you improve the code below?
 

# f = open("myfile.txt", "r")
# contents = f.read()


# Close the file handler using f.close() immediately after opening the file.

# Test that the file exists using f.write() before trying to read from it.

# Check that f.mode == True before calling f.read() to read from the file.
# Check that f.mode == 'r' before calling f.read() to read from the file.
# Correct


# Question 4 of 5
# Your program already imported the ZipFile module using from zipfile import ZipFile. How can you leverage this module to create a new zip archive and add a file to it?


# with ZipFile("archive.zip") as newzip:
#    newzip.add("file.txt")

# newzip=ZipFile.create("archive.zip","w")
# newzip.add("file.txt")
# with ZipFile("archive.zip","w") as newzip:
#    newzip.write("file.txt")
# Correct


# ZipFile.create("archive.zip",newzip)
# newzip.include("file.txt")

# Question 5 of 5
# What is the difference between shutil.copy() and shutil.copystat() functions?

# While shutil.copy() copies the file content, shutil.copystat() copies the file metadata.
# Correct


# While shutil.copy() copies the textual content, shutil.copystat() copies images and videos.

# While shutil.copy() copies the file in text mode, shutil.copystat() copies the file in binary mode.

# While shutil.copy() can copy the file to the same folder, shutil.copystat() can copy the file to any folder.


#########################

# Chapter 5:

# Example for retrieving data from the internet
#

#import urllib.request
# def main():
#   webUrl = urllib.request.urlopen("http://www.google.com")
#   print("result code: " + str(webUrl.getcode()))
#   data=webUrl.read()
#   print(data)

# if __name__ == "__main__":
#       main()

# print only events where at least 1 person repoerted 
# import json

# def printResults(data):
#    # use the json module to load the string data into a directory
#    theJSON = json.loads(data)

#    # now we can access the contens of the JOSN like any other Python object
#    if "title" in theJSON["metadata"]:
#       print(theJSON["metadata"]["title"])

#    # output the numberof events, plus the magnitude and each event nam
#    count =theJSON["metadata"]["count"]
#    print(str(count) + " events recorded")

#    # for each event, print the place where it occurred
#    for i in theJSON["features"]:
#          print(i["properties"]["place"])
  
#    print("------------\n")

#    # print the events that only have a magnitude greater than 4
#    for i in theJSON["features"]:
#       if i["properties"]["mag"] >= 4.0:
#        print("%2.1f" % i["properties"]["mag"], i["properties"]["place"])


#    print("------------\n")            

#    # print only the events where at least 1 person reported feeling something
#    print("Events that were felt:")
#    for i in theJSON["features"]:
#      feltReports = i["properties"]["felt"]
#      if feltReports !=None:
#        if feltReports > 0:
#          print("%2.1f" % i["properties"]["mag"], i["properties"]["place"],
#          "reported" + str(feltReports)+ "times")

      


# def main():    
#   # define  a variable to hold the source URL
#   # In this case we'll use the free feed from the USGS
#   # This feed lists all earthquakes for the last day larger than Mag 2.5
#   urlData = "https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/2.5_day.geojson"

#   # open the URL and read the data
#   webUrl = urllib.request.urlopen(urlData)
#   print("result code: " +str(webUrl.getcode())) 
#   if (webUrl.getcode() == 200):
#         data = webUrl.read()
#         printResults(data) 
#   else:
#     print("Received error, cannot parse results")

# if __name__ == "__main__":
#  main()

#

# Example file for parsing and precessing HTML

#
# from html.parser import HTMLParser
# class MyHTMLParser(HTMLParser):
#   def handle_comment(self, data):
#     print("Encountered comment: ", data)
#     pos = self.getpos()
#     print("\tAt line: ", pos[0], "position ", pos[1])
 
# def main():    
#   # instantiate the parser and feed it some HTML
#   parser = MyHTMLParser()
#   f = open("samplehtml.html")
#   if f.mode == 'r':
#     contents = f.read()
#     parser.feed(contents)


# if __name__ == "__main__":
#  main()


###################

# Chapter 5: Quiz 

# Question 2 of 8
# The following code, which is supposed to dump the google.com homepage HTML to the console, is missing a line at the ??? placeholder. What should this line be?
 

# import urllib.request
# webUrl = urllib.request.urlopen("http://www.google.com")
# ???
# print(results)


# results = webUrl.getCode()
# results = webUrl.read()
# Correct


# webUrl.request.read(results)

# webUrl.read(results)

# Question 3 of 8
# Given the XML below, how will you add a third item to the list that has a yellow color and a small size?
 

# <?xml version="1.0" encoding="UTF-8" ?>
# <catalog>
#   <item color="blue" size="large"/>
#   <item color="red" size="medium"/>
# </catalog>

# doc = xml.dom.minidom.parse("my.xml")
# newItem = doc.createElement("item")
# newItem.setAttribute("color", "yellow")
# newItem.setAttribute("size", "small")
# doc.firstChild.appendChild(newItem)
# Correct


# doc = xml.dom.minidom.parse("my.xml")
# attribute1 = doc.createAttribute("color", "yellow")
# attribute2 = doc.createAttribute("size", "small")
# element = doc.insertInElement("item",attribute1,attribute2)
# doc.firstChild.appendChild(element)
# doc = xml.dom.minidom.parse("my.xml")
# newItem = doc.createElement("item")
# newItem.setAttribute("color=yellow","size=small")
# doc.appendChild(newItem)
# Incorrect

# This code will incorrectly attempt to append the new item, not the catalog element, but to the top element.

# doc = xml.dom.minidom.parse("my.xml")
# firstChild = doc.firstChild()
# newItem = firstChild.createElement("item")
# newItem.setAttribute("color", "yellow")
# newItem.setAttribute("size", "small")
# Incorrect

# Question 4 of 8
# Given the following JSON data stored in a theJSON object, how can you list only the skill names?
 

# {
#     "name": "John",
#     "title": "Python Developer",
#     "skills": [{
#         "name": "coding",
#         "level": "expert"
#         },
#         {
#         "name": "documentation",
#         "level": "basic"
#     }]
# }

# for i in theJSON["skills"]:
#     print(i["name"])
# Correct


# print(theJSON["skills"]["name"])
# for i in theJSON:
#     print(i["skills"]["name"])
# Incorrect


# print(theJSON["skills"].theJSON["name"].theJSON["*"])

# Question 5 of 8
# What value should be returned by the URL request getcode() call to confirm that the specified site can be properly connected to?

# 200
# Correct


# 404

# null

# OK

# Question 6 of 8
# What class does Python provide to parse HTML?

# HTMLParser
# Correct


# ReadHTML

# HTMLReader

# HTMLTags

# Question 7 of 8
# The statement below fails when you try to run it. Which troubleshooting step is irrelevant for this scenario?
 

# doc = xml.dom.minidom.parse("myfile")

# Confirm that the file 'myfile' is first loaded to memory.
# Correct

# Confirm that the module 'xml.dom.minidom' is imported.
# Incorrect

# Confirm that the file 'myfile' contains valid XML.
# Incorrect


# Confirm that the file 'myfile' is in the local folder.


# Question 8 of 8
# For the HTML file below, how many times will the handle_starttag() and handle_endtag() methods of the Python-provided HTML parser class be called?
 

# <div class="sidebar">
#   <img src="pic.gif" height="50" width="100" />
#   <button type="button" id="btn-submit">Submit</button>
# </div>


# 3 and 2
# 2 and 2
# Incorrect


# 2 and 3
# 3 and 3
# Correct




