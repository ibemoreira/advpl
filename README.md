<div align="center">

# Wilberte Santos

</div>

---

## 🎯 Overview

Este projeto é uma função em **ADVPL** para o sistema **Protheus** que integra com uma API externa de câmbio para atualizar as taxas de câmbio de moedas estrangeiras (USD, EUR, JPY) para o real (BRL). A função busca as taxas mais recentes e as armazena no banco de dados do Protheus.

---

## ✨ Features

- **Consulta de Câmbio**: Realiza a consulta das taxas de câmbio de USD, EUR e JPY para o BRL.
- **Atualização no Banco de Dados**: Armazena as taxas de câmbio no banco de dados Protheus na tabela `SM2`.
- **Manipulação de Registros**: Se um registro com a data atual já existir, ele é atualizado; caso contrário, um novo registro é criado.
- **API de Câmbio**: Utiliza a API pública [AwesomeAPI](https://economia.awesomeapi.com.br/json/last) para obter as taxas de câmbio.

---

