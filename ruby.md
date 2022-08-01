**DATABASE COMMANDS
rails generate model DocumentVersion executed:boolean document:belongs_to
rake db:rollback STEP=2
rake db:migrate


**GRAPHQL
rake graphql:dump_schema // this will destroy and recreate schema.graphql
rails generate graphql:object user // generates user_type.rb
