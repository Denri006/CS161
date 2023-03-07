all: mm blockmm blockmm_transpose

mm: mm.c
	gcc -g0 mm.c -o mm 

blockmm: blockmm.c 
	gcc -O0 blockmm.c -o blockmm 

blockmm_transpose: blockmm_transpose.c 
	gcc -g3 blockmm_transpose.c -o blockmm_transpose

clean:
		rm -f blockmm mm blockmm_transpose
