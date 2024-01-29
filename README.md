This is a JwT Security Demo using spring boot 

when trying to acces the secure endpoint with wrong or no token it returns 403 forbidden 


![403 forbidden no user ](https://github.com/MohamedTaha15/SecurityDemo/assets/91467334/80bd219c-96b2-47b2-bd7a-eb2b1b060d8e)


when trynig to authenticate with  wrong credentials or non existant it returns 403 forbidden 


![authentication wrong password 403 forbidden](https://github.com/MohamedTaha15/SecurityDemo/assets/91467334/c48411ad-2af7-469a-9177-25e06b02ba54)


with succesful registeration of a user the app returns the token 


![registeration succesful and token returned ](https://github.com/MohamedTaha15/SecurityDemo/assets/91467334/9adc7973-4318-433c-9b13-a4d8156950d9)


when trying to authenticate with a succesful user credentials it returns the token 


![authentication succesful and token returned ](https://github.com/MohamedTaha15/SecurityDemo/assets/91467334/e0fdad3c-f830-40e5-9732-1a9a85c2aba7)


the token is decoded and returns the user info 


![token decoded with the data ](https://github.com/MohamedTaha15/SecurityDemo/assets/91467334/700ee722-70e7-46dc-a223-6db8d69ab4bd)


when accessing the secured end point bearing the valid token it retuns the functionality withtin the controller 


![token secured endpoint working ](https://github.com/MohamedTaha15/SecurityDemo/assets/91467334/2a42cfce-48e6-4c24-95b6-f924fad2eead)


