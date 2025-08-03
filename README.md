# Site MB Estética Avançada

Este é o repositório do site oficial da clínica MB Estética Avançada. O site foi desenvolvido com HTML, CSS e JavaScript, utilizando o framework Bootstrap para responsividade e componentes.

## Estrutura do Projeto

```
.
├── index.html                 # Página principal
├── css/
│   └── style.css              # Arquivo de estilos personalizados
├── js/
│   └── main.js                # Arquivo de scripts personalizados
├── images/                    # Pasta para imagens do site
├── procedimentos/             # Pasta com páginas individuais dos procedimentos
│   └── botox.html             # Exemplo de página de procedimento
└── README.md                  # Este arquivo
```

## Como Visualizar o Site Localmente

### Opção 1: Servidor Local com Python (Recomendado)

Se você tiver o Python instalado, pode iniciar um servidor local facilmente:

1. Abra o terminal/prompt de comando.
2. Navegue até o diretório raiz deste projeto.
3. Execute o seguinte comando:

   **Para Python 3:**
   ```bash
   python -m http.server 8000
   ```

   **Para Python 2:**
   ```bash
   python -m SimpleHTTPServer 8000
   ```

4. Abra seu navegador e acesse `http://localhost:8000`.

### Opção 2: Extensão Live Server no VS Code

Se estiver usando o Visual Studio Code:

1. Instale a extensão "Live Server" (ritwickdey.LiveServer).
2. Clique com o botão direito no arquivo `index.html`.
3. Selecione "Open with Live Server".

## Configurações Adicionais

### Integração com Calendly

Para configurar o agendamento online:

1. Acesse [Calendly](https://calendly.com/) e crie uma conta.
2. Configure seus horários e tipos de consulta.
3. Copie o link do seu agendamento.
4. No arquivo `index.html`, localize a div com a classe `calendly-inline-widget`.
5. Substitua o valor do atributo `data-url` pelo seu link do Calendly.

### Integração com Instagram

Para exibir o feed do Instagram:

1. Acesse [LightWidget](https://lightwidget.com/) e crie uma conta.
2. Conecte sua conta do Instagram.
3. Personalize o widget conforme desejado.
4. Copie o código fornecido.
5. No arquivo `index.html`, localize o iframe com a classe `lightwidget-widget`.
6. Substitua o `src` do iframe pelo código fornecido pelo LightWidget.

### Botão WhatsApp

Para configurar o botão de contato via WhatsApp:

1. Substitua o número de telefone no link do botão.
2. No arquivo `index.html`, localize o link com a classe `whatsapp-float`.
3. Altere o número no atributo `href` para o seu número de WhatsApp no formato internacional (ex: `https://wa.me/5511999999999`).

## Tecnologias Utilizadas

- **HTML5**
- **CSS3**
- **JavaScript**
- **Bootstrap 5**
- **Google Fonts**
- **Bootstrap Icons**

## Otimizações para SEO

O site foi desenvolvido com boas práticas de SEO em mente:

- Meta tags descritivas
- Estrutura semântica adequada
- Palavras-chave relevantes
- Imagens com atributos `alt`

## Responsividade

O site é totalmente responsivo e se adapta a diferentes tamanhos de tela, graças ao Bootstrap e aos media queries personalizados no `style.css`.

## Contribuição

Se desejar contribuir para o desenvolvimento do site:

1. Faça um fork deste repositório
2. Crie uma branch para sua feature (`git checkout -b feature/nova-feature`)
3. Commit suas mudanças (`git commit -am 'Adiciona nova feature'`)
4. Faça push para a branch (`git push origin feature/nova-feature`)
5. Abra um Pull Request

## Deploy

Para fazer o deploy do site, você pode utilizar serviços como:

- **GitHub Pages** (gratuito)
- **Netlify** (gratuito)
- **Vercel** (gratuito)
- **Hostinger**
- **GoDaddy**

Basta fazer upload dos arquivos do projeto para o seu serviço de hospedagem escolhido.

## Licença

Este projeto é de propriedade da MB Estética Avançada. Todos os direitos reservados.
