# I have discovered this is called counting sort and it already exists. I am keeping it up still just keep that in mind

# HashSort
A fast sorting algorithm using 'hash tables'
(also sorry I will not accept any changes because I am using this as a public portfolio.
If you wanna make this better than please just create a new repository with your improved code
. It would also be extra nice if you could link back to this repository
(also if there is a way that github does this like on the website normally please tell me so
that I can make this easier for everybody.)
also do feel free to use this algorithm if you want to in code and if it played a large role in
the project then it would be nice to reference me somewhere)

First thing I want to mention is that I have not done toooo much research into this so idk if I 
came up with this or not please tell me if I did not.

# How it works

This sorting algorithm works by using the inherit value that 1 < 4 rather than explicitly stating this in the code.
IT does this by using an array and using the value of the input number as an index to add to the array. (sorta like hashing
except no hash function). If you do this then the numbers get like sorted because they have been placed in order by
their index in the array. (sorry for the bad explanation). In order to make this more useable you have to convert this array
into a list of numbers which is just done by iterating through the array and using the index to add to the return list 
while adding as many numbers as much as the number is at that index

Time efficeny for sorting is O(n) (also im not that great at big o notation so please tell me if this is wrong)
(This is not taking in to account converting the 'hash table' back into a readable format, if you do it is O(2n) time efficient
which I think might end up just being O(n) but then again I do not know big o notation all that well)

# Cons
(I kept thinking about where to add these and nowhere really fit so i put them here)
This is not a very space efficient algorithm, needing an array the size of the largest number possible which might end up 
being like 10000000000000000000000000000000000000 or whatever. 

This is not a very general algorithm. If you want to sort other things other than numbers and maybe letters (maybe make a custom 
array type) it doesn't work. You also have to know the max or add an extra loop through the array to find the max. You could 
maybe improve it by making the array into an arrayList and making it dynamic but that would make the algorithm less efficient so
it kinda defeats the purpose of this whole algorithm. 

(there is something else here i forgot about while writing it so if you find it can you please tell me somehow)
