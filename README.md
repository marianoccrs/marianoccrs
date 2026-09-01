<div align="center">

<img src="https://raw.githubusercontent.com/marianoccrs/marianoccrs/main/assets/banner.jpg" width="100%" alt="Mariano Cáceres - Backend Development & Application Security">

<br><br>

<h3>BACKEND · PYTHON · FASTAPI · APPSEC · CYBERSECURITY</h3>

<p>
  <img src="https://img.shields.io/badge/Python-050B14?style=for-the-badge&logo=python&logoColor=00D9FF">
  <img src="https://img.shields.io/badge/FastAPI-050B14?style=for-the-badge&logo=fastapi&logoColor=00D9FF">
  <img src="https://img.shields.io/badge/OWASP-050B14?style=for-the-badge&logo=owasp&logoColor=00D9FF">
  <img src="https://img.shields.io/badge/Linux-050B14?style=for-the-badge&logo=linux&logoColor=00D9FF">
  <img src="https://img.shields.io/badge/Git-050B14?style=for-the-badge&logo=git&logoColor=00D9FF">
</p>

<p>
  <strong>Building secure applications while growing as a software engineer.</strong>
</p>

</div>

---

## About Me

Sou estudante de **Engenharia de Software e Cibersegurança**, com foco em **Backend Development, Python, FastAPI e Application Security (AppSec)**.

Construo projetos práticos relacionados a desenvolvimento de APIs, autenticação, autorização, controle de acesso, segurança de aplicações e análise de logs.

Meu posicionamento profissional está na interseção entre:

**Backend Development + Software Engineering + Application Security**

Atualmente busco minha primeira oportunidade como **Estagiário de Desenvolvimento Backend, Desenvolvedor Backend Júnior, Estagiário de Cybersecurity ou Estagiário de AppSec**.

---

## Security Focus

Meu principal foco técnico está em compreender como aplicações backend podem ser projetadas e implementadas considerando segurança desde o desenvolvimento.

**Application Security**

