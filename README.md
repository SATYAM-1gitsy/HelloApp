# HelloApp

HelloApp is a simple Java project used to demonstrate progressive development of a console application.

The project begins with a simple "Hello World" program and gradually adds features such as displaying user names, accepting command line inputs, managing collections of names, and persisting data.

## Project Structure

src/  → Java source code  
bin/  → Compiled binaries  
docs/ → Use case documentation

## Running the Application

Compile:

mvn clean compile

Run:

mvn exec:java -Dexec.mainClass="HelloApp"
