#Elsayed tamer darwesh#
from tkinter import *
root = Tk()
mybutton = Button(root, text="my button", fg="black", 
bg="pink").pack()
mylabel = Label(root, text="my label")
mylabel.pack()
mylabel.config(bg="red")
myentry = Entry(root, width=20).pack()
mytext = Text(root, width=20, height=10).pack()
mygroup = StringVar()
myoption1 = Radiobutton(root, text="check me1", variable=mygroup, 
value="check1").pack()
myoption2 = Radiobutton(root, text="check me2", variable=mygroup, 
value="check2").pack()
mycheckbox = Checkbutton(root, text="check me").pack()
root.mainloop()
