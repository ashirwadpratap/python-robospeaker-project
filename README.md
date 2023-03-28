# python-robospeaker-project
This is python robospeaker project in which what you want to hear you can type
import os



if __name__ == '__main__':
   print("welcome to Robospeaker 2.0 created by Ashirwad ") #first it welcomes you
while True:

   x= input("input") #you can hear anything by entering your word
   if x == "q":
      os.system("hello 'bye bye friend'")
       
   command=f"say {x}"
   os.system(command)

