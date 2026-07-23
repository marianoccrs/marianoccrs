<div align="center">

# Mariano Cáceres

**Software Engineering & Cybersecurity Student** · Back-end Python · Application Security

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/marianoccrs/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:mariano.caceres.dev@gmail.com)
![Profile views](https://img.shields.io/badge/dynamic/json?style=flat-square&color=0f2136&label=profile%20views&query=%24.count&url=https%3A%2F%2Fapi.countapi.xyz%2Fhit%2Fmarianoccrs%2Fprofile-readme)

</div>

<br>

## Sobre

Estudante cursando **Engenharia de Software** e **Cibersegurança** simultaneamente
(Universidade Estácio de Sá), com foco em desenvolvimento back-end seguro e
segurança de aplicações (AppSec).

Trabalho com Python, SQL e APIs REST aplicando fundamentos de secure coding e
o OWASP Top 10 desde o design, não como uma camada adicionada depois. Busco
minha primeira oportunidade de estágio para atuar com código em produção e
evoluir junto de um time técnico.

<br>

## Stack

<table>
<tr>
<td valign="top" width="50%">

**Desenvolvimento**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

</td>
<td valign="top" width="50%">

**Segurança**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Kali](https://img.shields.io/badge/Kali_Linux-557C94?style=flat-square&logo=kalilinux&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-000000?style=flat-square)
![OWASP](https://img.shields.io/badge/OWASP_Top_10-000000?style=flat-square&logo=owasp&logoColor=white)

</td>
</tr>
</table>

<br>

## Projetos

Poucos projetos, focados em back-end + segurança, cada um com decisões de
design documentadas no próprio README (não só o que o código faz, mas por quê).

<table>
<tr>
<td width="33%" valign="top">

**[secure-auth-api](https://github.com/marianoccrs/secure-auth-api)**

API de autenticação: hash de senha com bcrypt, JWT, bloqueio contra
força bruta e política de senha.

`Python` `FastAPI` `SQLAlchemy`

</td>
<td width="33%" valign="top">

**[log-analyzer-python](https://github.com/marianoccrs/log-analyzer-python)**

CLI que analisa logs SSH/Apache e detecta padrões de brute-force e
scanning, com relatório em CSV/JSON.

`Python`

</td>
<td width="33%" valign="top">

**[secure-crud-api](https://github.com/marianoccrs/secure-crud-api)**

API REST com isolamento de dados por usuário — proteção contra BOLA
(#1 do OWASP API Security Top 10).

`Python` `FastAPI` `SQLAlchemy`

</td>
</tr>
</table>

<br>

## Prova técnica

Trecho real do `secure-auth-api` — bloqueio de conta após tentativas de login
repetidas, para mitigar força bruta:

```python
def register_failed_attempt(db: Session, user: models.User) -> None:
    user.failed_login_attempts += 1
    if user.failed_login_attempts >= MAX_FAILED_ATTEMPTS:
        user.locked_until = datetime.now(timezone.utc) + timedelta(
            minutes=LOCKOUT_DURATION_MINUTES
        )
    db.commit()
```

<br>

## Estatísticas

<div align="center">
<img height="165" src="https://github-readme-stats.vercel.app/api?username=marianoccrs&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=marianoccrs&layout=compact&theme=tokyonight&hide_border=true" />
</div>

<br>

## Contato

📧 mariano.caceres.dev@gmail.com · 🔗 [linkedin.com/in/marianoccrs](https://www.linkedin.com/in/marianoccrs/) · 📍 Rio de Janeiro, Brasil
