######## Client initializations ########
Client_App_Name := ClientApp
Client_Cpp_Flags := -std=c++11
Client_Cpp_Files := $(wildcard ./*.cpp)
Client_Link_Flags := -lcryptopp

######## Client Objects ########
ClientApp: $(Client_Cpp_Files)
	$(CXX) $(Client_Cpp_Flags) -o $(Client_App_Name) $(Client_Cpp_Files) $(Client_Link_Flags)

.PHONY: clean

clean:
	@rm -f $(Client_App_Name) **/*.enc
