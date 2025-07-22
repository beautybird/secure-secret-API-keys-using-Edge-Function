# secure-secret-API-keys-using-Edge-Function
Secure your secret API keys (i,e, Google API keys and more) using edge function

<img width="920" height="519" alt="secure_API_Logo" src="https://github.com/user-attachments/assets/0b9f98f9-bb30-4ef9-acaf-87a7d6acd409" />


The goal is to not expose our Google API keys and our Supabase 

secret keys and any othe API's keys by not hard-coding them in the client side as it's the worst thing to do , instead 

we use the Edge function to save those keys and client make a call whenever needs to use any of these keys.  

Step by step use this setup guide to secure your client side app secret keys.

How to secure your keys, create the edge function code , deploy the function , then invoke it from the client side

![edge_function_secure_API](https://github.com/user-attachments/assets/8f69ea04-8de1-47a0-ba35-cfef536a8c8a)


using a helper class to connect to any API like Google maps or other services .

  https://youtu.be/YMFIW-Elexw  

with the entire code ..

