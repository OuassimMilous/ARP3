all: master server UI keyboard drone watchdog
clean-logs:
	rm log/logfile.txt
	touch log/logfile.txt
clean:
	rm build/*
master:

	gcc master.c -o build/master 

server:
	gcc server.c -o build/server

UI:
	gcc UI.c -o build/UI  -lncurses -lm

keyboard:
	gcc keyboard.c -o build/keyboard -lncurses

drone:
	gcc drone.c -o build/drone -lm

watchdog:
	gcc watchdog.c -o build/watchdog -lncurses


