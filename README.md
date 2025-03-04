# fLock

## fLock is a simple command-line executable that encrypts and decrypts directories and subdirectories from the chosen dir

## Usage:
### flock < IV > < KEY > < encrypt|decrypt > < dir >

## Iv & Key:
### DON'T use white spaces and special characters for the IV and KEY
### IV must be 16 characters long
### KEY must be 32 characters long
### fLock must be executed with administrator privileges

## Example (let's assume you have included fLock to the system variables) 
### flock aaaaaaaaaaaaaaaa bbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbb encrypt C:\Users\user\Desktop
### flock aaaaaaaaaaaaaaaa bbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbb decrypt C:\Users\user\Desktop
