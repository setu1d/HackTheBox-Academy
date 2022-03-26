## HTTP Fundamentals

### HyperText Transfer Protocol (HTTP)


*Questions*
  
target:   165.227.238.95:30601  
  
Q: To get the flag, use cURL to download the file returned by '/download.php' in the above server.  
A: ***HTB{64$!c_cURL_u$3r}***
  
### Solutions:
  
![obrázok](https://user-images.githubusercontent.com/86005993/160243428-e83c4260-13ec-4a81-a601-7489fa8a4ebb.png)
  
-----------------------------------------------------------------------------------------------------------------------------------------------------
  
### HTTP Requests and Responses
  
*Questions*
  
Target: 165.227.238.95:31097
  
Q: What is the HTTP method used while intercepting the request? (case-sensitive)  
A: ***GET***  
  
Q: Send a GET request to the above server, and read the response headers to find the version of Apache running on the server? (answer format: X.Y.ZZ)  
A: ***2.4.41***
  
### Solutions:  
  
![obrázok](https://user-images.githubusercontent.com/86005993/160245596-3c0be782-54b6-4027-a327-b1a120f098ce.png)  
![obrázok](https://user-images.githubusercontent.com/86005993/160245635-6276e79a-e0f0-4cd6-8713-d74d9e489bc1.png)  
  
-----------------------------------------------------------------------------------------------------------------------------------------------------
  
### HTTP Headers  
  
*Questions*
  
 Target: 159.65.56.112:31338
  

Q: The server above loads the flag after the page is loaded. Use the Network tab in the browser devtools to see what requests are made by the page, and find the request to the flag.  
A: ***HTB{p493_r3qu3$t$_m0n!t0r}***  
    
### Solutions:  
    
![obrázok](https://user-images.githubusercontent.com/86005993/160246637-b58b82e9-425d-4e6a-b510-2a2b2b3e88d7.png)  
![obrázok](https://user-images.githubusercontent.com/86005993/160246656-e0f2a7f8-5906-45c3-89bd-6ee1cff71c9c.png)
![obrázok](https://user-images.githubusercontent.com/86005993/160246696-95131d5c-ce7e-44bc-b2cc-3720acf7917e.png) 
![obrázok](https://user-images.githubusercontent.com/86005993/160246763-40e44446-dfa1-49af-956b-47ce4186b2e5.png)
  
## HTTP Methods  

### GET 
  
*Questions*
  
Target: 167.172.52.221:31693  
  
Q: The exercise above seems to be broken, as it returns incorrect results. Use the browser devtools to see what is the request it is sending when we search, and use cURL to search for 'flag' and obtain the flag.  
A: ***HTB{curl_g3773r}***  
  
### Solutions:  
  
![obrázok](https://user-images.githubusercontent.com/86005993/160254480-79a7ca49-bcfc-4225-ae26-8c1ad9bcca20.png) 

### POST

*Questions*  
  
Target: 
  
Q: Obtain a session cookie through a valid login, and then use the cookie with cURL to search for the flag through a JSON POST request to '/search.php'  
A: ***HTB{p0$t_r3p34t3r}***
  
### Solutions:
  
![obrázok](https://user-images.githubusercontent.com/86005993/160255884-14f978f5-a6a4-4a76-979b-d239e91551dd.png)









