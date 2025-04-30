*Lista de Exercícios 10 - Arquivos*
Para as questões 01 a 05, utilize como referência o arquivo “arquivo-01.txt” que se encontra junto da
atividade. O arquivo contém linhas com dados relacionados a felinos:
a) Nome popular;
b) Nome científico da espécie;
c) Indicação se o animal é doméstico ou selvagem;
d) Peso máximo;
e) Idade máxima em cativeiro.
01. Escreva um método que imprima os nomes científicos de cada um dos felinos disponíveis no arquivo.
02. Escreva um método que imprima o maior peso, o menor peso e a média de peso dos animais presentes
no arquivo.
03. Escreva um método que imprima o nome popular de todos os animais cuja idade máxima em cativeiro
esteja entre 10 e 16 anos.
Para as questões a seguir, utilize os arquivos “arquivo-01.txt” e “arquivo-02.txt”. O segundo arquivo contém
uma sequência de intervalos de pesos (mínimo máximo) correspondentes aos pesos dos felinos.
04. Escreva um programa que exiba, por linha do “arquivo-02.txt”, o nome de todos os felinos existentes no
“arquivo-01.txt” cujo peso máximo esteja dentro dos limites do intervalo.
Obs. 1: Os intervalos são fechados (utilizar <= e/ou >= nas cláusulas).
Obs. 2: O programa deve ser genérico – intervalos não devem ser programados manualmente.
05. Altere o programa anterior para salvar todos os resultados obtidos em um arquivo denominado “arquivo03.txt”.
06. A empresa ACME está tendo problemas de espaço em disco no seu servidor de arquivos (o HD tem
tamanho de 53687091200 bytes). A ACME tem 100 funcionários. As informações de utilização de HD dos
usuários devem ser obtidas do arquivo "usuarios.txt", que deve ser previamente criado pelo aluno antes da
construção do programa e deve possuir o seguinte formato:
 nomeFuncionario/bytesUsados
Maria Silva/45678653
José Antônio/78545678
João Maria Silva/230943086
…
Crie um programa que leia este arquivo e gere um relatório, chamado "relatório.txt", no seguinte formato:
nomeFuncionario/PercentualUsoDoDiscoDesteFuncionario
No final do arquivo deve ser escrito o total de espaço de disco ocupado (em bytes) e o percentual de uso
total do disco. 
