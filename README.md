# Desafio Técnico Full-stack

Projeto desenvolvido para o processo seletivo da Appmax.
> Documentação: [https://documenter.getpostman.com/view/19595551/UVkvJsNM](https://documenter.getpostman.com/view/19595551/UVkvJsNM)

## Criar uma API para realizar as seguintes ações:

- Cadastro de produtos com os seguintes campos obrigatórios.
- Movimentação de produtos.
- Histórico.

## Tecnologias utilizadas

- **PHP**: 8.1.3
- **Laravel**: 9.3.1
- **Composer**: 2.2.7
- **Node**: v16.13.2
- **NPM**: 8.5.3

## Instalação
> Antes de iniciar, crie um banco de dados. Neste exemplo estamos utilizando o nome app-7rz2ot9w, mas fica a vontade para usar o nome que preferir.

*1. Clonar repositório*
```
git clone https://github.com/Colorio/app-7rz2ot9w.git
```
*2. Acessar pasta do projeto*
```
cd app-7rz2ot9w.git
```
*3. Criar arquivo .env (Windows | macOS - Linux)*
```
copy .env.example .env | cp .env.example .env
```
*4. Intalar*
```
composer install
```
*5. Executar as migrations*
```
php artisan migrate
```