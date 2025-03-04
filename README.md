<p align="center">![alt text](https://github.com/aliasexo/fLock/blob/main/fLock.png?raw=true)</p>
# fLock is a simple command-line executable that encrypts and decrypts directories and subdirectories from the chosen dir

## Usage
flock IV KEY encrypt|decrypt dir

## Iv & Key
**don't** use white spaces and special characters for the IV and KEY

IV must be 16 characters long

KEY must be 32 characters long

fLock must be executed with administrator privileges

## Example 
flock aasimple16chariv asimple32charkeyasimple32charkey encrypt DIRPATH

flock aasimple16chariv asimple32charkeyasimple32charkey decrypt DIRPATH