```text
OWASP Top 10
OWASP API Security Top 10
Secure Coding
Authentication
Authorization
Access Control
BOLA
JWT
Password Hashing
Input Validation
API Security
Brute-force Protection
Log Analysis
Linux Security

Meu objetivo não é apenas implementar funcionalidades, mas compreender como uma aplicação pode falhar, ser abusada e quais controles podem reduzir esses riscos.

Security should be part of the development process from the beginning.

Technical Stack
Backend

Python · FastAPI · SQLAlchemy · REST APIs · SQL

Application Security

OWASP · AppSec · Secure Coding · Authentication · Authorization · API Security

Tools & Environment

Linux · Git · GitHub · CLI · JSON · CSV

Featured Projects
secure-auth-api

Secure REST API authentication built with Python and FastAPI.

Projeto desenvolvido para estudar mecanismos de autenticação, proteção de credenciais e controles de segurança em aplicações backend.

Security Focus
Password hashing com bcrypt
JWT authentication
Política de senhas
Controle de tentativas de login
Account lockout
Input validation
Database persistence
Authentication controls
Authentication Flow
                  ┌─────────────────┐
                  │      USER       │
                  └────────┬────────┘
                           │
                           ▼
                  ┌─────────────────┐
                  │  LOGIN REQUEST  │
                  └────────┬────────┘
                           │
                           ▼
                  ┌─────────────────┐
                  │    VALIDATE     │
                  │   CREDENTIALS   │
                  └────────┬────────┘
                           │
                   ┌───────┴───────┐
                   │               │
                INVALID          VALID
                   │               │
                   ▼               ▼
            ┌─────────────┐  ┌─────────────┐
            │    TRACK    │  │  GENERATE   │
            │   ATTEMPT   │  │     JWT     │
            └──────┬──────┘  └──────┬──────┘
                   │                │
                   ▼                ▼
            ┌─────────────┐  ┌─────────────┐
            │  PROTECTION │  │ AUTHENTICATED│
            └─────────────┘  │   REQUEST    │
                             └─────────────┘

Technologies

Python · FastAPI · SQLAlchemy · JWT · bcrypt · SQL

secure-crud-api

REST API focused on authentication, authorization and user-level data isolation.

Projeto desenvolvido com Python + FastAPI para estudar controle de acesso, autorização e isolamento de recursos entre usuários.

O principal conceito de segurança estudado neste projeto é:

BOLA — Broken Object Level Authorization

Security Focus
Authentication
Authorization
Access Control
User Data Isolation
Resource Ownership Validation
Input Validation
CRUD
API Security
BOLA Prevention
Authorization Flow
              AUTHENTICATED USER
                       │
                       ▼
                ┌─────────────┐
                │ API REQUEST │
                └──────┬──────┘
                       │
                       ▼
               ┌───────────────┐
               │    RESOURCE   │
               │    LOOKUP     │
               └───────┬───────┘
                       │
                       ▼
             ┌───────────────────┐
             │ OWNERSHIP / ACCESS│
             │    VALIDATION     │
             └─────────┬─────────┘
                       │
                 ┌─────┴─────┐
                 │           │
               ALLOWED      DENIED
                 │           │
                 ▼           ▼
          ┌────────────┐  ┌─────────┐
          │  RESOURCE  │  │   403   │
          │   ACCESS   │  │ FORBIDDEN│
          └────────────┘  └─────────┘

Technologies

Python · FastAPI · SQLAlchemy · SQL · REST API · OWASP

log-analyzer-python

CLI for SSH and Apache log analysis.

Ferramenta desenvolvida em Python para análise de logs SSH e Apache, com foco na identificação de padrões potencialmente relacionados a brute force, scanning e outros comportamentos suspeitos.

Features
SSH log analysis
Apache log analysis
Brute-force detection
Scanning patterns
CSV reports
JSON reports
CLI interface

Technologies

Python · Linux · CLI · SSH · Apache · CSV · JSON

Software Engineering

Além de desenvolver funcionalidades, busco construir uma visão de engenharia sobre as aplicações que desenvolvo.

Engineering Practices
Clean Code
Separation of Responsibilities
Input Validation
Error Handling
Authentication
Authorization
Database Persistence
Documentation
Testing
Git
Secure Coding
Application Security

Meu objetivo é desenvolver software que seja:

SECURE
   ↓
MAINTAINABLE
   ↓
TESTABLE
   ↓
DOCUMENTED
   ↓
SUSTAINABLE
Security Mindset

Minha abordagem de desenvolvimento e estudo segue um ciclo orientado à segurança:

┌───────────────┐
│   UNDERSTAND  │
└───────┬───────┘
        ↓
┌───────────────┐
│     DESIGN    │
└───────┬───────┘
        ↓
┌───────────────┐
│     BUILD     │
└───────┬───────┘
        ↓
┌───────────────┐
│    VALIDATE   │
└───────┬───────┘
        ↓
┌───────────────┐
│      TEST     │
└───────┬───────┘
        ↓
┌───────────────┐
│     SECURE    │
└───────┬───────┘
        ↓
┌───────────────┐
│   DOCUMENT    │
└───────┬───────┘
        ↓
┌───────────────┐
│    IMPROVE     │
└───────────────┘

O objetivo não é apenas fazer uma aplicação funcionar.

É entender como ela pode falhar, como pode ser abusada e como seus controles podem ser melhorados.

Currently Learning
Backend Development

Python · FastAPI · SQL · SQLAlchemy · REST APIs

Cybersecurity

OWASP · Application Security · API Security · Secure Coding

Software Engineering

Testing · Software Architecture · Git · Linux · CI/CD

Complementary Experience

Também desenvolvi um projeto relacionado a:

Python · pandas · Data Cleaning · Data Validation · Data Quality

O projeto utiliza uma base fictícia de estudo clínico para praticar limpeza, validação, identificação de inconsistências e análise da qualidade dos dados.

Essa área representa uma experiência complementar.

Foco profissional principal:

Backend Development + Application Security + Cybersecurity

Professional Goal

Busco minha primeira oportunidade profissional como:

Estagiário de Desenvolvimento Backend
Desenvolvedor Backend Júnior
Estagiário de Cybersecurity
Estagiário de AppSec

Tenho interesse em oportunidades presenciais, híbridas ou remotas.

Areas of Interest

Python

Backend Development

REST APIs

Databases

Authentication

Authorization

API Security

Application Security

Software Engineering

Cybersecurity

Meu objetivo é evoluir profissionalmente construindo aplicações:

seguras · organizadas · testáveis · documentadas · sustentáveis

Development Focus
                    BACKEND DEVELOPMENT
                           │
              ┌────────────┼────────────┐
              │            │            │
           Python       FastAPI       SQL
              │            │            │
              └────────────┼────────────┘
                           │
                           ▼
                  APPLICATION SECURITY
                           │
              ┌────────────┼────────────┐
              │            │            │
           OWASP    Authentication   Authorization
              │            │            │
              └────────────┼────────────┘
                           │
                           ▼
                  SOFTWARE ENGINEERING
                           │
              ┌────────────┼────────────┐
              │            │            │
         Clean Code      Testing     Documentation
              │            │            │
              └────────────┼────────────┘
                           │
                           ▼
                       SECURE
                       SOFTWARE
Contact
<div align="center">

Mariano Cáceres

Backend Development · Python · FastAPI · Application Security

<br>

📧 mariano.caceres.dev@gmail.com

🔗 linkedin.com/in/marianoccrs

📍 Rio de Janeiro, Brasil

<br>

BACKEND · PYTHON · APPSEC · CYBERSECURITY

<br>

<sub>Building secure applications while growing as a software engineer.</sub>

</div> ```
