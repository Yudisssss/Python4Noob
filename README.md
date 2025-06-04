<h1 align="center">
  <img src="https://static.wixstatic.com/media/efe4c3_6865853cc59c4bc89ef3191bba086130~mv2.jpg/v1/fill/w_560,h_188,al_c,q_80,usm_0.66_1.00_0.01,enc_auto/efe4c3_6865853cc59c4bc89ef3191bba086130~mv2.jpg" alt="python_logo_extended" width="100%" />
</h1>

Esse repositório foi feito para estudo, então gostaria de compartilhar para ajudar quem está começando a usar o Python agora.    

> [!IMPORTANT]  
> Tenha em mente que isso não é um tutorial feito para você seguir e sim ter uma base para começar! 

### Instalação 

Para Linux:  
<a href="https://python.org.br/instalacao-linux/"><img aligm="center" alt="C++" heigth="20" width="30" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/linux/linux-original.svg" /></a>   


Para Windows:  
<a href="https://python.org.br/instalacao-windows/"><img aligm="center" alt="C++" heigth="20" width="30" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/windows11/windows11-original.svg" /></a> 

## Criação de Ambiente
> [!IMPORTANT]  
> Criação de Ambiente para Linux 

venv = Virtual Environment   
Python =  é o interpretador Python do venv (uma cópia isolada).  
Pip = é o gerenciador de pacotes do venv.  
Activate = é um script que altera temporariamente o terminal para usar o venv.


### Instalando dependecias
```
sudo apt install python3.12-venv
```

### Criação do Ambiente 
```
python3 -m venv {Nome_que_você_quiser}
```

### Ativação do Ambiente
```
source {Nome_da_Pasta}/bin/activate
```

### Ativação realizada com Sucesso
```
(venv) usuario@maquina:~/meuprojeto$
```

### Desativar Ambiente
```
deactivate
```

### Remover Ambiente
```
rm -rf {Nome_da_Pasta}
```

## ✅ Resumo rápido

| Ação                   | Comando                                 |
| ---------------------- | --------------------------------------- |
| Criar venv             | `python3 -m venv venv`                  |
| Ativar venv            | `source venv/bin/activate`              |
| Instalar pacotes       | `pip install nome-do-pacote`            |
| Desativar              | `deactivate`                            |
| Remover                | `rm -rf venv`                           |
| Trocar para outro venv | `source caminho/para/venv/bin/activate` |

---

> [!IMPORTANT]  
> Criação de Ambiente para Windows

### No Prompt de Comando (cmd):

```
venv\Scripts\activate
```

### No PowerShell:

```
.\venv\Scripts\Activate.ps1
```

 Se der erro de permissão no PowerShell, rode este comando **uma vez** como administrador:

```
Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned
```

---

<p align="center">
    Tenha bons estudos!
</p>