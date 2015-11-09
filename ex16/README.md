# Exercise 16: Structs And Pointers To Them

## How to break it

### Try passing NULL to Person_destroy to see what it does. If it doesn't abort then you must not have the -g option in your Makefile's CFLAGS. 

```
jharvard@appliance (~/git-repos/LCTHW-BOOK/ex16): ./ex16
Joe is at memory location 0x90af008:
Name: Joe Alex
	Age: 32
	Height: 64
	Weight: 150
Frank is at memory location 0x90af020:
Name: Frank Blank
	Age: 20
	Height: 72
	Weight: 180
Name: Joe Alex
	Age: 52
	Height: 62
	Weight: 190
Name: Frank Blank
	Age: 60
	Height: 72
	Weight: 180
Name: Harrison Appiah
	Age: 21
	Height: 23
	Weight: 40
Segmentation fault (core dumped)
```
