# Create-your-Blockchain-
I created a simple demo blockchain with the help of python.
How to create own blockchain in python 
We import hashlib library (for hash generation) which provide sha256 to us.
Make function for hash generation which is hashGenerator. Which convert data into 64 hexadecimal.
We declare one variable Result in which we fetch sha256 using hashlib & encode our data.
Then return result in hexadecimal by using hexadigest bcz SHA256 don’t give result in hexadecimal form.
Declare another class Blockchain in which defining __init__ function in which we declare hashlast variable for generation of previous hash then hashStart variable for generation of new hash of current block.
Then genesis variable in which assign block in which data of block is Sahil shaikh is blockchain developer.
To make it part of chain we use self.chain & make it part of list (array)   
Then we define add function then prev_hash variable then assign value self.chain[-1].hash to access genesis block hash by using list variable.
Then hash variable to create hash of current block by using hashGenerator by assigning data & previous hash of block for unique hash.
Then convert into dictionary.
First we use Class to create Block , defining init function
