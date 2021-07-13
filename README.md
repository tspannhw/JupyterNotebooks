# JupyterNotebooks

import requests
 
url = "http://cdp.3.89.115.0.nip.io:18131/api/v1/query/5196/stonks?key=4bb7455c-7f39-4dce-8bf5-f1385c448970"
 
response = requests.request("GET", url)

print(response.text)
