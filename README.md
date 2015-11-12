wallswag
CODE
--variables
Z = 14
z = 12
X = 28
x = 27
Y = 4

for n = 1, Y do --makes it reapeat four times

  turtle.up()   -- turtle moves forward

  for n = 1, Z do  --reapets Z amount of times
  
    ItemPick()     -- chooses slot
    turtle.placeDown()   --places block
    turtle.forward()    -- moves forward
   
  end
  
  turtle.turnRight()
  turtle.turnRight()
  turtle.forward()
  turtle.turnLeft()
  turtle.forward()
  
  for n = 1, X do
  
    ItemPick()
    turtle.placeDown()
    turtle.forward()
    
   end
   
   ItemPick()
   turtle.placeDown()
   turtle.turnRight()
   turtle.forward()
   
  for n = 1, z do
  
    ItemPick()
    turtle.placeDown()
    turtle.forward()
   
  end
  
   ItemPick()
   turtle.placeDown()
   turtle.turnRight()
   turtle.forward()
   
  for n = 1, x do
  
    ItemPick()
    turtle.placeDown()
    turtle.forward()
    
  end
  
  ItemPick()
  turtle.placeDown()
  turtle.turnRight()
  
end
VISUAL
ComputerCraftEdu:repeat
ComputerCraftEdu:number 1
ComputerCraftEdu:do

ComputerCraftEdu:moveForward

ComputerCraftEdu:end
