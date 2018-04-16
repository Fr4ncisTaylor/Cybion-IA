# Inteligência Artificial API Cybion
<p align="center"><img src="image.png" alt="cybion_ia"></p>
<p align="center"><a href="francistrapp2000@gmail.com">Autor</a></p>
<p align="center">⚜️<strong>Versão 1.4.4 | Python 3.6+</strong></p>

* * *
## Informações

* Biblioteca oficial para acesso à api Cybion I.A.


* * *
## Instalação

* `pip install Cybion_IA`

* * *
## Usando a Api

* Registrando
```python
import cybion_ia as ia ## importando e renomeando como "ia"

user  = "seu_nome" # seu nome SOMENTE LETRAS
passw = "sua_senha" # sua senha sem símbolos

reg = ia.register(user, passw)
print(reg)
```
 O resultado será semelhante a esse:
 
 ```bash
 {'token' : 012345678901234567890123}
 ```
 
 * Fazendo request
 
 ```python
 import cybion_ia as ia
 
 token = 'Seu_Token' ## Substitua "Seu_Token" pelo seu token.
 
 user = 'Seu_Nome' ## Substitua pelo seu nome.
 
 Api = cybion_ia.Api(token)
 
 print(Api.ia(msg='olá', token=token, user=user))
 ```
 
 O resultado será semelhante a esse:
 
 ```bash
 {'status': '200 OK', 'message': 'Olá!# Tudo bem?'}
 ```
 
 * Recuperando Token
 
 ```python
 
 import cybion_ia
 
 user = 'Seu_Nome'
 passw = 'Sua_Senha'
 
 print(cybion_ia.get_token(user=user, passw=passw)
 ```
 
 O resultado será semelhante a esse:
 
 ```bash 
 {'Token': 012345678901234567890123 }
 ```


