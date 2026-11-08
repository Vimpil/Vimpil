# Kirill Shevchenko

**Senior Backend Engineer · PHP / Symfony · APIs · SQL & Production Systems**

Backend engineer with 9+ years of independent software development experience. I mainly work with PHP and Symfony, focusing on API integrations, SQL performance, backend development and maintaining existing systems. I also have experience with JavaScript, TypeScript, React and Angular.

Based in Montenegro · Open to remote roles

## What I work on

- **API integrations:** connecting systems through REST and SOAP APIs, including payment integrations, external services and authentication with OAuth/JWT.
- **SQL performance:** analyzing and optimizing slow queries in MySQL and MariaDB using `EXPLAIN`. At Colnect, this included complex joins, temporary tables and `UNION ALL`.
- **Existing systems:** debugging production code, investigating integration issues and improving reliability through incremental changes.
- **Backend processes:** working with scheduled jobs, asynchronous operations, retries and idempotency in integration workflows.

Main tools: PHP, Symfony, MySQL / MariaDB, PostgreSQL, Docker, Nginx, Linux, Git, PHPUnit and CI/CD. Additional experience with Laravel, Yii, Redis, React, Angular and TypeScript.

## Professional experience

**Independent B2B developer · September 2017–present**

Independent software development for clients and personal projects. Some commercial work is covered by NDA and is described only at a general technical level.

**Instant Pickup Delivery · 2019–2020**

Backend development for a delivery platform using PHP and MySQL, with integrations including Stripe and mapping services (Google Maps / Mapbox). Also worked with JavaScript and TypeScript on the application side.

**Colnect · 2021–2022**

Symfony backend development and MariaDB query optimization. Investigated slow database operations involving joins, temporary tables and `UNION ALL`, improving query performance in an existing application.

**OneBrain AI · 2023**

Internship involving React development and real-time data synchronization.

**NDA-covered backend and admin development**

Part-time development and maintenance of an existing backend and administration system. Work included PHP backend functionality, WebSocket-based payment workflows, scheduled jobs, retries, idempotency, caching, CI/CD and an Angular administration interface.

**Additional experience**

- **Blockchain:** Bitcoin PSBT/UTXO development, a Top 200 result in Summer of Bitcoin and participation in a Solidity/Web3 competition in 2023.
- **WordPress:** custom plugins and themes, mostly non-commercial.
- **BetsuNippon:** independent development and maintenance of custom WordPress functionality and plugins.

The repositories below are portfolio projects and technical assignments, not commercial products or representations of client work.

## Featured projects

These are independent portfolio projects and technical assignments, not commercial products.

### [mariadb-query-optimization-lab](https://github.com/Vimpil/mariadb-query-optimization-lab)

Reproducible MariaDB query optimization experiments using synthetic datasets, Docker and execution-plan analysis.

- Five optimization cases covering indexing, JOINs, GROUP BY and query execution strategies
- MariaDB 11.4 with `EXPLAIN` and `ANALYZE`
- Large synthetic dataset: 2M orders and 4.6M order lines
- Interleaved benchmarks with warm-up runs and 15 measured repetitions
- Before/after execution plans and query performance comparisons
- Full result-equivalence checks to verify correctness
- Documented benchmark methodology, limitations and negative results

### [library-api](https://github.com/Vimpil/library-api)

Symfony 7.4 REST API for authors and books, built to a fixed specification.

- Filtering, pagination and sorting
- Separate `PUT` and `PATCH` semantics
- Request-to-DTO mapping with validation
- Writes dispatched as Symfony Messenger commands (synchronous transport)
- Doctrine migrations on SQLite
- 97 PHPUnit tests, 229 assertions

### [order-management-api-symfony](https://github.com/Vimpil/order-management-api-symfony)

Symfony 7.2 API for tile orders and prices.

- XML order ingestion (plain XML over HTTP, not a SOAP service)
- External price lookup with a controlled fallback when the provider is unavailable
- Paginated order statistics
- Full-text search with Manticore Search, MySQL and Docker Compose
- 11 PHPUnit controller tests with mocked dependencies

## Other projects

- [eth-wallet-dashboard](https://github.com/Vimpil/eth-wallet-dashboard): React / TypeScript dashboard showing Ethereum wallet balance and transactions.
- [whatsapp-media-crypto](https://github.com/Vimpil/whatsapp-media-crypto): an experiment, not production-ready. It has known correctness and security issues, is not an official WhatsApp implementation, and no stable release is planned. See its README before using it.

## Contact

[LinkedIn](https://www.linkedin.com/in/lifetrue/) · [vimpilteam@gmail.com](mailto:vimpilteam@gmail.com)
