# aiohttp-postgres
Basic CRUD app framework utilizing Clean Architecture concepts of Infrastructure, Usecases, and Adapters

Asyncio Python utilizing the following libraries:
* aiohttp: async web framework
* aiopg: async Postgres driver with SQLAlchemy support
* attrs: easy creation and validation of usecase-layer objects
* marshmallow: marshaling data between JSON web requests and usecase-layer objects
* alembic: database migration and schema management with SQLAlchemy support
 
API Design
* GET request filter query design influenced by the LHS Brackets recommendation here: https://www.moesif.com/blog/technical/api-design/REST-API-Design-Filtering-Sorting-and-Pagination/