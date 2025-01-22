   
1. Python3 Install
   sudo apt update
   sudo apt install python3
   python3 --version 

2. install FastApi
   pip3 install fastapi 
   pip3 install "uvicorn[standard]" 
   
   if you have error message "error: externally-managed-environment"
   then 
      remove file /usr/lib/Python3.12/EXTERNALLY-MANAGED
	  and retry 
	   
   
3 Install other packages/libraries
   pip3 install pycryptodome 
   pip3 install openpyxl
   pip3 install sqlalchemy
   pip3 install pydantic
    
4. Start program
   python -m uvicorn my_main:app --host 0.0.0.0 --port 8081 --reload