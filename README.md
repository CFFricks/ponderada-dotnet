# ponderada-dotnet

## Resumo

O projeto `Bank` foi desenvolvido como um exercício prático do autoestudo ponderado para implementação e teste de um sistema de gerenciamento de contas bancárias em C#. Utilizando o .NET Framework e o Visual Studio, o projeto foca na criação de uma classe `BankAccount` que oferece funcionalidades básicas como crédito e débito, além de garantir que as operações sejam realizadas de forma segura e dentro das regras de negócio estabelecidas.

## Tecnologia Utilizada

- **Linguagem de Programação**: C#
- **Framework**: .NET (especificamente o .NET 8.0)
- **Ambiente de Desenvolvimento**: Visual Studio
- **Framework de Teste**: MSTest para a criação e execução de testes de unidade

- 
## Código
Depois de adicionar o codigo em Bank.cs e buildar o resultado foi:
![image](https://github.com/CFFricks/ponderada-dotnet/assets/99102201/e08c36fd-b2c4-47b5-9fbf-a438128eecd6)
<br/>
Apos a criação do projeto BankTests estou adicionando a referencia para o projeto Banks:
![image](https://github.com/CFFricks/ponderada-dotnet/assets/99102201/b2a43e4d-3311-48e6-9a5a-4d78209f359e)
<br/>
Depois de criar um TestMethod e corrigir a linha que estava errada no Program.cs:
![image](https://github.com/CFFricks/ponderada-dotnet/assets/99102201/b08576c9-bcca-4dc7-8582-d62bf828df2a)
<br/>
Criando o TestMethod Debit_WhenAmountIsMoreThanBalance_ShouldTrowArgumentOutOfRange:
![image](https://github.com/CFFricks/ponderada-dotnet/assets/99102201/17a90c3d-2930-417a-b911-a24727ee3ff9)
E testando se ele esta funcionando:
![image](https://github.com/CFFricks/ponderada-dotnet/assets/99102201/ed1ae686-c28b-4592-a457-d55d50974175)
<br/>
Depois de alterar todo o codigo aqui esta ele rodando e passando:
![image](https://github.com/CFFricks/ponderada-dotnet/assets/99102201/0e449034-3720-4411-8292-108219c95048)

# Conceitos Aprendidos:
Os testes de unidade são essenciais porque garantem que cada componente do software funcione corretamente isoladamente. Isso ajuda a prevenir bugs, facilita a manutenção do código e suporta o desenvolvimento ágil através de feedback imediato sobre mudanças recentes.

## 1. Testes de Unidade

Testes de unidade são técnicas de verificação de software que validam a correção das menores partes testáveis de uma aplicação, como funções ou métodos. O objetivo é assegurar que cada unidade funcione conforme esperado isoladamente, contribuindo para a confiabilidade do sistema como um todo.

## 2. MSTest Framework

O MSTest é a estrutura de teste de unidade integrada ao Visual Studio para aplicações .NET, oferecendo uma série de funcionalidades para criar, executar e avaliar testes de unidade. Através de atributos e métodos específicos, facilita a identificação de métodos de teste, preparação de recursos, e mais.

## 3. Asserts

Assertivas são usadas em testes de unidade para validar condições específicas no código. O MSTest provê métodos `Assert` que permitem verificar diferentes condições, como igualdade de valores e lançamento de exceções, sendo cruciais para determinar se o código se comporta como esperado.

## 4. Exceções e Tratamento de Erros

O tratamento adequado de exceções e erros é vital, especialmente em aplicações críticas como as financeiras. No projeto `Bank`, vimos como importantes é garantir que operações inválidas sejam bloqueadas por meio de exceções, e testar esses comportamentos assegura a estabilidade e segurança da aplicação.

## 5. Isolamento de Testes

Manter testes isolados uns dos outros é crucial para a independência dos testes. Isso é alcançado configurando e limpando o estado necessário para cada teste, garantindo que falhas sejam fáceis de diagnosticar, pois cada teste é responsável por um único aspecto ou cenário da funcionalidade.

## 6. Desenvolvimento Guiado por Testes (TDD)

O conceito de Desenvolvimento Guiado por Testes, embora não explicitamente mencionado, é sugerido ao criar testes antes do código funcional. TDD promove um melhor design de software e assegura que o software atenda aos requisitos desde o início, guiando o desenvolvimento com testes.

