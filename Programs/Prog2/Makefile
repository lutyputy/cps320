webserver: webserver.c eznet.o httpv.o utils.o
	gcc -g webserver.c eznet.o httpv.o utils.o -lbsd -owebserver

eznet.o : eznet.c eznet.h
	gcc -c eznet.c

httpv.o : httpv.c httpv.h
	gcc -c httpv.c

utils.o : utils.c utils.h
	gcc -c utils.c

clean :
	-rm *.o



# 	webserver: webserver.c eznet.o httpv.o utils.o
# 	gcc -g -fsanitize=address -fno-omit-frame-pointer webserver.c eznet.o httpv.o utils.o -lbsd -owebserver

# eznet.o : eznet.c eznet.h
# 	gcc -c eznet.c

# httpv.o : httpv.c httpv.h
# 	gcc -c httpv.c

# utils.o : utils.c utils.h
# 	gcc -c utils.c

# clean :
# 	-rm *.o