# Test-Driven Development with Python, 2nd Edition

> Minhas **notas** e **códigos** do livro.

![logo](images/logo.jpeg)

## Conteúdo

 - **Prerequisites and Assumptions:**
   - [Introdução e Instalação do Geckodriver](#geckodriver)
 - **Chapter 1. Getting Django Set Up Using a Functional Test:**
   - [Criando um projeto Django com django-admin.py](#django-admin-py)
   - [Adicionando arquivos ao .gitignore com o comando "echo"](#gitignore)
 - **Chapter 02:**
 - **Chapter 03:**
 - **Chapter 04:**
 - **Chapter 05:**
 - **Chapter 06:**
 - **Chapter 07:**
 - **Chapter 08:**
 - **Chapter 09:**
 - **Chapter 10:**
 - **Chapter 11:**
 - **Chapter 12:**
 - **Chapter 13:**
 - **Chapter 14:**
 - **Chapter 15:**
 - **Chapter 16:**
 - **Chapter 17:**
 - **Chapter 18:**
 - **Chapter 19:**
 - **Chapter 20:**
 - **Chapter 21:**
 - **Chapter 22:**
 - **Chapter 23:**
 - **Chapter 24:**
 - **Chapter 25:**
 - **Chapter 26:**
 - **Appendix:**
   - **Appendix A. PythonAnywhere:**
   - **Appendix B. Django Class-Based Views:**
   - **Appendix C. Provisioning with Ansible:**
   - **Appendix D. Testing Database Migrations:**
   - **Appendix E. Behaviour-Driven Development (BDD):**
   - **Appendix F. Building a REST API: JSON, Ajax, and Mocking with JavaScript:**
   - **Appendix G. Django-Rest-Framework:**
   - **Appendix H. Cheat Sheet:**

---

<div id="geckodriver"></div>

## Introdução e Instalação do Geckodriver

> Bem, resumidamente o **Geckodriver** é o *driver* que nos permitirá controlar remotamente o **Firefox** via Selenium.

Geckodriver está disponível em [https://github.com/mozilla/geckodriver/releases](https://github.com/mozilla/geckodriver/releases). Você precisa fazer o download, extraí-lo e colocá-lo em algum lugar no caminho do sistema.

**NOTE:**  
Para **Windows**, você pode simplesmente colocá-lo na mesma pasta que o código deste livro - ou se você colocá-lo na pasta Python *Scripts*, ele estará disponível para outros projetos.

**NOTE:**  
Para **macOS** ou **Linux**, um local conveniente para colocá-lo é **/usr/local/bin** *(você precisará sudo disso)*.

Para testar se isso está funcionando, abra um console Bash e você deverá ser capaz de executar:

```
$ geckodriver --version
```

**OUTPUT:**  
```
geckodriver 0.30.0 (d372710b98a6 2021-09-16 10:29 +0300)

The source code of this program is available from
testing/geckodriver in https://hg.mozilla.org/mozilla-central.

This program is subject to the terms of the Mozilla Public License 2.0.
You can obtain a copy of the license at https://mozilla.org/MPL/2.0/.
```

---

<div id="django-admin-py"></div>

## Criando um projeto Django com django-admin.py

A primeira etapa para colocar o Django em funcionamento é criar um projeto, que será o contêiner principal de nosso site. Django fornece uma pequena ferramenta de linha de comando para isso:

```python
$ django-admin.py startproject superlists .
```

**NOTE:**  
Não se esqueça do **“.”** no fim; é importante!

---

<div id="gitignore"></div>

## Adicionando arquivos ao .gitignore com o comando "echo"

Agora vamos dar uma olhada e ver quais arquivos queremos enviar, para isso vamos utilizar o comando **ls**:

```
ls
```

**OUTPUT:**
```
db.sqlite3 
function_tests.py 
geckodriver.log 
manage.py 
superlists 
virtualenv
```

Existem algumas coisas aqui que não queremos sob controle de versão:

 - **db.sqlite3**
   - É o arquivo de banco de dados
 - **geckodriver.log**
   - Contém a saída de depuração do Selenium
 - **virtualenv**
   -  E, finalmente, nosso virtualenv também não deve estar no git.

Vamos adicionar todos eles a um arquivo especial chamado **.gitignore** que, hum, diz ao Git o que deve ser ignorado:

```python
$ echo "db.sqlite3" >> .gitignore
$ echo "geckodriver.log" >> .gitignore
$ echo "virtualenv" >> .gitignore
```

---

<div id=""></div>

## x

x

---

<div id=""></div>

## x

x

---

<div id=""></div>

## x

x

---

<div id=""></div>

## x

x

---

<div id=""></div>

## x

x

---

<div id=""></div>

## x

x

---

<div id=""></div>

## x

x

---

<div id=""></div>

## x

x

---


<div id=""></div>

## x

x

---

<div id=""></div>

## x

x

---

<div id=""></div>

## x

x

---

<div id=""></div>

## x

x

---

<div id=""></div>

## x

x

---

<div id=""></div>

## x

x

---

<div id=""></div>

## x

x

---

<div id=""></div>

## x

x

---


<div id=""></div>

## x

x

---

<div id=""></div>

## x

x

---

<div id=""></div>

## x

x

---

<div id=""></div>

## x

x

---

<div id=""></div>

## x

x

---

<div id=""></div>

## x

x

---

<div id=""></div>

## x

x

---

<div id=""></div>

## x

x

---


<div id=""></div>

## x

x

---

<div id=""></div>

## x

x

---

<div id=""></div>

## x

x

---

<div id=""></div>

## x

x

---

<div id=""></div>

## x

x

---

<div id=""></div>

## x

x

---

<div id=""></div>

## x

x

---

<div id=""></div>

## x

x

---


<div id=""></div>

## x

x

---

<div id=""></div>

## x

x

---

<div id=""></div>

## x

x

---

<div id=""></div>

## x

x

---

<div id=""></div>

## x

x

---

<div id=""></div>

## x

x

---

<div id=""></div>

## x

x

---

<div id=""></div>

## x

x

---



















**REFERENCE:**  
[Test-Driven Development with Python, 2nd Edition](https://learning.oreilly.com/library/view/test-driven-development-with/9781491958698/)
