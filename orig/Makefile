FC= ifort
OBJS= sub.f90  param.f90  main.f90

build:  
	$(FC) -o fastslow $(OBJS) 

#.SUFFIXS : .f90

clean:
	rm -f *.o *.mod fastslow
run:
	cp ../topo.dat ./
	./fastslow 
