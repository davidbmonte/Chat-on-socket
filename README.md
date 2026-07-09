# Simple Python TCP Chat (Socket & Threading)

Este é um projeto simples de chat bilateral (Peer-to-Peer / Cliente-Servidor) desenvolvido em Python utilizando a biblioteca nativa `socket` para comunicação em rede TCP e `threading` para permitir o envio e recebimento de mensagens de forma simultânea (assíncrona).

## 🚀 Funcionalidades

* **Comunicação Bidirecional:** O host e o cliente podem enviar e receber mensagens ao mesmo tempo.
* **Multithreading:** Uso de threads para que o terminal não fique travado esperando uma resposta antes de permitir digitar uma nova mensagem.
* **Controle de Conexão:** Encerramento limpo da comunicação ao digitar `exit`.

---

## 🛠️ Pré-requisitos

Para rodar este projeto, você só precisa do **Python 3.x** instalado na sua máquina. Nenhuma biblioteca externa é necessária, pois o projeto utiliza módulos nativos do Python.

---

## 💻 Como Executar o Projeto

Você pode testar o projeto localmente na mesma máquina ou em computadores diferentes dentro da mesma rede.

### 1. Clonar o repositório
```bash
git clone [https://github.com/seu-usuario/seu-repositorio.git](https://github.com/seu-usuario/seu-repositorio.git)
cd seu-repositorio
