## Projeto sistema administrativo da plataforma e-diaristas

Desenvolvido no curso de Multi-stack da Treinaweb

## Instalado o projeto

#### Clonar o repositório

```
git clone https://github.com/CarlRsd/multistack-sistema-administrativo-ediaristas.git
```

#### Instalar as dependências

```
composer install
```

Ou em ambiente de desenvolvimento:

```
composer update
```

#### Criar arquivo de configurações de ambiente

Copiar o arquivo de exemplo `.env.example` para `.env` na raiz do projeto e em seguida configurar os detalhes de configuração da aplicação e do banco de dados.

#### Criar a estrutura no banco de dados

```
php artisan migrate
```

#### Iniciar o servidor de desenvolvimento

```
php artisan serve
```
