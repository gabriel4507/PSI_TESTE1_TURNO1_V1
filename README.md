# Teste de PSI 1 - Turno 1 - Versão 1

## Informação do aluno

    Nome: Gabriel Veludo

Teste termina às 10:45.

Escreve as respostas dentro dos blocos correspondentes.
Substitui as reticências pelo que é pedido em cada pergunta.
Não desformates o documento.

### P1. Indica o que é impresso pelo seguinte código. Justifica a tua resposta

    int i = 5 / 2;
    
    Console.WriteLine($"*\t{i}");

P1 - Resposta

    
    Neste código é imprimido o *    2 que é uma divisão de número inteiros  5 por 2 o que resulta em 2.
    Em seguida usa o Console.WriteLine para imprimir um * seguido por um caracter de tabulação e o valor de i que é .
    Por isso o resultado impresso será um asterico um espaço de tabulação e um 2.

### P2. Considera o seguinte código com um *bug*

    string s = "2.5";
    int i = Convert.ToInt32(s);

    Console.WriteLine(i);

### Indica uma possível correção para que o código não apresente erros. Explica porque foi necessário fazer essa correção

P2 - Resposta

    

### P3. Escreve um programa que solicite ao utilizador dois números inteiros e apresente a sua soma. Caso o resultado seja um número divisível por 3, deve também ser impressa a mensagem "Múltiplo de 3!"

P3 - Resposta

          Console.WriteLine("Introduza o numero1:");
          int nr1 = int.Parse(Control.ReadLine());

          Console.WriteLine("Introduza o numero2:");
          int nr2 = int.Parse(Control.ReadLine());

          int soma = nr1 + nr2;

          Console.WriteLine("A  soma dos numeros é:" + soma);

          if ( soma % 3 == 0 )
            {
                Console.WriteLine("É um multiplo de 3");
            } 
              

### P4. Tens um repositório git criado localmente, onde estás no ramo 'master'. Queres associá-lo ao repositório remoto contido no url 'https://github.com/PSI/OMeuRepositorioRemoto'. Queres também alterar o nome do ramo atual para 'main'. Deverás enviar os *commits* já feitos localmente para o repositório remoto. Indica os comandos necessários

P4 - Resposta

    git branch -M master main
    git remote add origin https://github.com/PSI/OMeuRepositorioRemoto
    git branch -u origin/main main
    git push -u origin main
    
    
    
