# Ficha 1 de Programação e Sistemas de Informação - Módulo 13

Cria um repositório **privado** no GitHub com o nome **"PSI_Ficha1_M13"** e com um ficheiro **README**.

Podes fazer clone do repositório para o teu computador (ou para o Replit) e preencher o README localmente (ou no Replit) com as respostas dos exercícios. Seguidamente, terás de fazer commit e push das atualizações.

Alternativamente, podes preencher o ficheiro README diretamente no GitHub. A partir da página principal do repositório, clica em "Edit File" (ícone representando um lápis). Com o README preenchido, carrega no botão "Commit Changes".

Para entregar a ficha, acede a [este link](https://docs.google.com/spreadsheets/d/1DrdGnICVAA8q9bs9_LAURFKoReAO7jJGB8qqvUWacL0/edit?usp=sharing) (separador **Ficha Módulo 11**), e mete o **URL** do teu repositório ao lado do teu nome.
No teu repositório, acede a "Settings -> Collaborators" e adiciona o utilizador "Manuel Geraldes" para ter acesso.

## Exercício 1 - Responde às seguintes questões, e indica se as afirmações são verdadeiras ou falsas. (6v)

1. Qual a *keyword* para declarar uma interface?
2. Qual a visibilidade dos membros de uma interface?
3. Uma classe que implementa uma interface não tem de fornecer implementações de todos os membros da interface.
4. Uma classe que implementa uma interface pode ter membros que não estão definidos na interface.
5. Uma classe pode estender mais do que uma classe base.
6. Uma classe pode implementar mais do que uma interface.


## Exercício 2 - Considera o diagrama UML em baixo e indica, justificando, quais das seguintes instruções são válidas e quais são inválidas. (14v)
Considera que todas as instruções ocorrem fora das classes presentes no diagrama (por exemplo, numa classe Program).

!(UML)[uml.png]

* 'Animal animal = new Cao();'
* 'Gato gato = new Cao();'
* 'Gato gato = new Animal();'
* a.Ladrar(); // 'a' é uma instância de Animal
* c.Comer(); // 'c' é uma instância de Cao
* float x = g.Energia; // 'g' é uma instância de Gato
* Console.WriteLine(g.Nome); // 'g' é uma instância de Gato
