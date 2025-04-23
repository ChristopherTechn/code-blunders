On 22-04-2025 - Node.js

ERROR:
So this is the error which I faced when creating migrations for my CLIMATE CHANGE PROJECT. 

Sequelize CLI [Node: 20.12.0, CLI: 6.6.2, ORM: 6.37.7]

Loaded configuration file "config\config.json".
Using environment "development".

ERROR: The "data" argument must be of type string or an instance of Buffer, TypedArray, or DataView. Received type number #####


So I FIXED the error by, ensuring that the password in the config.js is also wrapped in quatation marks.
The other error related to migrations was that when creating the migrations, is that you can not run a table which has a foreign key before you create the initial table. 

