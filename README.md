# Objects-in-glowscript
GlowScript 2.7 VPython # program with some useful objects  ball = sphere(pos=vector(5,0,0), # position of sphere's center (x,y,z)      radius=0.5, # radius of sphere     color=color.green, # color of sphere     make_trail=True) # leaves trial, if object moves      parr = arrow(pos=vector(3,3,3), # tail or start of vector     axis=vector(6,6,6), # tip or end of vector     color=color.orange) # color of vector  particle=box(pos=vector(0,0,0), # position of box's center (x,y,z)     size=vector(2,2,2), # size of box (x length, y length, z length)     color=color.red, # color of box     opacity=0.4) # transparency of box, 1 solid, 0 see through      some=cylinder(color=color.cyan, # color of cylinder     pos=vector(0,-3,0), # start of cylinder     axis=vector(10,0,0), # length of cylinder      radius=0.3) # radius of cylinder
