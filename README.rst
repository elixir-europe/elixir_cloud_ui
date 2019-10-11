What is this
=============================
This is a first version of ELIXIR Cloud & AAI web portal (the user interface). The implementation is done with Python and Django and the only functionality in at this point is ELIXIR AAI authentication.

How to deploy this
======================
For deploying this you need to have a client in ELXIR AAI so replace the Client ID and secret values with the real values from ELIXIR AAI. 

```
git clone https://github.com/elixir-europe/elixir_cloud_ui.git
cd elixir_cloud_ui
OIDC_RP_CLIENT_ID=x OIDC_RP_CLIENT_SECRET=y python3 manage.py runserver 
```
