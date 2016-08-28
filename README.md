# lua

--[INTRODUCTION]--
Made this 'tutorial' or so to speak on ROBLOX when I used to play, I just retreived my account information and saw this, so I just decided to upload it to GitHub. Enjoy!

--[PROPERTIES]--

-- Anchored: If this setting is set to true, the part will not fall, if it is false, it will fall.

script.Parent.Anchored = true

-- Transparency: This makes the brick invisible, the higher the number, the more invisible. The max is 1, so you can use decimals.

script.Parent.Transparency = 0.9

-- Reflectancy: This will make the sky reflect off of the brick that has this applied onto it.

script.Parent.Reflectance = 1

-- BrickColor: This is obivious, it changes the brick color!

script.Parent.BrickColor = BrickColor.new("Bright red")

-- Material: This will change the material type to whatever you have typed into the string.

script.Parent.Material = "DiamondPlate"

-- Size: Welcome to the Vector3 value world! Size requires a Vector3 in order for it to work.

script.Parent.Size = Vector3.new(3,3,3)

-- Name: This will well, change the name obviously!

script.Parent.Name = "MyPart" 

--[Name Help]--

game.Workspace.MyPart.Transparency = 0.5 -- <-- Call the part by it's new name or the string wont work!

-- NOTE: 0,0,0 are the y,x, and z axis! The first zero is the x axis, the second is the y axis, and the third zero is the z axis!

-- NOTE2: Keep all axis values UNDER 360 degrees! Or the brick will just stay in the same position!


-- Position: Position, and all of that stuff requires a Vector3, so don't do: script.Parent.Position = 9,8,2
-- This is what you do to change the position of the brick:

script.Parent.Position = Vector3.new(0,0,0) -- Now, if you did not know, you can also do minus values like script.Parent.Position = Vector3.new(9,-12,0)

-- Rotation: Rotation is exactly the same thing as position, except you remove position for Rotation.

script.Parent.Rotation = Vector3.new(0,0,0)

-- Velocity: Again, Velocity uses the Vector3 value. Replace Position/Rotation with Velocity.

-- If you don't know what velocity is, it is simple. Velocity is like a current of water.

-- It makes things move. So, drop a brick on the part that has the velocity value, and watch it move!
script.Parent.Velocity = Vector3.new(0,0,0)

-- RotVelocity: RotVelcoity makes the brick rotate, and move at the same time. Basically a spiral! Great if your building a airport and you need bricks for the lugage circle things!

script.Parent.RotVelocity = Vector3.new(0,0,0)

-- CanCollide: CanCollide is how you make walkthrough bricks! If it is set to true, you cant walkthrough it, if it is set to false, you can.

script.Parent.CanCollide = true

script.Parent.CanCollide = false

-- Archivable: If this is set to true, you can save it, and copy it. If it is set to false, you CANNOT save it, or copy it.

script.Parent.Archivable = false

script.Parent.Archivable = true

-- Locked: If the part is locked, you cannot move it, or select it. If it is un-locked, you can move it, and select it.

script.Parent.Locked = false

script.Parent.Locked = true

-- Elasticity: Elasticity means how bouncy the object is (Now you can create a trampoline! Yayy!)

script.Parent.Elasticity = 4

-- FormFactor: FormFactor basically is how thick, and thin the part is

-- There are currently only 4 forms you can choose from, here are all 4:

script.Parent.FormFactor = "Brick"

script.Parent.FormFactor = "Custom"

script.Parent.FormFactor = "Plate"

script.Parent.FormFactor = "Symmetric"

-- NOTE: If you choose symmetric, it will not allow you to enter decimal numbers, they have to be whole numbers!

-- Friction: If you make the friction a bigger number, it will be harder for a falling object to fall off the part that has a big ammount of friction.

script.Parent.Friction = 2

-- Surface Inputs: These all have something to do with motors. By changing the values of those inputs, it would make the motor go faster, or slower.

-- NOTE: I am ONLY showing you guys 2 as there are too many for me to list.

script.Parent.TopParamA = 0.7

script.Parent.TopParamB = 6

-- Surface: Surface will change the faces of your part to your desired style.

-- NOTE: I am only showing 2 cause #yolosweg :3

