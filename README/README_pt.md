# Flask Web Application - Sistema de gerenciamento de sites corporativos (versão criptografada)

## Introdução ao Projeto

Esta é uma **versão criptografada** de um sistema de gerenciamento de sites corporativos desenvolvido com base na estrutura Flask.O código principal foi ofuscado e criptografado pelo PyArmor para proteger os direitos de propriedade intelectual.O sistema oferece suporte a vários idiomas (chinês e inglês), autenticação de usuário, gerenciamento de produtos e notícias, exibição de informações da empresa e outras funções.

## Captura de tela do aplicativo

A seguir está uma captura de tela da interface principal do aplicativo:

### Casa
![首页](screenshots/index.png)

### Histórico de gestão
![管理后台](screenshots/admin_dashboard.png)

## Notas de versão

Esta versão é uma versão básica de criptografia que fornece funções completas de gerenciamento de sites corporativos.Se você precisar:

- **Versão completa do código-fonte**: Contém código-fonte completo não criptografado para facilitar o desenvolvimento secundário
- **Desenvolvimento de Funções Personalizadas**: Personalização e expansão de funções de acordo com suas necessidades específicas
- **Serviços de suporte técnico**: obtenha suporte técnico profissional e serviços de manutenção

Entre em contato conosco através das informações de contato abaixo e forneceremos planos e orçamentos detalhados.

## Recursos de criptografia

- **Proteção de código**: os arquivos principais do Python (app.py, init_db.py, models.py) são ofuscados e criptografados
- **Proteção de tempo de execução**: use o ambiente de tempo de execução PyArmor para evitar que o código seja descompilado
- **Funcionalidade completa**: O código criptografado mantém todas as funcionalidades e recursos originais
**Suporte multilíngue**: função de comutação integrada em chinês e inglês

## Incluir arquivos

```
/
├── app.py                  # Entrada criptografada do aplicativo principal
├── init_db.py              # Script de inicialização de banco de dados criptografado
├── models.py               # Modelos de dados criptografados
├── babel.cfg               # Configuração de internacionalização Babel
├── pyarmor_runtime_000000/ # Arquivos de suporte ao tempo de execução do PyArmor
├── static/                 # Arquivos de recursos estáticos (CSS, JS, imagens)
├── templates/              # Arquivos de modelo HTML
├── translations/           # Arquivos de tradução multilíngue
└── instance/               # Diretório do banco de dados (criado automaticamente na primeira execução)
```

## Início rápido

### Requisitos ambientais

- Python 3.9 ou superior
- Pacotes de dependência instalados:
- Frasco 3.0.0+
- Flask-SQLAlchemy 3.1.1+
- Login do frasco 0.6.3+
- Frasco-Babel 4.0.0+
- Trabalho 3.0.1+

### Instalar dependências

Se as dependências necessárias ainda não estiverem instaladas, instale-as primeiro:

```bash
pip install flask flask-sqlalchemy flask-login flask-babel werkzeug
```

### Execute o aplicativo

1. **Inicializar banco de dados**

Antes de executar pela primeira vez, o banco de dados precisa ser inicializado:

```bash
   python init_db.py
   ```

2. **Inicie o aplicativo**

__CODE_BLOCO_3__

3. **Acessar aplicativo**

Abra o navegador e visite: http://127.0.0.1:5000

## Instruções de uso

### Visite o site

1. Abra o navegador e visite http://127.0.0.1:5000
2. Use o botão de troca de idioma no canto superior direito para alternar entre chinês e inglês

### Histórico de gestão

1. Visite http://127.0.0.1:5000/admin/login
2. Faça login com a conta de administrador (nome de usuário e senha padrão: admin/admin123)
3. Produtos, notícias e informações da empresa podem ser gerenciados no background da gestão

## Descrição da função

### Funções de front-end

- **Home**: Exibir perfil da empresa e principais produtos
- **Sobre nós**: mostre detalhes da empresa
- **Exibição de produtos**: navegue em todas as listagens de produtos
- **Atualizações do setor**: veja as últimas notícias e informações
- **Troca de idioma**: suporta a troca entre chinês e inglês

### Gerenciar funções em segundo plano

