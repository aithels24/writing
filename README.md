# writing
def writingto():
    
    file2 = open('greeting.txt', 'w') #Creates a file and opens it for edit
    
    print("Opening greeting file")
    
    file2.write("Hello\n") #line in the file
    file2.write("How are you\n")#\n creates a new line
    
    file2.write("My name is Ai, ") #singluar line withput \n
    file2.write("I am in grade 12")
    
    file2.close()
    print("File close")
    
