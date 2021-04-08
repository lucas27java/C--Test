# Exercícios de fixação em C# realizados em sala de aula📝 ✏️


![Study GIF-downsized_large](https://user-images.githubusercontent.com/74679398/113941197-0bfeac80-97d5-11eb-9e4e-4b58867c784f.gif)


 - **1) Achar a Área do Triangulo**
         
         Console.WriteLine("Por favor insira o valor do raio");
         double RAIO = double.Parse(Console.ReadLine());
         double AREA = RAIO * RAIO * 3.1416;
         Console.WriteLine("Valor final da area");
         Console.WriteLine(AREA);
 
 -  **2.Calcular a Tensão Elétrica**
            
            Console.WriteLine("Calculo de tensao eletrica");
            Console.WriteLine("Insira o valor da corrente eletrica");
            double I = double.Parse(Console.ReadLine());
            Console.WriteLine("Insira a Resistencia");
            double R = double.Parse(Console.ReadLine());
            double V = R * I;
            Console.WriteLine("O valor da tensao eh");
            Console.WriteLine(V);

 - **3) Calculo de Polegadas**
        
        Console.WriteLine("Digite um valor");
        double POLEGADAS = double.Parse(Console.ReadLine());
        double POLEGADAS = POLEGADAS * 2.54;
        Console.WriteLine("O resultado é");
        Console.WriteLine(POLEGADAS);

 - **4) Calculo do Salario** 
         
         Console.WriteLine("Digite o Salário Bruto");
         double SALARIO_BRUTO = double.Parse(Console.ReadLine());                                                               
         double PORCENTAGEM1 = SALARIO_BRUTO * 0.10;//a variavel esta sendo declarada, eo = é a formula usada para fazer a conta
         double SALARIO1 = SALARIO_BRUTO - PORCENTAGEM1;
         double PORCENTAGEM2 = SALARIO1 * 0.05;
         double SALARIO_LIQUIDO = SALARIO1 - PORCENTAGEM2;
         Console.WriteLine("Seu Salário Bruto é");
         Console.WriteLine(SALARIO_BRUTO);//Para o resultado ser mostrado,    se escreve o WriteLine e a variavel dentro do parenteses
         Console.WriteLine("Seu Salario Liquido é");
         Console.WriteLine(SALARIO_LIQUIDO);

 -  **5) Classificação da Idade.**
      
        int idade = int.Parse(Console.ReadLine());
        if (idade<=13){Console.WriteLine("Infantil");}
        if ((idade<=14)||(idade<=17)){Console.WriteLine("Juvenil");}
        if (idade>17){Console.WriteLine("Senior");}

 -  **6) Achar o Mês com o Comando Switch**
        
        int mês;
        mês = int.Parse(Console.ReadLine());
        switch (mês)
        
        {
            case 1: 
            Console.WriteLine("Janeiro");
        break;
        
        case 2: 
            Console.WriteLine("Fevereiro");
        break;
        
        case 3: 
            Console.WriteLine("Março");
        break;
        
        case 4: 
            Console.WriteLine("Abril");
        break;
        
        case 5: 
            Console.WriteLine("Maio");
        break;
        
        case 6: 
            Console.WriteLine("Junho");
        break;
        
        case 7: 
            Console.WriteLine("Julho");
        break;

        case 8: 
            Console.WriteLine("Agosto");
        break;
    
        case 9: 
            Console.WriteLine("Setembro");
        break;
    
    
        case 10: 
            Console.WriteLine("Outubro");
        break;
    
    
        case 11: 
            Console.WriteLine("Novembro");
        break;
    
        case 12: 
            
        Console.WriteLine("Dezembro");
        break;
        default:
        Console.WriteLine("Mês não encontrado");
        break;
        }
        Console.WriteLine("Fim do programa");

 
 - **7)   Achar o Múltiplo de 5**
          
          int valor;
          valor = int.Parse(Console.ReadLine());
           if (valor%5==0)
               
           { Console.WriteLine("é mutiplo de 5");
                  
              }        
          
          else 
          {
              Console.WriteLine(" não é mutiplo de 5");
          }

 - **8) Comando While**
         
         int valor = 1;
         while(valor<=50)
        { Console.WriteLine(valor);
        valor++;}

 - **9) Comando If e Else**
       
       int n ;
       n = int.Parse(Console.ReadLine());
        if((n>=100)&&(n<=200))
        {
            Console.WriteLine("Esta entre 100 e 200");
        
        
        }
        else
            
        {Console.WriteLine("Não esta entre 100 e 200");}

 - **10) Calculo do IMC** 
 
        double Peso = double.Parse(Console.ReadLine());
        double Altura = double.Parse(Console.ReadLine());
        double IMC = (Peso/(Altura*Altura));
        if (IMC<=16){Console.WriteLine("Subnutrido");}
        if ((IMC>=16)&&(IMC<=16.99)){Console.WriteLine("Magreza  Moderada");}
        if ((IMC>=17)&&(IMC<=18.49)){Console.WriteLine("Magreza Leve");}
        if ((IMC>=18.5)&&(IMC<=24.99)){Console.WriteLine("Saudavel");}
        if ((IMC>=25)&&(IMC<=29.99)){Console.WriteLine("Sobre Peso");}
        if ((IMC>=30)&&(IMC<=34.99)){Console.WriteLine("Obesidade");}
        if ((IMC>=35)&&(IMC<=39.99)){Console.WriteLine("Obesidade Severa");}
        if (IMC>=40){Console.WriteLine("Obesidade Morbida");}

              

 - **11) Comando If e Else**
        
        int x ;
        int y ;
        x = int.Parse(Console.ReadLine());
        y = int.Parse(Console.ReadLine());
        if (x>y)
         
       {Console.WriteLine((x-y)+"  é maior que y") ;}
        
        else {
           {Console.WriteLine((y-x)+ "  é menor que y");}
        }
        
        
 - **12) Exercicio de Velocidade**
        
         Console.WriteLine("Por favor insira o valor da velocidade inicial");
         double VI = double.Parse(Console.ReadLine());
         double VELOCIDADE_FINAL = VI / 3.6;
         Console.WriteLine("resultado");
         Console.Write(VELOCIDADE_FINAL);
         Console.Write("m/s");

 - **13) Exercicio do Xerox**
     
       double xerox = 0.50;
       double xerox2 = 0.30;
       int folhas = 1;
       folhas = int.Parse(Console.ReadLine());
       if(folhas>=200){Console.WriteLine(xerox2*folhas);}
        
       else 
       {Console.WriteLine(xerox * folhas);}

 - **14) Exercicio de If e Else**
        
        int a = int.Parse(Console.ReadLine());
        int b = int.Parse(Console.ReadLine());
        int c = int.Parse(Console.ReadLine());
        if((a+b>c)&&(a+c>b)&&(b+c>a)){Console.WriteLine("É possivel formar um triangulo");}
        else {Console.WriteLine("Não é possivel formar um triangulo");}
        

 - **15) Exercicio de If e Else**
        
        int a = int.Parse(Console.ReadLine());
        int b = int.Parse(Console.ReadLine());
        int c = int.Parse(Console.ReadLine());
        if((a==b)&&(b==c)){Console.WriteLine("O triangulo é um equilatero");}
        if(((a==b)&&(b!=c))||((a!=b)&&(b==c))||((b!=a)&&(a==c))){Console.WriteLine("O triangulo é isósceles");}
        if((a!=b)&&(b!=c)){Console.WriteLine("O triangulo é escaleno");}    

 - **16) Média do Aluno com If e Else**
        
        int A = int.Parse(Console.ReadLine());
        if (A>=5){Console.WriteLine("Aprovado");}
        else { Console.WriteLine("Reprovado");}
        Console.WriteLine(A);
        int B = int.Parse(Console.ReadLine());
        if (B>=5){Console.WriteLine("Aprovado");}
        else { Console.WriteLine("Reprovado");}
        Console.WriteLine(B);
        int C = int.Parse(Console.ReadLine());
        if (C>=5){Console.WriteLine("Aprovado");}
        else { Console.WriteLine("Reprovado");}
        Console.WriteLine(C);
        int D = int.Parse(Console.ReadLine());  
        if (D>=5){Console.WriteLine("Aprovado");}
        else { Console.WriteLine("Reprovado");}
        Console.WriteLine(D);
        double media = (A+B+C+D)/4;
        Console.WriteLine("media final é");
        Console.Write(media=(A+B+C+D)/4);
        if (media>=5){Console.WriteLine(" Aprovado");}
        else {Console.WriteLine(" Reprovado");}

 - **17) Soma, Subtração, Divisão,Multiplicação**
 
        Console.WriteLine("Insira um valor");
        double A = double.Parse(Console.ReadLine());
        Console.WriteLine("Insira um valor");
        double B = double.Parse(Console.ReadLine());
        Console.WriteLine("O resultado é ");
        double SOMA = A + B;
        double SUBTRAÇÃO = A - B;
        double DIVISÃO = A / B;
        double MULTIPLICAÇÃO = A * B;
        Console.WriteLine(SOMA);
        Console.WriteLine(SUBTRAÇÃO);
        Console.WriteLine(DIVISÃO);
        Console.WriteLine(MULTIPLICAÇÃO);

 - **18) While com If**
       
       int soma;
       int num  = 1;
       while (num <=30) 
        {
        if (num%4==0) 
            {
              Console.Write ("{0}, ",num);
            }
            num=num+1;

 

        

 


