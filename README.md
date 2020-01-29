# Jest Playground

O Jest é um _test runner_ de JavaScript, ou seja, uma biblioteca JavaScript para criar, executar e estruturar testes. Ele é distribuído como um pacote NPM, você pode instalá-lo em qualquer projeto JavaScript. Jest é um dos _test runner_ mais populares atualmente e a opção padrão para o _Create React App_.

## Tipo de teste abordado

**Teste de unitário**: Teste de unidade é toda a aplicação de teste nas assinaturas de entrada e saída de um sistema. Consiste em validar dados válidos e inválidos via I/O sendo aplicado por desenvolvedores ou analistas de teste. Uma unidade é a menor parte testável de um programa de computador.

## Configurando Jest

**Requesitos**:

- Node instalado ( para utilizar o npm )

**1 passo:** Crie uma pasta que irá utilizar o jest, entre nesta pasta e crie um package para iniciar seu projeto.

    ex: `mkdir jest_test && cd jest_test && npm init -y`

**2 passo:** Instale o Jest como uma dependência de desenvolvimento em seu projeto

    `npm i -D jest`

**3 passo:** Crie ou edite um script para executar o teste em seu projeto. Abra o arquivo package.json e adicione/edite o seguinte trecho:

```javascript
    "scripts": {
    "test": "jest"
    }
```

***4 passo:*** Por convenção custuma-se criar os testes em jest na pasta __test__, utilize o comando abaixo para criar essa pasta:

    `mkdir __tests__`

***OK! Tudo pronto. Vamos lá !***

os exemplos de códigos estão no repositório