# Gerenciador de Tarefas Simples

Este é um gerenciador de tarefas simples implementado em Python. O programa permite adicionar tarefas, listar todas as tarefas e marcar tarefas como concluídas.

## Funcionalidades

- Adicionar novas tarefas com uma descrição.
- Listar todas as tarefas com status de "pendente" ou "concluída".
- Marcar uma tarefa como concluída.

## Requisitos

- Python 3.x

## Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
2.Navegue até o diretório do projeto
cd nome-do-repositorio
3.Execute o script Python:
python gerenciador_de_tarefas.py
Exemplo de Uso
# Adicionando tarefas
adicionar_tarefas("Estudar Python")
adicionar_tarefas("Fazer exercício físico")

# Listando tarefas
listar_tarefas()

# Marcando a primeira tarefa como concluída
concluir_tarefa(0)

# Listando tarefas novamente
listar_tarefas()
Saída esperada:
1. Estudar Python - pendente
2. Fazer exercício físico - pendente

1. Estudar Python - concluída
2. Fazer exercício físico - pendente
Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

Licença
Este projeto é licenciado sob a MIT License.
