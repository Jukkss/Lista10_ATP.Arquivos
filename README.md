## 📘 Lista de Exercícios 10 - Arquivos

### Arquivo de referência: `arquivo-01.txt`

Este arquivo contém dados de felinos com as seguintes informações por linha:

- Nome popular  
- Nome científico da espécie  
- Indicação se o animal é doméstico ou selvagem  
- Peso máximo  
- Idade máxima em cativeiro

---

### Questões

**01.** Escreva um método que imprima os nomes científicos de cada um dos felinos disponíveis no arquivo.

**02.** Escreva um método que imprima o maior peso, o menor peso e a média de peso dos animais presentes no arquivo.

**03.** Escreva um método que imprima o nome popular de todos os animais cuja idade máxima em cativeiro esteja entre 10 e 16 anos.

---

### Arquivos de referência: `arquivo-01.txt` e `arquivo-02.txt`

O segundo arquivo contém intervalos de peso (mínimo e máximo) para filtragem dos felinos.

**04.** Escreva um programa que exiba, por linha do `arquivo-02.txt`, o nome de todos os felinos existentes no `arquivo-01.txt` cujo peso máximo esteja dentro dos limites do intervalo.

Obs. 1: Os intervalos são fechados (utilizar `<=` e/ou `>=`).  
Obs. 2: O programa deve ser genérico — os intervalos não devem ser programados manualmente.

**05.** Altere o programa anterior para salvar todos os resultados obtidos em um arquivo denominado `arquivo03.txt`.

---

### Questão 06 – Relatório de uso de disco

A empresa ACME está enfrentando problemas de espaço em disco. O HD tem um tamanho total de `53687091200` bytes (50 GB), e existem 100 funcionários. As informações de uso individual estão contidas no arquivo `usuarios.txt`, com o seguinte formato:





