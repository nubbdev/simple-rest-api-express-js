# Simple Rest API with Express JS
Simple Rest API with Express JS and MySQL


Another dependencies included :
- body-parser
- dotenv


Configuration :
1. git clone https://github.com/nubbdev/simple-rest-api-express-js.git
2. Create database and run query below
```
CREATE TABLE IF NOT EXISTS `users` (
  `id` int(11) NOT NULL AUTO_INCREMENT,
  `first_name` varchar(50) NOT NULL DEFAULT '0',
  `last_name` varchar(50) NOT NULL DEFAULT '0',
  PRIMARY KEY (`id`)
)
```
3. Change your db on .env config files
4. Run command below (your position should in the clone directory)
```
node serve.js
```
Happy coding ༼ つ ◕_◕ ༽つ
