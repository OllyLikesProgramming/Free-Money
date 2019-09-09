# Free-Money
from tkinter import *
import datetime
t = datetime.time
datetime.datetime.now().time()
datetime.time(15, 8)


x = input ("What is your name?")

now = datetime.datetime.now()
today8am = now.replace(hour=8, minute=0, second=0, microsecond=0)
#if now < today8am:
    #print ("Good Moring!")
#if now > today8am:
   # print ("Good Afternoon!")


today6am = now.replace(hour=6, minute=0, second=0, microsecond=0)
#if now < today6am:
  #  print ("Evening!")
#if now > today6am:
  #  print ("Morning!")

now = datetime.datetime.now()
today10pm = now.replace(hour=22, minute=0, second=0, microsecond=0)
#if now < today10pm:
 #   print ("Good Afternoon!")
#if now > today10pm:
  #  print ("Good evening!")

today12pm = now.replace(hour=12, minute=0, second=0, microsecond=0)
#if now < today12pm:
  #  print ("Good Morning!")
#if now > today12pm:
  #  print ("Good Afternoon!")
    
today8pm = now.replace(hour=20, minute=0, second=0, microsecond=0)
#if now < today8pm:
 #   print ("Good Afternoon!")
#if now > today8pm:
   # print ("Good Evening!")
    
today6pm = now.replace(hour=18, minute=0, second=0, microsecond=0)
#if now < today6pm:
  #  print ("Good Afternoon!")
#if now > today6pm:
   # print ("Good Night!")
    
today0pm = now.replace(hour=0, minute=0, second=0, microsecond=0)


today12am = now.replace(hour=23, minute=59, second=59, microsecond=0)

today9pm = now.replace(hour=21, minute=0, second=0, microsecond=0)


if now > today6am and now < today12pm:
    print ("Hello " + x + " Good morning!")
    
if now > today12pm and now < today6pm:
    print ("Hello " + x + " Good Afternoon!")

if now > today6pm and now < today9pm:
    print ("Hello " + x + " Good Evening!")
    
if now > today9pm and now < today12am:
    print ("Hello " + x + " Good Night!")
    
if now > today0pm and now < today6am:
    print ("Hello " + x + " Good Night!")
