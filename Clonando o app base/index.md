---
layout: page
title: Clonando o app base
nav_order: 3
has_children: true
permalink: /cloning/home/
---

# Clonando o app base

Neste ponto, o qual o modelo já está preparado, é possível dar continuidade ao trabalho com este exemplo.

O app base a ser utilizado está em um repo público: [autodesk-platform-services/aps-iot-extensions-demo](https://github.com/autodesk-platform-services/aps-iot-extensions-demo)

Para começar a trabalhar com ele há opções como clonar ou realizar download como zip, por exemplo.

Para simplificar o gerenciamento e armazenar as alterações, é recomendado trabalhar com um fork desse repo

![Fork IOT Sample](../../assets/images/fork_sample.gif)

Com a própria versão configurada, pode-se seguir o passo a passo do [README](https://github.com/JoaoMartins-callmeJohn/aps-iot-extensions-demo#running-locally) e clonar o exemplo (no gif abaixo foi utilizado o [GitHub Desktop](https://desktop.github.com))

![clone IOT Sample](../../assets/images/clone_app.gif)

Basicamente, deve-se:

- Instalar as dependências com `yarn install`

![install IOT Sample](../../assets/images/yarn_install.gif)

- Definir as variáveis de ambiente de acordo com seu app APS (`APS_CLIENT_ID` e `APS_CLIENT_SECRET`)

- Iniciar o exemplo com o comando `yarn start`

Dessa forma, será possível verificar o app navegando até http://localhost:3000

![localhost 3000](../../assets/images/localhost_3000.png)

O exemplo está funcionando, porém ainda falta ajustar os dados (modelo e sensores).

Esse passo será realizado na próxima etapa

[Próximo passo - Adaptando aos seus dados]({{ site.baseurl }}/adapting/home/){: .btn}
