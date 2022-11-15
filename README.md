# Orken
student of SDU
from tkinter import *


class Main(Frame):
    def __init__(root, self):
        super(Main, self).__init__(root)
        self.build()

    def build(self):
        pass
 
    def logicalc( self,operation ):
        pass

    def update():
       pass


if __name__ == '__main__':
    root = Tk()
    root["bg"] = "#000"
    root.geometry("14x48+20+100")
    root.title("Калькулятор")
    root.resizable(False, False)
    app = Main(root)
    app.pack()
    root.mainloop()
