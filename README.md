# secure-secret-API-keys-using-Edge-Function
Secure your secret API keys (i,e, Google API keys and more) using edge function

The goal is to not expose our Google API keys and our Supabase 

secret keys and any othe API's keys by not hard-coding them in the client side as it's the worst thing to do , instead 

we use the Edge function to save those keys and client make a call whenever needs to use any of these keys.  

