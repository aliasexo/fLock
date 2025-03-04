<p align="center">
  <img src="https://github.com/aliasexo/fLock/blob/main/fLock.png?raw=true" alt="alt text">
</p>

<h1 align="center">fLock is a simple command-line executable that encrypt and decrypt directories and subdirectories from the chosen dir</h1>

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
