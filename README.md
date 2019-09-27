# pack-and-show1
from tkinter import *
from tkinter import ttk

pos = Tk()

pos.geometry('600x400')
lbl = ttk.Label(pos,text = 'how are you my frande',font = 'tahoma 22')

def hide():
    lbl.pack_forget()
def show():

    lbl.pack()
Button(pos,text = 'ybyno',font = 'tahoma 22',command = show).pack()

Button(pos,text = 'y5fih',font = 'tahoma 22',command = hide).pack()

    
lbl.pack()
pos.mainloop()
