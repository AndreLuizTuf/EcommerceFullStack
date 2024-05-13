# README





Coisas que você pode querer abordar:

* Ruby versão
`3.2.2`

* Configuração
Adicione suas variáveis de ambiente ao arquivo `config/credentials.yml.enc`. Você pode fazer isso executando `bin/rails credenciais:edit`

* Criação de Database 
Localmente usamos sqlite3 como nosso banco de dados. Isso já está configurado para você. Na produção, certifique-se de que sua variável env `DATABASE_URL` esteja definida. Usamos PostgreSQL na produção.

* Iniciar o Database 
execute `bin/rails db:migrate` para criar as tabelas

* Tailwind configuração  
run bundle exec rake assets:precompile

* Instrução de Deploy
Implantamos no Render crie uma conta gratuita aqui render.com

