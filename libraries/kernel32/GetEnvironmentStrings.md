
## Function name : GetEnvironmentStrings
Group: Process and Thread - Library: kernel32    
***  


#### Retrieves the environment block for the current process.

***  


## Code examples:
[Storing the environment strings in cursor](../../samples/sample_089.md)  

## Declaration:
```foxpro  
LPVOID GetEnvironmentStrings(VOID);  
```  
***  


## FoxPro declaration:
```foxpro  
DECLARE INTEGER GetEnvironmentStrings IN kernel32  
```  
***  


## Parameters:
This function has no parameters.  
***  


## Return value:
The return value is a pointer to an environment block for the current process.  
***  


## Comments:
A process can use this function"s return value to specify the environment address used by the CreateProcess function.  
  
***  
