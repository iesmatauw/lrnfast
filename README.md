# FastAPI CRUD using Async, Alembic & Postgresql

<p>
  <img alt="Version" src="https://img.shields.io/badge/version-0.1.0-blue.svg?cacheSeconds=2592000" />
  <a href="https://twitter.com/wedwardbeck" target="_blank">
    <img alt="Twitter: wedwardbeck" src="https://img.shields.io/twitter/follow/wedwardbeck.svg?style=social" />
  </a>
</p>

> Example CRUD API using FastAPI

This repository is the result of wading through how to use async CRUD operations 
using the backend core from the excellent generator template by Sebastián Ramírez, 
[Full Stack FastAPI and PostgreSQL - Base Project Generator][tiangolo/fullstack].

In reviewing [the FastAPI docs][fastapidocs], the [encode/databases docs][databases-queries]
on queries, and the gitter channels, there seemed to be only the basic 
information on using databases with SQL Alchemy and data table 
definitions that would not work well with Alembic autogenerate - as least in 
my case using the generator template.  This repository is the working result
of my tests and learning to use FastAPU with async, asycnpg, databases, and Alembic 
autogenerated migrations with declarative base model.  Hopefully it will be useful 
to others looking for some examples of using databases, asyncpg and Alembic with FastAPI.


## Details

* **Uses version 0.4.0 of the [Fullstack generator][tiangolo/fullstack-v4]**: 
before current changes in structure of the project were made.
* **[encode/databases][databases-queries]**: To simplify managing connections, pooling, etc.   
* **asyncpg with Posgresql**: Built using a Postgresql 12 database, but can be altered to use SQLite.
* **[Alembic][alembic]**: Using autogenerate to create migrations.  

## To Do

Tests, deployment via docker, and other changes to come, time permitting.
Want to see these sooner - see below in [Contributing][learnfast-contrib].

## Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](https://github.com/wedwardbeck/lrnfast/issues).
1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/YourFeature`)
3. Commit your Changes (`git commit -m 'Add My Feature'`)
4. Push to the Branch (`git push origin feature/YourFeature`)
5. Open a Pull Request

## Contact

#### Edward Beck

- Twitter: [@wedwardbeck](https://twitter.com/wedwardbeck)
- Github: [@wedwardbeck](https://github.com/wedwardbeck)

## License

This project is licensed under the terms of the MIT license.

---
[tiangolo/fullstack]: https://github.com/tiangolo/full-stack-fastapi-postgresql
[tiangolo/fullstack-v4]: https://github.com/tiangolo/full-stack-fastapi-postgresql/tree/0.4.0
[fastapidocs]: https://fastapi.tiangolo.com/
[databases-queries]: https://www.encode.io/databases/database_queries/#queries
[databases]: https://www.encode.io/databases/database_queries/#queries
[alembic]: https://github.com/sqlalchemy/alembic
[learnfast]: https://github.com/wedwardbeck/lrnfast
[learnfast-contrib]: https://github.com/wedwardbeck/lrnfast#contributing
