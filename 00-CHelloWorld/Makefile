#nombre del ejecutable 
TARGET = hello

#crea el archivo hello solo si hello.c existe
$(TARGET): hello.c
	gcc hello.c -o $(TARGET)  

# Ejecuta y guarda el resultado en el txt,y tambien lo muestra con cat
run: $(TARGET)
	./$(TARGET) > output.txt
	cat output.txt

#limpia, borra el archivo hello y output.txt
clean:
	rm -f $(TARGET) output.txt