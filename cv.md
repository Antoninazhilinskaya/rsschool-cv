# **Antonina Zhilinskaya** #

## Junior Frontend Developer ##

## **Contact me** ##

## **Phone:** +375(29)595-99-54 ##
## **Email:** tonya_zhilinskaya@mail.ru ##
## **Social media:** inst: tonya_zh ##

## ** About me **##

## Currently I work as an accountant in an audit company in the outsourcing department. Work experience more than 2 years. I love math and numbers. But I realized that I want to work in a different field. And this is IT. I appreciate the specificity and accuracy in myself. Goal: retrain as soon as possible. ##   

## **Skills** ##

## I have basic knowledge of Python programming language, Django web framework (Python). ##

## ** Code Example ** ##

## 
from tkinter import *
import time
import random
tk = Tk()
tk.title('Bouncing ball')
tk.resizable(0, 0)
tk.wm_attributes('-topmost', 1)
canvas = Canvas(tk, width=800, height=500, highlightthickness=0)
canvas.pack()
tk.update()
class Ball:
    
    def __init__(self, canvas, paddle, score, color):
        self.canvas = canvas
        self.paddle = paddle
        self.score = score
        self.id = canvas.create_oval(100, 100, 25, 25, fill=color)
        self.canvas.move(self.id, 200, 100)
        starts = [-3, -2, -1, 1, 2, 3]
        random.shuffle(starts)
        self.x = starts[0]
        self.y = -2
        self.canvas_height = self.canvas.winfo_height()
        self.canvas_width = self.canvas.winfo_width()
        self.hit_bottom = False
##        

## ** Education ** ##

## * University: Belarusian State Economic University
   * Courses:
       * Web designer UX/UI
       * Python
##

## ** English ** ##

## A2 ( I'm looking forward to improving it in the future.) ##