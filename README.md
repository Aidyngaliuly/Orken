# Orken
student of SDU
from tkinter import *


class Main(Frame):
    def __init__(root, self):
        super(Main, self).__init__(root)
        self.build()

    def build(self):
        pass
 
    def logicalc(operation, self):
        pass

    def update():
       pass


if __name__ == '__main__':
    root = Tk()
    root["bg"] = "#000"
    root.geometry("550x480+200+200")
    root.title("Калькулятор")
    root.resizable(False, False)
    app = Main(root)
    app.pack()
    root.mainloop()
