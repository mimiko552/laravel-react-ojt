# laravel-react-ojt

1.Cloning project to PC

`=> git clone https://github.com/mimiko552/laravel-react-ojt.git`

2.Pull source from feature/mmk/20210629/pj-base

`=> cd laravel-react-ojt`

`=> git pull origin feature/mmk/20210629/pj-base`
 
3.Composer Install

`=> php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"`

`=> php -r "if (hash_file('sha384', 'composer-setup.php') === '756890a4488ce9024fc62c56153228907f1545c228516cbf63f885e036d37e9a59d27d63f46af1d4d07ee0f76181c7d3') { echo 'Installer verified'; } else { echo 'Installer corrupt'; unlink('composer-setup.php'); } echo PHP_EOL;"`

`=> php composer-setup.php`

`=> php -r "unlink('composer-setup.php');"`

`=> sudo mv composer.phar /usr/local/bin/composer`

`=> composer install`

4.Create/start container in docker

`=> docker-compose up -d`

5.Enter to PHP container & Laravel App and run migrate command

`=> docker-compose exec app bash`

`=> cd lararavel-app`

`=> php artisan migrate`

6.Run laravel app on browser

`http://localhost:8000/`

7.Running React App 

`=> cd ..`

`=> cd react-app`

`=> npm install`

`=> npm start`

8.Run React app on browser

`http://localhost:3000/`
