# Descrição
Sistema de venda de ingressos para um show de rock extremamente popular. O sistema é projetado para gerenciar o alto volume de acessos, garantindo que os usuários tenham uma experiência justa e eficiente. A arquitetura é baseada em microserviços, permitindo escalabilidade e manutenção simplificada.

## Funcionalidades
- Autenticação de Usuário: Registro e login de usuários.
- Gerenciamento de Ingressos: Verificação e venda de ingressos.
- Notificações: Envio de notificações sobre o status da compra.
- Gerenciamento de Filas: Controle da fila de usuários para compra de ingressos.

## Casos de uso
1. Login
   - Usuário insere suas credenciais para acessar o sistema.
2. Entrar na Fila Virtual
   - Usuário é colocado em uma fila virtual para garantir a ordem de compra justa.
3. Comprar Ingresso
   - Usuário seleciona e tenta comprar o ingresso.
4. Verificar Disponibilidade de Ingressos
   - Sistema verifica no banco de dados se ainda há ingressos disponíveis antes de permitir a compra.
5. Confirmar Compra
   - Sistema confirma a compra, desconta o ingresso do banco de dados e gera a confirmação de pagamento.
6. Notificar Usuário
   - Usuário é notificado sobre o status da compra.

## Diagrama de sequência
<img src="diagram de sequência.png"/>
