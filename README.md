# flet_simple_interest_calculator
I built a simple interest calculator using the FLET library.

# GUI Development with FLET
# Python has a lot of libraries/packages. E.g numpy, beautifulsoup, pandas, FLET.
# FLET is a python library for creating high-quality and real time mobile web and desktop flutter apps.
# FLET uses flutter material design UI to make it easy to design beautiful and professional looking user interface.

# To install FLET, we use the Pip dependency.
pip install flet - !pip install flet

# This is to show your first page.
import flet
from flet import Page, Text, colors
def main(page: Page):
page.title = "Our first Project"
page.add(Text("Hello, World!", size=20, 
weight="bold",color=colors.BLUE_400))
    
flet.app(target=main)

# How to build a simple interest calculator with FLET
# First step:
Create your calculate.py module.
calculate.py module
Simple Interest in Python
Enter Amount
def simple_interest(p,r,t):
SI = (p*r*t)
return SI

#print(simple_interest(1000,4,4)) - Test if the function works.

# Second step:
Create your simple_interest module.
Simple_interest.py module 
