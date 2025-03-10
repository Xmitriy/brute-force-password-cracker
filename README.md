CyanCoding's Brute Force Password Cracker

Welcome to CyanCoding's Brute Force Password Cracker! This program attempts to crack a password using a brute force method by trying every possible combination of lowercase letters, uppercase letters, and digits.

Features
Brute Force Method: It generates every possible combination of characters from the given alphabet (a-z, A-Z, 0-9) to guess the password.
Performance Tracking: The program tracks the number of attempts made and calculates the number of password attempts per second.
User Friendly: The program displays progress in real-time and shows the number of attempts made and the time taken to crack the password.
Usage
Clone or Download the Repository:

If you're using Git:
bash
Copy
Edit
git clone https://github.com/Xmitriy/brute-force-password-cracker.git
Or download the zip file and extract it.
Compile the Program:

If you have g++ installed, you can compile the program using the following command:
bash
Copy
Edit
g++ -o cracker cracker.cpp
Run the Program:

After compilation, run the program with the following command:
bash
Copy
Edit
./cracker
Enter your password:

The program will ask you to enter a password. After you enter the password, it will attempt to crack it.
Example
Input:
bash
Copy
Edit
Welcome to CyanCoding's Brute Force Password Cracker!

What do you want your password to be? > aB12
Output:
bash
Copy
Edit
Attempting to crack aB12...

CyanCoding's C++ BFPC cracked the password "aB12" in 12345678 attempts and 3.21 seconds.
That's about 1234567 passwords per second!
Requirements
C++ Compiler: Any compiler supporting C++ (e.g., g++, clang++)
Operating System: Works on any system supporting C++ (e.g., Linux, macOS, Windows)
Code Explanation
Key Components:
Alphabet[62]: An array containing all possible characters for the brute force attempt (lowercase letters, uppercase letters, and digits).
separateWithCommas(long long num): A helper function to format large numbers with commas for easier readability.
crack(unsigned int length, string current): The main brute force function that generates all combinations of characters recursively.
stop: A flag used to stop the brute force process once the correct password is found.
Flow of Execution:
User Input: The user provides the password that the program will attempt to crack.
Password Cracking: The program starts generating all possible combinations of characters and checks them against the entered password.
Progress Display: It displays the number of attempts made and updates the attempts per second in real time.
Completion: Once the password is cracked, the program shows the total time taken and the number of attempts.
License
This project is open-source and available under the MIT License.

![Image Alt Text](https://images6.alphacoders.com/975/975644.jpg)
