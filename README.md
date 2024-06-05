

# Sistema de Gerenciamento de Restaurantes

Este é um sistema simples de gerenciamento de restaurantes em Python. Ele permite cadastrar novos restaurantes, listar todos os restaurantes, e alternar o estado (ativo/inativo) dos restaurantes existentes.

## Funcionalidades

- **Exibir Nome do Programa**: Exibe o nome do programa com uma arte ASCII.
- **Exibir Opções**: Mostra as opções disponíveis no menu principal.
- **Cadastrar Restaurante**: Permite cadastrar um novo restaurante.
- **Listar Restaurantes**: Lista todos os restaurantes cadastrados com suas categorias e status.
- **Alternar Estado do Restaurante**: Alterna o estado de um restaurante entre ativo e inativo.
- **Finalizar Aplicativo**: Encerra o programa.

## Pré-requisitos

- Python 3.x instalado

## Como usar

1. Clone o repositório ou copie o código para um arquivo Python (`sistema_restaurantes.py`).

2. Execute o arquivo Python:

   ```bash
   python sistema_restaurantes.py
   ```

3. Use o menu principal para navegar pelas opções disponíveis:
   - **1**: Cadastrar restaurante
   - **2**: Listar restaurantes
   - **3**: Alternar estado do restaurante
   - **4**: Sair

## Estrutura do Código

### Lista de Restaurantes

```python
restaurantes = [
    {'nome':'Praça', 'categoria':'Japonesa', 'ativo':False}, 
    {'nome':'Pizza Suprema', 'categoria':'Pizza', 'ativo':True},
    {'nome':'Cantina', 'categoria':'Italiano', 'ativo':False}
]
```

### Funções Principais

- **exibir_nome_do_programa**: Exibe o nome do programa com uma arte ASCII.
- **exibir_opcoes**: Exibe o menu principal.
- **finalizar_app**: Encerra o programa.
- **voltar_ao_menu_principal**: Espera o usuário pressionar uma tecla para voltar ao menu principal.
- **opcao_invalida**: Informa que a opção escolhida é inválida.
- **exibir_subtitulo**: Exibe um subtítulo com bordas.
- **cadastrar_novo_restaurante**: Cadastra um novo restaurante.
- **listar_restaurantes**: Lista todos os restaurantes.
- **alternar_estado_restaurante**: Alterna o estado de um restaurante entre ativo e inativo.
- **escolher_opcao**: Lê a opção escolhida pelo usuário e chama a função correspondente.
- **main**: Função principal que inicializa o programa.

## Exemplo de Uso

1. Ao iniciar o programa, será exibido o nome do programa e o menu principal.
2. Se você escolher a opção 1, poderá cadastrar um novo restaurante.
3. A opção 2 listará todos os restaurantes cadastrados.
4. A opção 3 permitirá alternar o estado de um restaurante.
5. A opção 4 encerrará o programa.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests.
