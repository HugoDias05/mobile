## Descrição
Aplicação simples, pensando na praticidade do usuário para o dia a dia. Com design agradável e pensando na User Experience, o aplicativo conta com página de detalhamento de notícias, filtro por categoria e opção para salvar as notícias para ler offline pelo cache.


## INSTALAÇÃO DO REPOSITÓRIO
1. Após feita a clonagem do repositório, instale as dependências.
 ```sh
   npm install
   ```
2. Insira sua chave VAPID do firebase console no arquivo "Notification.service.ts" para utilização local.
3. Execute o comando "ionic serve" para iniciar o servidor e acessar a aplicação pelo navegador.
 ```sh
   ionic serve
   ```
4. Execute o comando "node server.js" para iniciar o backend da aplicação.
 ```sh
   node server.js
   ```

## PRE-REQUISITOS
1. Node.js
2. Ionic
3. Firebase
4. VAPID Key (para notificações push)

## Como contribuir

1. Faca um Fork no projeto
2. Crie sua branch (`git checkout -b nome da branch`)
3. adicione suas alteracoes (`git add.`)
4. Commitar suas mudancas (`git commit -m 'upando arquivos restantes'`)
5. Push do branch (`git push origin nome da branch`)
6. Open a Pull Request 