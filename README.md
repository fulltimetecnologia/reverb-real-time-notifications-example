###

Vamos usar um driver de reverb para enviar notificações em tempo real usando o servidor Echo no projeto Laravel 11.

O que é Reverb?

Laravel Reverb traz comunicação em tempo real via WebSocket super rápida e escalável diretamente para a sua aplicação Laravel, e oferece integração perfeita com o conjunto existente de ferramentas de transmissão de eventos do Laravel.

# Versões

- php 8.3
- npm 10.7.0
- node v18.20.4

# Executar

```bash
php artisan serve
```

```bash
php artisan reverb:start
```

```
http://localhost:8000/
```

### 

Aqui está o que foi feito nesse exemplo:

1. Criação de uma estrutura de autenticação usando Laravel UI.

2. Configuração de dois tipos de usuários: um super admin e um usuário comum. Identificados por uma coluna "is_admin" na tabela de usuários.

3. Criação de uma tabela de posts com colunas para o título e o corpo.

4. Permitir que os usuários criem posts com título e corpo.

5. Assim que um post for criado, o admin receberá uma notificação em tempo real usando o Reverb. Vamos criar o evento PostCreate para enviar a notificação em tempo real.

Passo para Exemplo de Notificação em Tempo Real com Laravel 11 Reverb  

Passo 1: Instalar o Laravel 11  
Passo 2: Criar Autenticação usando Scaffold  
Passo 3: Criar Migrations  
Passo 4: Criar e Atualizar Models  
Passo 5: Configurar o Servidor Reverb & Echo  
Passo 6: Criar Evento PostCreate  
Passo 7: Criar Rotas  
Passo 8: Criar Controller  
Passo 9: Criar e Atualizar Arquivos Blade
Passo 10: Criar Usuário Admin

Executar App Laravel
