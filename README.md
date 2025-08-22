gem install rails
rails new meu_projeto
rails generate controller Welcome
Rails.application.routes.draw do
  get '/welcome', to: 'welcome#index'
end
rails server

# config/routes.rb
Rails.application.routes.draw do
  get '/welcome', to: 'welcome#index'
end
