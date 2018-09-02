# linear-algebra-python
def plus(self,v):
    new_coordinates=[x+y for x,y in zip(self.coordiantes,v.coordinates)]
    #new_coordinates=[]
    #n=len(self.coordiantes)
    #for i in range():
    #    new_coordinates.append(self.coordinates[i]+v.coornates[i])
    return Vector(new_coordinates)
    
def minus(self,v):
    new_coordinates=[x-y for x,y in zip(self.coordiantes,v.coordiantes)]
    return Vector(new_coordinates)
    
def times_sca;ar(self,c):
    new_coordinates=[c*x for x in self.coordinates]
    return Vector(new_coordinates)
    
def __str__(self):
    return 'Vector:{}.format(self.coordinates)
    
def __eq__(self,v):
    return self.coordinates==.coordinates
    
v=Vector([8.218,-9.341])
w=Vector([-1.129,2.111])
print V.plus(w)

v=Vector([7.119,8.215])
w=Vector([-8.223,0.878])
print V.minus(w)

v=Vector([1.671,-1.-1.012,-0.318])
c=7.41
print V.times_scalar(c)

