# date of birth
 # LUBOWA KENNETH
#REGISTRATION NUMBER:16/6622/PS
#STUDENT NUMBER:216002992
print '-' * 12
print "  Mar = 1" 
print "  Apr = 2" 
print "  May = 3"
print "  Jun = 4"
print "  July = 5"
print "  Aug = 6" 
print "  Sept = 7" 
print "  Oct = 8" 
print "  Nov = 9"
print "  Dec = 10" 
print "  Jan= 11" 
print "  Feb = 12"
print '-' * 12
print " "

defday_of_week():
    month = ["Jan", "Feb", "Mar", "Apr", "May", "Jun", "July", "Aug", "Sept",
	     "Oct", "Nov", "Dec"]

day = ["Sun", "Mon", "Tue", "Wed", "Thur", "Fri", "Sat", "Sun"]

    b = int(raw_input("Enter NUMBER for Month of the Year: "))
print "Month : ", month[b - 1] 
print " "

    c = int(raw_input("Enter day of the month : "))
print "Day : ", c
print " "

    d = int(raw_input("Enter year : "))
print "Year : ", d
print " "
if b == 11 or b == 12:
        d = d - 1 
else: 
        d = d       

    k = int(raw_input("Enter the century : "))
print "Century : ", k 
print " "

    w = (13 * b - 1) / 5 
    x = d / 4 
    y = e / 4 
    z = w + x + y + c + d - 2 * k 
    r = z % 7

print "  ", month[b - 1], str(c) + ",", str(k) + str(d),"was: ", day[r],"!!"
print " "

day_of_week()
