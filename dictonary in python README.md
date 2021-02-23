# build-a-dictonary-in-python-
mydict={
    "watchdog":'''this game is of 20 gb download size 
    requried:25 gb hard disk storage and 8 gb ram windows/7/8/10 64.bit''',
    "watchdog2":'''this game is of 21 gb download size 
    requried:28 gb hard disk storage and 8 gb ram windows/7/8/10 64.bit''',
    "gta5":'''this game is of 45 gb download size 
    requried:65 gb hard disk storage and 8 gb ram windows/7/8/10 64.bit''',
    "hitman":'''this game is of 19 gb download size 
    requried:23 gb hard disk storage and 8 gb ram windows/7/8/10 64.bit''',
    "hitman2":'''this game is of 22 gb download size 
    requried:27 gb hard disk storage and 8 gb ram windows/7/8/10 64.bit''',
    "sanandreas":'''this game is of 1 gb download size 
    requried:4 gb hard disk storage and 8 gb ram windows/7/8/10 32.bit'''

}
a=print("the options are",mydict.keys())
b=input("enter your Game \n " )
print("game requierment to download is \n" ,mydict.get(b))

