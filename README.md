# Dynamic & Static link library in C

===========================================================================
sudo apt install gedit
sudo apt install gcc

gcc example-01.c -static -no-pie -lm -o example-01
gedit example-01

gcc example-01.c -static -no-pie -lm -o example-01
file example-01

readelf -a example-01 | grep shared
readelf -a example-01 | grep interpreter 

objdump -D example-01 > example-01.dump
objdump -d example-01 > example-01.dump


gedit example-D.dump
gedit example-d.dump


==============================================================================
