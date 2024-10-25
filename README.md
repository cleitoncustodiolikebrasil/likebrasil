{
  "version": "1.0",
  "id": "typebot_flow_like_brasil",
  "name": "Like Brasil Bot",
  "description": "Bot de apresentação do negócio Like Brasil",
  "nodes": {
    "start": {
      "type": "message",
      "content": "Olá, meu nome é Cleiton Custodio 👋\nSou Líder Fundador de Negócios da Like Brasil e quero te explicar como você pode melhorar sua saúde de forma natural e ainda ganhar uma renda extra!\nQuantas pessoas você conhece que precisam de saúde e querem uma renda extra? 🤔",
      "actions": [
        {
          "label": "Mais de 3 pessoas",
          "type": "next",
          "target": "mais_de_tres"
        },
        {
          "label": "Mais de 5 pessoas",
          "type": "next",
          "target": "mais_de_cinco"
        }
      ]
    },
    "mais_de_tres": {
      "type": "message",
      "content": "Já pensou em ganhar dinheiro ajudando essas pessoas a melhorar a saúde de dentro para fora? 🌱💸\nNa Like Brasil, você pode criar uma renda extraordinária MESMO SEM VENDER NADA!\nSó precisa de um celular 📱 e disposição para compartilhar saúde e bem-estar!\nQuer saber como isso funciona? 🤔",
      "actions": [
        {
          "label": "SIM, QUERO SABER MAIS!",
          "type": "next",
          "target": "como_funciona"
        },
        {
          "label": "NÃO, OBRIGADO.",
          "type": "end"
        }
      ]
    },
    "mais_de_cinco": {
      "type": "message",
      "content": "Já pensou em ganhar dinheiro ajudando essas pessoas a melhorar a saúde de dentro para fora? 🌱💸\nNa Like Brasil, você pode criar uma renda extraordinária MESMO SEM VENDER NADA!\nSó precisa de um celular 📱 e disposição para compartilhar saúde e bem-estar!\nQuer saber como isso funciona? 🤔",
      "actions": [
        {
          "label": "SIM, QUERO SABER MAIS!",
          "type": "next",
          "target": "como_funciona"
        },
        {
          "label": "NÃO, OBRIGADO.",
          "type": "end"
        }
      ]
    },
    "como_funciona": {
      "type": "message",
      "content": "Vou te contar como funciona nossa Rede de Consumo Inteligente 🤩\nMas antes, deixa eu me apresentar melhor. Meu nome é Marcellus Franco, tenho mais de 10 anos de experiência e já ajudei muitas pessoas a conquistar a independência financeira!\nAgora, veja como funciona nossa oportunidade:\n\n👉 **Vantagem 1:** Consumidores inteligentes recebem **50% de desconto** em todos os nossos produtos incríveis, como nutracêuticos, óleos ozonizados e produtos capilares.\n👉 **Vantagem 2:** Ao indicar 3 consumidores, você participa do **Bônus Global**, ganhando até **R$40** por nível de indicação, com potencial para uma renda incrível em poucos meses.\n👉 **Vantagem 3:** Além de dinheiro, você pode ganhar **prêmios, viagens e reconhecimento** na Like Brasil!",
      "actions": [
        {
          "label": "SIM, QUERO FAZER PARTE!",
          "type": "next",
          "target": "parte_rede"
        },
        {
          "label": "NÃO, OBRIGADO.",
          "type": "end"
        }
      ]
    },
    "parte_rede": {
      "type": "message",
      "content": "Incrível! 🤩 Vou te contar como funciona nossa proposta especial:\nEstou formando uma equipe de empreendedores de sucesso, e você pode ser um dos meus indicados diretos!\nJuntos, podemos construir uma renda acima de **R$5.000 por mês** em poucos meses!\nQuanto você acha que vale essa oportunidade de ganhar 5 mil ou mais todos os meses? 🤔",
      "actions": [
        {
          "label": "Uns R$2.000",
          "type": "next",
          "target": "valor_negocio"
        },
        {
          "label": "Uns R$5.000",
          "type": "next",
          "target": "valor_negocio"
        }
      ]
    },
    "valor_negocio": {
      "type": "message",
      "content": "Agora, a boa notícia:\n👉 O investimento é muito menor do que você imagina!\nVocê vai precisar investir apenas **R$500,00** em produtos, e o melhor: você paga **APENAS R$250** com nosso desconto de consumidor inteligente! 😱🤑\nE nem precisa pagar agora! Você pode fazer seu cadastro GRATUITO primeiro e depois agendar sua primeira compra quando for mais conveniente para você.\n\nVamos fazer seu **cadastro gratuito** agora? 🎁",
      "actions": [
        {
          "label": "SIM, QUERO CADASTRAR!",
          "type": "next",
          "target": "cadastro"
        },
        {
          "label": "NÃO, OBRIGADO.",
          "type": "end"
        }
      ]
    },
    "cadastro": {
      "type": "message",
      "content": "Perfeito! Vamos começar. Para iniciar o cadastro, você será direcionado para nossa loja interna, onde poderá ver todos os nossos produtos e agendar seu primeiro pedido.\n\nA seguir, você receberá uma mentoria exclusiva comigo, onde vou te ensinar como captar contatos pelo Brasil inteiro usando o digital com custo **zero**! 🚀\nClique no link abaixo para iniciar seu cadastro gratuito agora:\n[LINK DE CADASTRO]\nSe tiver alguma dúvida, clique aqui para falar diretamente comigo no WhatsApp:\n[LINK PARA WHATSAPP]",
      "actions": [
        {
          "label": "FINALIZAR",
          "type": "end"
        }
      ]
    },
    "end": {
      "type": "message",
      "content": "Obrigado por entrar em contato! Se tiver mais alguma dúvida, estarei por aqui. 😊",
      "actions": []
    }
  }
}
