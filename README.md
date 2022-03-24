## OAuth2.0 Work Flow Overwiev:
### *Poniższy obrazek obrazuje w ogólnym skrócie ukazuje działanie OAutha2.0*

<center><img src="images/normal.PNG"></center>

## Projekt składa się z 3 aplikacji modułowych takich jak:
- **spring-security-client**  port: **8080**
- **OAuth Resource-Server**   port: **8090**
- **OAuth Authorization-Server** port **9000**

### *OAuth2.0 flow with Open ID Conncet*

### *1.First step: 127.0.0.1/api/hello*
<!-- ![alt text](images/first.PNG "Tittle")   -->
<center><img src="images/first.PNG"></center>

### *2.Next we are redirect to below URI by authorization server.*
<!-- ![alt text](images/second_good.PNG "Tittle") -->
<center><img src="images/second_good.PNG"></center>

### *3. We must autheciate our acc, by pass credntials*

<!-- ![alt text](images/3.PNG "Tittle") -->
<center><img src="images/3.PNG"></center>

### *4. Next we must check  scope, i wyrazić consenst*
<center><img src="images/udzielenie_zgody.PNG"></center>

<!-- ![alt text](images/udzielenie_zgody.PNG "Tittle") -->

### *5. After That all we got our resorces*

<!-- ![alt text](images/getResources.PNG "Tittle") -->

<center><img src="images/getResources.PNG"></center>

