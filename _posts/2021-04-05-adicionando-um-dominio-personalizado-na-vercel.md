---
layout: post
title: Adicionando um domínio personalizado na Vercel
date: '2021-04-05 01:53:11'
subtitle: ...com Google Domains
categories: [web]
---
Pra quem ainda não conhece a [Vercel](https://vercel.com/) e já conhece a [Netlify](https://www.netlify.com/) não tenho muito o que dizer, as duas fazem basicamente a mesma coisa, hospedam sites estáticos com deploy automático. Eu achei a interface da segunda mais bonita mas a primeira é mais fácil de "deployar", porém as diferenças são mínimas, eu escolhi a [Vercel](https://vercel.com/) para servir esse blog simplesmente porque está na moda. 🤷‍♂️

O registrar desse tutorial será o [Google Domains](https://domains.google/intl/pt-BR_br/) pois foi onde registrei esse meu domínio, na época se bem me lembro somente o Google registrava domínios .dev, o processo é muito simples, mas mesmo assim vou tentar facilitar mais ainda.

## Adicionando seu domínio próprio

Assim que fazemos um deploy na [Vercel](https://vercel.com/) recebemos um endereço completamente aleatório para acessarmos nosso site, não queremos isso, queremos acessar através do nosso domínio bonitinho 🥰, para isso precisamos dentro da plataforma da [Vercel](https://vercel.com/) fazer os seguintes passos:

### ➡️ 1. Selecione seu projeto

![vercel](/assets/images/image-1.png)

### ➡️ 2. Navegue para `Settings`

![vercel](/assets/images/image-2.png)

### ➡️ 3. Selecione o ítem `Domains` no menu ao canto esquerdo

![vercel](/assets/images/image-3.png)

### ➡️ 4. Adicione seu domínio

![vercel](/assets/images/image-4.png)

### ➡️ 5. Configure o redirecionamento
Você verá um pop-up como esse:

![vercel](/assets/images/image-5.png)

No meu caso como eu quero que o domínio sem o alias **www** seja o padrão do meu site eu escolhi a segunda opção, você também pode escolher a terceira opção e decidir isso mais tarde.

### ➡️ 6. Configurando os nameservers

Você verá uma tela como essa:

![vercel](/assets/images/image-6.png)

clique na aba `Nameservers` e copie os endereços fornecidos.

Caso seu domínio seja novo você verá algo parecido com isso:

![google-domains](/assets/images/image-7.png)

clique em **Usar servidores personalizados de nome**.
Cole no campo os dois endereços fornecidos pela [Vercel](https://vercel.com/) e clique em **Salvar**.

### ➡️ Conclusão

Foi tudo muito simples né? Depois desses passos você vai perceber que a [Vercel](https://vercel.com/) fica atualizando a verificação do seu domínio, quando você perceber a frase **Valid Configuration** significa que deu tudo certo e seu domínio está configurado, possa ser que ele demore um pouco para propagar o que é comum, o meu levou várias horas para propagar no Brasil, eu usei a ferramenta [whatsmydns.net](https://www.whatsmydns.net/) para fazer as verificações, mas não precisa ser ansioso como eu, deixa rolar, se você seguiu todos os passos em breve seu site estará no ar com o seu domínio próprio.

![CANALTVDIAMONDTEEN-feliz-oba-treta-via-giphy](https://media.giphy.com/media/CPyK0LpgSUytcTX8Bm/giphy.gif)

**Referências**:

- [Custom Domains - Vercel Documentation](https://vercel.com/docs/custom-domains#)