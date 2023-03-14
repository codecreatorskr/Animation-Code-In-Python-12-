# Animation-Code-In-Python-12-


  
   	 import turtle as t
  	 import time

	   t.speed(0)
	   t.bgcolor('black')
	   t.pencolor('red')
	   time.sleep(3)
	   for i in range(160):
		   t.right(i)
		   t.circle(125,i)
		   t.forward(i)
		   t.right(90)

	   t.done()
