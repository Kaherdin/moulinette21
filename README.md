# 42. Year 42/2. CH : WITHOUT ANY GUARANTEE

## Tested : C00, C01, C02 & C03
## Todo : C04......

A tool for quickly test solutions for the C piscine exercises.
Based on https://github.com/mirror12k/42us-stupidity.git 


## Usage
 
1. Clone moulinette21
2. Go inside moulinette21
3. Clone a day's repo inside moulinette21
4. Run `./spawn.pl <c_repo> config_<c_repo>.pl`<br>
    Replacing the placeholders! This will create the test files for all the exercises.
5. Run `./tools/build.sh`<br>
  Build the exercies' files with the provided main.c's.
6. Run `./tools/verify.sh`<br>
  This makes norminette verify all the files. (Only works from the iMacs in the labs.)
7. Run `./tools/check_all.sh`<br>
  This will perform every test. If tests pass then they will say `good` otherwise errors are printed on the terminal.
  
## Example workflow

```
$ git clone https://github.com/mirror12k/42us-stupidity.git Moulinette
$ cd Moulinette
$ cp ~/Desktop/c01 c01
$ ./spawn.pl c01 config_c01.pl
$ ./tools/build.sh
$ ./tools/verify.sh
$ ./tools/check_all.sh
```