- **Gerenciamento de produtos**: adicione, edite, exclua produtos
- **Gerenciamento de notícias**: publique, edite, exclua notícias
- **Informações da empresa**: atualize informações básicas da empresa
- **Autenticação de usuário**: sistema de login seguro

## Guia de captura de tela

Para obter o melhor efeito de exibição do README, é recomendado criar e adicionar capturas de tela de acordo com as seguintes diretrizes:

1. **Criar pasta de capturas de tela**: Crie a pasta `screenshots/` no diretório `dist/`
2. **Tamanho da captura de tela**: use uma captura de tela com resolução de 1920x1080 ou 1366x768 para garantir que o conteúdo esteja claramente visível
3. **Conteúdo da captura de tela**:
- Página inicial: exibe a interface completa da página inicial, incluindo barra de navegação e área de conteúdo principal
- Troca de idioma: mostra o efeito comparativo da troca entre chinês e inglês (podem ser usadas capturas de tela em tela dividida)
- Exibição de produtos: exibe lista de produtos e detalhes de produtos individuais
- Página de notícias: exibe lista de notícias e detalhes de notícias
- Backend de gerenciamento: exibe o painel e a interface funcional após o login do administrador
4. **Formato de captura de tela**: use o formato PNG para obter melhor qualidade
5. **Nomeação de arquivo**: Salve a captura de tela de acordo com o nome do arquivo especificado no README (index.png, language_switch.png, etc.)

## Notas

1. **Integridade do Arquivo**: Certifique-se de que todos os arquivos foram baixados corretamente, especialmente o diretório `pyarmor_runtime_000000` e seu conteúdo

2. **Arquivo de banco de dados**:
- O arquivo do banco de dados será criado automaticamente no diretório `instance`
- Se você precisar fazer backup de dados, faça backup do arquivo `instance/site.db` regularmente

3. **Suporte multilíngue**:
- Todos os arquivos de tradução estão incluídos no diretório `translations`
- Para adicionar novos idiomas de tradução, consulte a documentação original do projeto

4. **Ambiente operacional**:
- Certifique-se de que a versão do Python não seja inferior a 3.9
- Certifique-se de que todas as dependências necessárias estejam instaladas

5. **Dicas de segurança**:
- Ao implantar em um ambiente de produção, altere a senha de administrador padrão.
- Considere usar um servidor WSGI (como Gunicorn) em vez do servidor de desenvolvimento
- Configure regras de firewall apropriadas

## Recomendações de implantação

### Ambiente de desenvolvimento

Use o servidor de desenvolvimento integrado Flask (mostrado no início rápido acima).

### Ambiente de produção

1. **Usar servidor WSGI**:
```bash
   pip install gunicorn
   gunicorn -w 4 -b 0.0.0.0:8000 app:app
   ```

2. **Use proxy reverso**:
- Configure Nginx ou Apache como proxy reverso
- Configure o certificado SSL para ativar HTTPS

3. **Otimização do banco de dados**:
- Considere usar PostgreSQL ou MySQL em vez de SQLite
- Configurar mecanismo de backup regular

## Solução de problemas

### Perguntas frequentes

1. **O aplicativo não pode ser iniciado**:
- Verifique se a versão Python atende aos requisitos
- Confirme se todos os pacotes dependentes estão instalados corretamente
- Verifique se o diretório `pyarmor_runtime_000000` existe e está completo

2. **A troca de idioma não funciona**:
- Confirme se o diretório `translations` e seu conteúdo estão completos
- Verifique se as configurações de cookies do navegador são permitidas

3. **Erro de conexão com banco de dados**:
- Confirme se o diretório `instance` existe e tem permissões de gravação
- Tente executar novamente `init_db.py` para inicializar o banco de dados

### Visualização de registro

Quando o aplicativo for iniciado, as informações de log serão exibidas no console.Se você encontrar problemas, poderá verificar esses logs para obter mais informações.

## Licença

[MIT License](LICENSE)

## Informações de contato

Se você tiver alguma dúvida, sugestão ou precisar de desenvolvimento de versão completa/função personalizada, entre em contato através dos seguintes métodos:

- **E-mail**: austinlive666@gmail.com (recomendado)
- **Discordância**:[https://discord.gg/7AN9PuGn](https://discord.gg/7AN9PuGn)

---

Obrigado por usar este projeto!