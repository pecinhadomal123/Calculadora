📚 Sistema de Notas do Aluno




Um projeto simples desenvolvido em Python para praticar conceitos fundamentais de programação, como funções, entrada de dados, operações matemáticas, condicionais e formatação de saída.

O programa recebe duas notas de um aluno, calcula a média final e informa automaticamente se o aluno foi aprovado ou reprovado.

🎯 Objetivo

O objetivo deste projeto é desenvolver uma aplicação simples para cálculo de média escolar e, ao mesmo tempo, praticar conceitos básicos da linguagem Python.

📊 Regra de aprovação
Média	Resultado
≥ 7,0	✅ Aprovado
< 7,0	❌ Reprovado
⚙️ Funcionamento

O programa segue quatro etapas principais:

Solicita a primeira nota do aluno.

Solicita a segunda nota.

Calcula a média das duas notas.

Verifica o resultado e informa o status do aluno.

A média é calculada utilizando a seguinte fórmula:

Média = (Nota 1 + Nota 2) / 2

💻 Código
def calcular_media(nota1, nota2):
    return (nota1 + nota2) / 2


print("=== Sistema de Notas do Aluno ===")

n1 = float(input("Digite a primeira nota: "))
n2 = float(input("Digite a segunda nota: "))

media = calcular_media(n1, n2)

print(f"A média final é: {media:.2f}")

if media >= 7.0:
    print("Status: Aprovado!")
else:
    print("Status: Reprovado.")

🚀 Como executar
Pré-requisitos

Antes de executar o projeto, certifique-se de ter o Python 3 instalado.

Para verificar a instalação:

python --version


ou:

python3 --version

Clone o repositório
git clone https://github.com/seu-usuario/sistema-notas.git


Entre na pasta do projeto:

cd sistema-notas


Execute o programa:

python sistema_notas.py

🖥️ Exemplo de uso
Aluno aprovado
=== Sistema de Notas do Aluno ===
Digite a primeira nota: 8
Digite a segunda nota: 7

A média final é: 7.50
Status: Aprovado!

Aluno reprovado
=== Sistema de Notas do Aluno ===
Digite a primeira nota: 5
Digite a segunda nota: 6

A média final é: 5.50
Status: Reprovado.

🧠 Conceitos utilizados

Este projeto utiliza alguns conceitos importantes da programação em Python:

Funções — organização da lógica de cálculo da média;

Variáveis — armazenamento das notas e da média;

input() — entrada de dados pelo usuário;

float() — conversão dos valores para números decimais;

Operadores matemáticos — cálculo da média;

if/else — tomada de decisão;

F-strings — formatação da média com duas casas decimais.

Exemplo da função
def calcular_media(nota1, nota2):
    return (nota1 + nota2) / 2


Essa função recebe duas notas como parâmetros e retorna a média entre elas.

📁 Estrutura do projeto
sistema-notas/
│
├── sistema_notas.py
└── README.md

Arquivo	Descrição
sistema_notas.py	Código principal da aplicação
README.md	Documentação do projeto
🔮 Melhorias futuras

Algumas funcionalidades que podem ser adicionadas futuramente:

 Validar se as notas estão entre 0 e 10;

 Adicionar uma terceira nota;

 Criar um sistema de recuperação;

 Permitir o cadastro de vários alunos;

 Exibir um relatório com as notas;

 Criar uma interface gráfica;

 Salvar os resultados em um arquivo;

 Criar testes automatizados.

📌 Status do projeto

🟢 Concluído

O projeto atualmente realiza o cálculo da média de duas notas e apresenta o status do aluno de acordo com a média obtida.

👨‍💻 Autor

Desenvolvido como projeto de estudo para praticar Python e lógica de programação.

📄 Licença

Este projeto pode ser utilizado livremente para fins de estudo e aprendizado.
