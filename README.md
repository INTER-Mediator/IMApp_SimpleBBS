# IMApp_SimpleBBS
Simple BBS Web Application with Using INTER-Mediator.

This is a part of the hands-on session to study INTER-Mediator, but you don't have to work, and all codes are prepared on this repository. If you want to check the contents of the session, the url below is documentation (Japanase).

https://qiita.com/motofumi/items/57583c2b28d0d11a1a9d

# Preparation
Installing PHP, git, composer, MySQL and Node.js with npm.

The database has to be prepared with the following schema which is the sample db of the INTER-Mediator. If you already try to use the INTER-Mediator, this sample db has to be setup.

https://raw.githubusercontent.com/INTER-Mediator/INTER-Mediator/master/dist-docs/sample_schema_mysql.txt

# Setup
This web app based on the composer. So you clone this repository, following to execute the composer command on the root of the repository.
```
git clone https://github.com/inter-mediator/IMApp_SimpleBBS
cd IMApp_SimpleBBS
composer update
```

## Getting Started App
The quick way to host the web app, the php command's server mode is convenient.
```
php -S localhost:9000
```
After that, you can access the application with url http://localhost:9000/ from any browser that executing on the same host.
