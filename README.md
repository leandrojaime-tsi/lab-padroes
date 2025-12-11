# lab-padroes
## Descrição
Este projeto implementa um padrão de conexão segura com o banco de dados, utilizando **Desing Patterns** para evitar *Hardcoding*.

## O que foi feito:
- [x] Criação de repositorio
- [x] Implementação de conexão
- [x] Resolução de conflito Merge
- [x] Separação de configuração

## Exemplo de uso:
Abaixo, o código padrão utilizado pelo Arquiteto:

```python
# Constante de configuração
DB_HOST = "192.168.0.1"

def configurar_banco():
    ***Conecta usando constante definida***
    return f"Conectado ao {DB_HOST}"
