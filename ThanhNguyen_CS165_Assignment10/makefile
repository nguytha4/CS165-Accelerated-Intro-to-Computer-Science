
all: store

store: storeMain.o Store.o Customer.o Product.o
	g++ storeMain.o Store.o Customer.o Product.o -o store
	
storeMain.o: storeMain.cpp
	g++ -c storeMain.cpp

Store.o: Store.cpp Store.hpp
	g++ -c Store.cpp
	
Customer.o: Customer.cpp Customer.hpp
	g++ -c Customer.cpp
	
Product.o: Product.cpp Product.hpp
	g++ -c Product.cpp
	
clean:
	rm -f *.o