script.Parent.TopSurface = "Smooth"

script.Parent.BottomSurface = "Smooth"

--[PRINTING]--

print 'Hello World!'

-- You can also print numbers like so:

print (708)

-- This command makes the computer print Hello World!

-- Another good function is the wait function.

print (5)

wait (3)

print ("I like turtles")

-- The computer prints the number 5, waits 3 seconds, and then prints I like turtles.

--[VARIABLES]--

myVariable = 10

print (myVariable)

-- myVariable has a value of 10 now. Its the samething as doing this: print (10) except we stored 10 inside of myVariable.

-- Alright, so that was just an example of a integer value. A integer value is a whole number only (No decimals!!).

-- There are 5 datatypes of variable values, String, Integer, boolian (bool), object datatype (I will be showing this further on), and the decimal datatype.

-- Fact: Boolian datatypes can only hold 2 values, true, or false.

-- I am now going to show you a example of a string datatype.

myVariable2 = "iAnhilated"

print (myVariable2)

myVariable3 = 8545.8

print (myVariable3)

-- You know how you put variables in a single script, and it will ONLY work for that script? (Local Variable). Well, a IntValue item is a global variable so it will work in ANY script.

-- But, you have to access it a different way:

game.Workspace.MyPart.myVariable4.Value = 50

print (game.Workspace.MyPart.myVariable4.Value)

-- A number value, can be any number, a string value can be any text, a IntValue can be any WHOLE number, and a boolian value can be true or false.

game.Workspace.MyPart.myVariable5.Value = true

print (game.Workspace.MyPart.myVariable5.Value)

--[BASIC MATH]--

 it, so here is the proper way of entering a sum:
 
-- Remember the print command? That comes in use here:

print (5 + 4)

-- It should print out the number 9.

-- Remember variables? Well, you can store questions in them aswell!

myVariable6 = 5 + 9

print (myVariable6)

-- This should print out the number 14.

-- Now, you can also do subtraction, multiplication, or division.

myVariable7 = 5 - 3

print (myVariable7)

-- This should become 2.

-- Multiplication and division are different symbols. For multiplication you would use the star (SHIFT + 8). For division, you would use forward slash (/).

myVariable8 = 10 / 2

print (myVariable8)

-- 10 divided by 2 = 5.

myVariable9 = 10 * 2

print (myVariable9)

-- 10 multiplied by 2 = 20.

-- You can also use variable to print a script for math:

myVariable10 = 0.25 + 0.25

game.Workspace.MyPart.Transparency = myVariable10

-- This will make the part transparent 0.5%.

xValue = 10

yValue = 20

zValue = 15

game.Workspace.MyPart.Size = Vector3.new(xValue, yValue, zValue)

-- But, instead of doing that, why not make the computer think? Now, how do you make it think.... Aha! Math!

xValue2 = 5 + 5

yValue2 = 10 + 10

zValue = 7.5 + 7.5

game.Workspace.MyPart.Size = Vector3.new(xValue2, yValue2, zValue2)

-- Now, what you can also do is add a variable to a variable, here is an example:

myVariable11 = 50

myVariable11 = myVariable11 + 30

print (myVariable11)

--[FUNCTIONS]--

function example1()

	end
	
function example2()

	print ("Hi")
end

example2()

function giveSword()

end

giveSword()

--[RETURNING]--

function Returning1()

	print ("Hey!")
	
	return 10
end

print (Returning1())

--So the function prints Hey!, and then it will return 10. So it prints 10. You can also return a string.
	
function Returning2()

	print ("Hey!")
	
	return "MyString"
end

print (Returning2())

-- So, you dont always have to print the function, you can set it to a variable, if that makes sense.

myVariable12 = 5

function Returning3()

	print ("Hey!")
	
	return 100
end

print (myVariable12)

myVariable12 = Returning3()

-- What we are doing is simple. We are just substituting the number 100 for hello().

print (myVariable12)

--[PARAMETERS/ARGUEMENTS]--

function Parameters()

print ("hi")	
	
end

Parameters()

function hello(var1)

	print(var1)
end

hello()

function hi(hii)

	print (hii)
end

hi(5)

-- END OF CODE, THANK YOU FOR VIEWING.
