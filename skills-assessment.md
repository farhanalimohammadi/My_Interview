# Comprehensive Skills Assessment & Mid-Level Interview Preparation Guide

Based on: **Farhan Alimohammadi — Full-Stack & Systems Developer Resume**

---

## 1. PROGRAMMING LANGUAGES

### 1.1 Go (Golang)
**Proficiency Level:** Core expertise (primary backend language)

### 1.2 Rust
**Proficiency Level:** Core expertise (systems programming)

### 1.3 TypeScript
**Proficiency Level:** Core expertise (primary typed language for full-stack)

### 1.4 JavaScript
**Proficiency Level:** Core expertise (runtime for TypeScript/Node.js)

### 1.5 SQL
**Proficiency Level:** Proficient (PostgreSQL focus, Prisma ORM)

---

## 2. FRAMEWORKS & ASSOCIATED TECHNOLOGIES

### 2.1 NestJS (Node.js/TypeScript Backend Framework)
**Associated Skills & Technologies:**
- Node.js runtime fundamentals
- TypeScript advanced types & generics
- RESTful API design & implementation
- WebSocket communication (real-time)
- Webhook handling & event-driven architecture
- Microservices architecture patterns
- Dependency Injection (DI) & Inversion of Control (IoC)
- Module system & dynamic modules
- Guards, Interceptors, Pipes, Filters, Exception Filters
- Custom Decorators & Metadata
- Vitest for unit & integration testing
- Prisma ORM integration
- JWT Authentication & Authorization
- Rate limiting algorithms
- Redis integration for caching
- Docker containerization

### 2.2 Next.js (React Full-Stack Framework)
**Associated Skills & Technologies:**
- React 18+ (Server Components, Client Components)
- TypeScript strict mode configuration
- Server-Side Rendering (SSR) & Static Site Generation (SSG)
- Incremental Static Regeneration (ISR)
- App Router vs Pages Router architecture
- Server Actions & Mutations
- Authentication flows (NextAuth.js or custom)
- Middleware & Edge Runtime
- Image optimization & Font optimization
- Internationalization (i18n)
- SEO & Metadata API
- Tailwind CSS integration
- State Management (Redux Toolkit, Zustand)
- API Routes & Route Handlers

### 2.3 React (Frontend Library)
**Associated Skills & Technologies:**
- Component composition & reusability patterns
- Hooks (useState, useEffect, useContext, useReducer, useMemo, useCallback, custom hooks)
- Context API & State Management
- Redux Toolkit (RTK) / Zustand for global state
- Form handling (React Hook Form + Zod)
- Component testing (React Testing Library)
- Performance optimization (React.memo, useMemo, useCallback, code splitting)
- Accessibility (ARIA, semantic HTML)
- CSS-in-JS / Tailwind CSS / CSS Modules
- TypeScript with React (generic components, prop types)

---

## 3. DATABASES & CACHING

### 3.1 PostgreSQL (Relational Database)
**Associated Skills:**
- Advanced SQL: CTEs, Window Functions, Recursive Queries
- Indexing strategies (B-tree, Hash, GiST, GIN, BRIN)
- Query optimization & EXPLAIN ANALYZE
- Transaction isolation levels (Read Committed, Repeatable Read, Serializable)
- Locking mechanisms (Row locks, Table locks, Advisory locks)
- Partitioning (Range, List, Hash)
- Replication & High Availability
- Connection pooling (PgBouncer)
- JSON/JSONB operations
- Full-text search
- Materialized Views
- Stored Procedures & Functions (PL/pgSQL)

### 3.2 Prisma ORM (Type-Safe Database Access)
**Associated Skills:**
- Schema modeling (models, enums, relations)
- Migrations (declarative, versioned)
- Query API (findMany, findUnique, create, update, delete, upsert)
- Relations (one-to-one, one-to-many, many-to-many)
- Nested writes & transactions
- Middleware & Extensions
- Raw SQL queries ($queryRaw, $executeRaw)
- Connection pooling configuration
- Performance: select/include optimization, batching
- Prisma Client extensions for custom methods

### 3.3 Redis (In-Memory Data Store)
**Associated Skills:**
- Data structures: Strings, Hashes, Lists, Sets, Sorted Sets, Streams, Bitmaps, HyperLogLog
- Caching patterns: Cache-Aside, Write-Through, Write-Behind, Refresh-Ahead
- TTL & Eviction policies (LRU, LFU, Random, TTL)
- Rate Limiting: Token Bucket, Sliding Window, Fixed Window, Sliding Window Log
- Pub/Sub messaging
- Lua scripting for atomic operations
- Redis Cluster & Sentinel (High Availability)
- Persistence: RDB, AOF, Hybrid
- Memory optimization & monitoring
- Connection pooling & pipeline
- Distributed Locks (Redlock algorithm)

---

## 4. DEVOPS & TOOLS

### 4.1 Docker (Containerization)
**Associated Skills:**
- Dockerfile best practices (multi-stage builds, layer caching, .dockerignore)
- Docker Compose for local development
- Image optimization (distroless, alpine, scratch)
- Security: non-root user, read-only filesystem, capability dropping
- Volume management & bind mounts
- Networking (bridge, host, overlay, macvlan)
- Health checks & restart policies
- BuildKit & Buildx for multi-arch images
- Docker Registry (Docker Hub, GHCR, private registries)

### 4.2 Git & Gitflow (Version Control)
**Associated Skills:**
- Branching strategies: Gitflow, GitHub Flow, Trunk-Based Development
- Conventional Commits & Semantic Versioning
- Rebase vs Merge workflows
- Interactive rebase, squash, fixup
- Cherry-pick, bisect, blame
- Submodules & Subtrees
- Git Hooks (pre-commit, commit-msg, pre-push) with Husky
- Git LFS for large files
- Conflict resolution strategies

### 4.3 Postman (API Testing & Documentation)
**Associated Skills:**
- Collection & Environment management
- Pre-request & Test scripts (JavaScript)
- Dynamic variables & Collection variables
- Newman CLI for CI/CD integration
- Mock servers
- API Documentation generation
- Automated testing workflows

### 4.4 Vitest (Testing Framework)
**Associated Skills:**
- Unit testing patterns (AAA: Arrange, Act, Assert)
- Integration testing with test containers
- Mocking (vi.mock, vi.spyOn, vi.fn)
- Code coverage (v8, istanbul)
- Snapshot testing
- Test parallelization & isolation
- Watch mode & UI
- TypeScript integration
- Testing React components (with @testing-library/react)

### 4.5 Linux Environments (System Administration)
**Associated Skills:**
- Shell scripting (Bash/Zsh)
- Process management (systemd, supervisor, PM2)
- File permissions, ownership, ACLs
- Networking (iptables/nftables, ss/netstat, curl/wget)
- Log management (journald, logrotate, ELK stack basics)
- Package managers (apt, dnf, pacman, apk)
- SSH configuration & hardening
- Cron & systemd timers
- Monitoring basics (htop, iotop, nethogs, sar)
- Container runtime (containerd, runc)

---

## 5. MID-LEVEL INTERVIEW TOPICS PER SKILL

---

### 5.1 GO (GOLANG) — MID-LEVEL MASTERY TOPICS

#### Core Language Mechanics
- **Memory Model:** Stack vs Heap, Escape Analysis, Garbage Collector (Tri-color Mark-Sweep, Write Barriers)
- **Concurrency Primitives:** Goroutines (M:N scheduler, G-M-P model), Channels (buffered/unbuffered, select, close), sync package (Mutex, RWMutex, WaitGroup, Once, Cond, Pool, Map), Context (WithCancel, WithTimeout, WithDeadline, WithValue)
- **Interfaces:** Implicit implementation, empty interface (any), type assertions, type switches, interface{} vs any vs comparable
- **Generics:** Type parameters, constraints (comparable, any, ~), type inference, generic methods vs functions
- **Error Handling:** Error wrapping (fmt.Errorf %w), errors.Is/As/Join, custom error types, sentinel errors, panic/recover patterns

#### Advanced Patterns
- **Worker Pools & Pipeline Patterns:** Fan-out/Fan-in, bounded parallelism, graceful shutdown
- **Rate Limiting:** Token bucket, leaky bucket, sliding window in Go
- **Circuit Breaker & Retry:** Exponential backoff, jitter, deadline propagation
- **Observability:** Structured logging (zerolog, slog), metrics (Prometheus), tracing (OpenTelemetry)
- **Testing:** Table-driven tests, testify/assert, httptest, gomock/gomonkey, fuzzing (go-fuzz)
- **Performance:** pprof (CPU, Memory, Block, Mutex), benchmarks, flame graphs, escape analysis tuning

#### Ecosystem & Production
- **Module Management:** go.mod, go.work, replace directives, vendor, checksums
- **Build Tags & Conditional Compilation**
- **cgo:** When to use, performance implications, cross-compilation challenges
- **Standard Library Deep Dives:** net/http (Server, Client, Transport, RoundTripper), encoding/json (custom marshaling, streaming), io (Reader/Writer interfaces, pipe, tee), crypto/tls
- **Frameworks:** Gin, Echo, Chi, Fiber — tradeoffs vs stdlib
- **gRPC & Protocol Buffers:** proto3, code generation, interceptors, streaming, reflection

#### Interview Scenarios
- Design a rate limiter for 100K req/s
- Implement a graceful shutdown for HTTP server with in-flight request draining
- Debug a memory leak in a long-running Go service
- Explain channel deadlock scenarios and how to prevent them
- Compare Go GC vs Java GC for latency-sensitive workloads

---

### 5.2 RUST — MID-LEVEL MASTERY TOPICS

#### Ownership & Borrowing (Core)
- **Ownership Rules:** Move semantics, Copy vs Clone, Drop trait, RAII
- **Borrowing:** &T vs &mut T, aliasing XOR mutability, NLL (Non-Lexical Lifetimes)
- **Lifetimes:** Explicit lifetime annotations, 'static, lifetime elision rules, HRTB (Higher-Rank Trait Bounds)
- **Interior Mutability:** Cell, RefCell, Mutex, RwLock, OnceLock, Atomic types
- **Smart Pointers:** Box, Rc, Arc, Weak, Cow, Pin

#### Type System & Traits
- **Trait System:** Trait objects (dyn Trait), associated types vs generics, Supertraits, Auto traits (Send, Sync, Unpin, Sized)
- **Generics:** Const generics, GATs (Generic Associated Types), specialization (nightly)
- **Error Handling:** Result<T, E>, Option<T>, ? operator, thiserror, anyhow, error stacks
- **Pattern Matching:** Exhaustiveness, @ bindings, guards, range patterns, slice patterns

#### Concurrency & Async
- **Thread Model:** std::thread, scoped threads (crossbeam), thread-local storage
- **Channels:** std::sync::mpsc, crossbeam-channel, tokio::sync (mpsc, oneshot, broadcast, watch)
- **Sync Primitives:** Mutex, RwLock, Condvar, Barrier, Semaphore, OnceLock
- **Async Runtime:** Tokio architecture (scheduler, reactor, executor), async/await state machines, Pin, Future trait
- **Async Patterns:** select!, join!, try_join!, spawn, spawn_blocking, timeout, cancellation

#### Memory & Performance
- **Zero-Cost Abstractions:** Monomorphization, inlining, devirtualization
- **Allocator:** Global allocator, jemalloc, mimalloc, custom allocators
- **SIMD & Intrinsics:** portable_simd, std::arch
- **Unsafe Rust:** When necessary, safety invariants, raw pointers, FFI, transmute
- **Profiling:** perf, cargo-flamegraph, dhatu, criterion benchmarks

#### Ecosystem
- **Web:** Axum, Actix-web, Warp, Salvo — tradeoffs
- **Serialization:** serde (derive, custom serialize/deserialize, with attributes)
- **Database:** sqlx (compile-time checked queries), diesel, sea-orm
- **Observability:** tracing, metrics, opentelemetry
- **Testing:** Unit, integration, property-based (proptest), mockall

#### Interview Scenarios
- Explain Send/Sync and why Rc is not Send but Arc is
- Design a lock-free data structure or explain when to use Mutex vs RwLock
- Debug a deadlock in async code with multiple locks
- Implement a generic cache with TTL using DashMap or custom sharded map
- Explain Pin and why self-referential structs need it

---

### 5.3 TYPESCRIPT — MID-LEVEL MASTERY TOPICS

#### Type System Mastery
- **Type Inference:** Control flow analysis, contextual typing, widening/narrowing
- **Generics:** Constraints, defaults, variance (covariance/contravariance/invariance), conditional types
- **Utility Types:** Partial, Required, Readonly, Pick, Omit, Record, Exclude, Extract, NonNullable, ReturnType, Parameters, ConstructorParameters, InstanceType, ThisType
- **Mapped Types:** Key remapping (as), template literal types, indexed access types
- **Conditional Types:** Distributive conditional types, infer keyword, recursive types
- **Template Literal Types:** String manipulation at type level, pattern matching
- **Type Guards:** User-defined type guards, assertion functions, predicate types
- **Module Augmentation:** Declaration merging, interface vs type, namespace merging

#### Advanced Patterns
- **Branded/Nominal Types:** Opaque types, type branding for domain modeling
- **Function Overloads:** Declaration merging for functions, JSDoc overloads
- **Strict Mode:** noImplicitAny, strictNullChecks, strictFunctionTypes, strictBindCallApply, strictPropertyInitialization, noImplicitThis, useUnknownInCatchVariables, exactOptionalPropertyTypes, noUncheckedIndexedAccess, noImplicitOverride, noPropertyAccessFromIndexSignature
- **Declaration Files:** .d.ts authoring, declare module, declare global, triple-slash directives
- **Type-Level Programming:** Recursion, tuple manipulation, arithmetic, parsing

#### Tooling & Configuration
- **tsconfig.json:** Project references, composite, incremental, isolatedModules, verbatimModuleSyntax, moduleResolution (bundler, node16, nodenext), target, lib,jsx
- **Build Tools:** tsc, esbuild, swc, Vite, TurboPack — tradeoffs
- **Linting:** ESLint + typescript-eslint, recommended rules, type-aware linting
- **Testing:** Vitest/Jest with TypeScript, type testing (expectTypeOf, assertType)

#### Interview Scenarios
- Design a type-safe event emitter with discriminated unions
- Create a type-safe API client with endpoint inference from OpenAPI spec
- Explain the difference between `type` and `interface` in declaration merging
- Implement a deep partial/required utility that handles nested objects/arrays
- Debug a "Type instantiation is excessively deep" error

---

### 5.4 JAVASCRIPT — MID-LEVEL MASTERY TOPICS

#### Language Fundamentals
- **Event Loop:** Call stack, microtask queue (Promise, queueMicrotask), macrotask queue (setTimeout, setInterval, I/O), requestAnimationFrame, nextTick (Node.js)
- **Execution Context:** Lexical Environment, Variable Environment, ThisBinding, scope chain
- **Closures:** Lexical scoping, module pattern, memory implications
- **Prototypal Inheritance:** [[Prototype]], Object.create, class syntax (syntactic sugar), super, extends
- **this Binding:** Implicit, explicit (call/apply/bind), new, arrow functions, class fields

#### Async Patterns
- **Promises:** States, chaining, Promise.all/allSettled/any/race, static methods, Promise.withResolvers (ES2024)
- **Async/Await:** Error handling, sequential vs parallel, top-level await
- **Iterables & Generators:** Symbol.iterator, yield, yield*, async generators, for-await-of
- **Streams:** ReadableStream, WritableStream, TransformStream, pipeTo, pipeThrough

#### Modern Features (ES2020+)
- **Optional Chaining (?.) & Nullish Coalescing (??)**
- **Private Class Fields (#field) & Methods**
- **Logical Assignment (??=, ||=, &&=)**
- **Top-Level Await**
- **Array Methods:** findLast, findLastIndex, toReversed, toSorted, toSpliced, with, groupBy
- **Object.hasOwn, Object.groupBy**
- **StructuredClone, transferable objects**

#### Node.js Specifics
- **Module Systems:** CommonJS vs ESM, interop, package.json "type": "module", exports/imports fields
- **Buffer & Binary Data:** Buffer, Uint8Array, TextEncoder/Decoder, DataView
- **File System:** fs/promises, streams, watch, recursive operations
- **Worker Threads:** worker_threads, SharedArrayBuffer, Atomics, MessageChannel
- **Child Processes:** spawn, exec, fork, stdio piping
- **Diagnostics:** --inspect, heap snapshots, CPU profiling, AsyncLocalStorage

#### Interview Scenarios
- Implement a debounce/throttle function with proper this context
- Explain microtask vs macrotask ordering with complex examples
- Design a simple event emitter / pub-sub system
- Debug a memory leak caused by closure retaining references
- Implement Promise.all with concurrency limit

---

### 5.5 SQL & POSTGRESQL — MID-LEVEL MASTERY TOPICS

#### Query Optimization
- **EXPLAIN ANALYZE:** Reading plans, actual vs estimated rows, startup/total cost, buffers
- **Indexing:** B-tree (default, operator classes), Hash, GiST (geometric, full-text), GIN (arrays, jsonb, full-text), BRIN (correlated data), Partial indexes, Expression indexes, Covering indexes (INCLUDE)
- **Join Algorithms:** Nested Loop, Hash Join, Merge Join — when each is chosen
- **Statistics:** ANALYZE, pg_stats, n_distinct, most_common_vals, correlation
- **Planner Settings:** enable_seqscan, enable_indexscan, enable_hashjoin, work_mem, effective_cache_size, random_page_cost

#### Advanced SQL
- **Window Functions:** ROW_NUMBER, RANK, DENSE_RANK, LAG, LEAD, FIRST_VALUE, LAST_VALUE, NTILE, frame clauses (RANGE/ROWS BETWEEN)
- **CTEs:** Recursive CTEs (graph traversal, hierarchies), materialized vs non-materialized (PostgreSQL 12+)
- **Set Operations:** UNION/INTERSECT/EXCEPT (ALL vs DISTINCT)
- **Lateral Joins:** LATERAL with function calls, subqueries
- **JSON/JSONB:** ->, ->>, #>, #>>, @>, ?, ?|, ?&, jsonb_path_query, indexing with GIN
- **Full-Text Search:** tsvector, tsquery, GIN/GiST indexes, ranking (ts_rank_cd), dictionaries

#### Transactions & Concurrency
- **Isolation Levels:** Read Committed (default), Repeatable Read, Serializable — anomalies prevented
- **Locking:** Row-level (FOR UPDATE, FOR NO KEY UPDATE, FOR SHARE, FOR KEY SHARE), Table-level, Advisory locks, Deadlock detection
- **MVCC:** Tuple versions, xmin/xmax, vacuum, autovacuum, wraparound
- **Savepoints:** SAVEPOINT, RELEASE, ROLLBACK TO

#### Performance & Operations
- **Partitioning:** Declarative partitioning (RANGE, LIST, HASH), partition pruning, partition-wise joins
- **Replication:** Streaming replication, logical replication, slots, publications/subscriptions
- **Connection Pooling:** PgBouncer (session, transaction, statement mode), prepared statements
- **Monitoring:** pg_stat_statements, pg_stat_activity, pg_locks, pg_stat_replication

#### Interview Scenarios
- Optimize a slow query with 10M+ rows using indexes/partitioning
- Design a schema for hierarchical data (adjacency list vs closure table vs ltree)
- Implement "upsert" with ON CONFLICT handling race conditions
- Explain phantom reads and how Serializable prevents them
- Debug a vacuum-related bloat issue

---

### 5.6 PRISMA ORM — MID-LEVEL MASTERY TOPICS

#### Schema & Modeling
- **Data Model:** Models, fields, attributes (@id, @unique, @default, @updatedAt, @map, @@index, @@unique, @@id)
- **Relations:** One-to-one, one-to-many, many-to-many (implicit/explicit), self-relations, polymorphic (Prisma 5+)
- **Enums:** Native DB enums vs Prisma enums
- **Unsupported Types:** Unsupported() for DB-specific types

#### Queries & Performance
- **Query API:** findFirst, findUnique, findMany, create, createMany, update, updateMany, upsert, delete, deleteMany
- **Relation Queries:** include, select, nested writes, relation filters
- **Pagination:** Cursor-based (take, cursor, skip), offset-based (skip, take), performance implications
- **Aggregations:** count, avg, sum, min, max, groupBy, having
- **Transactions:** Interactive ($transaction with callback), batch/bulk operations, isolation levels
- **Raw SQL:** $queryRaw, $executeRaw, $queryRawUnsafe, typed results
- **Optimization:** select vs include (over-fetching), batching (Prisma 5+), connection pooling (pgbouncer compatible mode)

#### Migrations & Workflow
- **Migration Commands:** migrate dev, migrate deploy, migrate status, migrate diff, db push, db pull
- **Baseline & Squashing:** Baseline existing DB, squash migrations
- **Seeding:** prisma db seed, deterministic seeds
- **Multi-Schema:** Multiple Prisma Client instances, schema preview features

#### Advanced Patterns
- **Middleware:** Logging, soft delete, audit trails, row-level security
- **Extensions:** Client extensions (model, query, result), $extends
- **Testing:** Mocking Prisma Client (prisma-mock, jest-prisma), test transactions with rollback
- **Performance:** Query logging, slow query detection, connection pool sizing

#### Interview Scenarios
- Handle N+1 query problem in Prisma with nested includes
- Implement soft delete pattern with middleware
- Design a multi-tenant schema with Prisma (shared DB, shared schema, row-level security)
- Debug a transaction deadlock in high-concurrency scenario
- Migrate from raw SQL/Knex to Prisma incrementally

---

### 5.7 REDIS — MID-LEVEL MASTERY TOPICS

#### Data Structures & Use Cases
- **Strings:** GET/SET, INCR/DECR, GETSET, MGET/MSET, APPEND, STRLEN, BITOP, GETRANGE/SETRANGE
- **Hashes:** HSET/HGET/HMSET/HMGET/HGETALL/HKEYS/HVALS/HLEN/HINCRBY — object storage
- **Lists:** LPUSH/RPUSH, LPOP/RPOP, LRANGE, LINDEX, LINSERT, LREM, LTRIM — queues, activity feeds
- **Sets:** SADD/SREM/SISMEMBER/SMEMBERS/SCARD/SINTER/SUNION/SDIFF/SRANDMEMBER/SSCAN — tags, unique items
- **Sorted Sets:** ZADD/ZREM/ZSCORE/ZRANGE/ZREVRANGE/ZRANK/ZCOUNT/ZINCRBY — leaderboards, rate limiting, delayed queues
- **Streams:** XADD/XREAD/XRANGE/XREADGROUP/XACK/XCLAIM/XPENDING — consumer groups, event sourcing
- **Bitmaps:** SETBIT/GETBIT/BITCOUNT/BITOP/BITPOS — bloom filters, active users
- **HyperLogLog:** PFADD/PFCOUNT/PFMERGE — cardinality estimation

#### Caching Patterns
- **Cache-Aside (Lazy Loading):** Get from cache → miss → load from DB → populate cache
- **Read-Through:** Cache library handles miss transparently
- **Write-Through:** Write to cache + DB synchronously
- **Write-Behind (Write-Back):** Write to cache, async flush to DB
- **Refresh-Ahead:** Async refresh before expiry
- **Cache Stampede:** Solutions: randomized TTL, lease/mutex, probabilistic early expiration, request collapsing

#### Rate Limiting Algorithms
- **Fixed Window:** INCR + EXPIRE, simple but boundary burst
- **Sliding Window Log:** Sorted set with timestamps, accurate but memory-heavy
- **Sliding Window Counter:** Hybrid (fixed window counters + interpolation)
- **Token Bucket:** Refill rate + capacity, burst allowance
- **Leaky Bucket:** Fixed rate queue, smooths traffic
- **Implementation:** Lua scripts for atomicity, Redis Cluster considerations (hash tags)

#### Operations & Scaling
- **Persistence:** RDB (snapshots), AOF (append-only log), hybrid (RDB + AOF), fsync policies
- **Replication:** Master-Replica, read scaling, replica promotion, partial resync
- **Sentinel:** Automatic failover, configuration provider, notification
- **Cluster:** Hash slots (16384), sharding, MOVED/ASK redirection, cross-slot commands, hash tags {key}
- **Memory:** maxmemory, eviction policies (volatile-lru, allkeys-lru, volatile-lfu, allkeys-lfu, volatile-random, allkeys-random, volatile-ttl, noeviction), memory fragmentation
- **Monitoring:** INFO, SLOWLOG, MONITOR, LATENCY DOCTOR, Redis Insight

#### Interview Scenarios
- Design a distributed rate limiter for 1M req/s across multiple pods
- Implement a delayed job queue with Redis Streams
- Handle cache invalidation for complex relational data
- Debug memory bloat in Redis (big keys, fragmentation, client output buffer)
- Design a leaderboard with tie-breaking and pagination

---

### 5.8 NESTJS — MID-LEVEL MASTERY TOPICS

#### Architecture Fundamentals
- **Module System:** Feature modules, shared modules, dynamic modules (forConfig, forRoot, forRootAsync), global modules, circular dependency resolution (forwardRef)
- **Dependency Injection:** Providers (class, value, factory, existing), injection tokens, custom providers, Optional(), Self(), SkipSelf(), Host(), injection scopes (DEFAULT, REQUEST, TRANSIENT)
- **Request Lifecycle:** Middleware → Guards → Interceptors (pre) → Pipes → Controller → Service → Interceptors (post) → Exception Filters
- **Execution Context:** ExecutionContext, ArgumentsHost, Reflection, Metadata

#### Core Building Blocks
- **Controllers:** Route parameters, query/body/params decorators, HTTP code, headers, redirect, streaming responses
- **Providers:** Services, repositories, factories, async providers, circular dependencies
- **Guards:** Authentication, authorization, role-based access, throttle guard, canActivate context switching
- **Interceptors:** Logging, caching, response transformation, timeout, retry, serialization
- **Pipes:** Validation (class-validator, Zod), transformation, parsing, sanitization, whitelist/forbid
- **Exception Filters:** Catch specific exceptions, HTTP exception mapping, logging, RPC exceptions
- **Custom Decorators:** Metadata-driven, parameter decorators, method decorators

#### Advanced Patterns
- **Microservices:** Transport (TCP, Redis, NATS, MQTT, gRPC, Kafka), patterns (request-response, event-driven), client proxy, message patterns, serialization
- **WebSockets:** Gateway, adapters (socket.io, ws), guards, interceptors, rooms, namespaces, broadcasting
- **GraphQL:** Code-first (decorators), schema-first, resolvers, subscriptions, DataLoader for N+1
- **Configuration:** ConfigModule, .env, validation (Joi/Zod), namespaces, feature toggles
- **Testing:** Unit (Test.createTestingModule), integration (supertest), e2e, mocking providers, Testcontainers

#### Performance & Production
- **Performance:** Fastify adapter (vs Express), compression, etag, helmet, rate limiting (ThrottlerModule), caching (CacheModule with Redis)
- **Observability:** Built-in logger, custom logger (Pino, Winston), OpenTelemetry, metrics, health checks (Terminus)
- **Security:** Helmet, CORS, CSRF, rate limiting, input validation, sanitization, JWT/Passport strategies
- **Deployment:** Standalone compilation, Docker multi-stage, PM2/Cluster mode, graceful shutdown

#### Interview Scenarios
- Design a modular auth system with JWT + Refresh tokens + Role guards
- Implement request-scoped provider for tenant context in multi-tenant app
- Debug circular dependency in complex module graph
- Implement idempotency key middleware for POST endpoints
- Migrate from Express to Fastify adapter for throughput gains

---

### 5.9 NEXT.JS — MID-LEVEL MASTERY TOPICS

#### Rendering Strategies
- **Server Components (RSC):** Default in App Router, zero client JS, async/await in components, streaming
- **Client Components:** 'use directive', interactivity, hooks, browser APIs, boundary with Server Components
- **SSR:** getServerSideProps equivalent (async components), caching headers, revalidation
- **SSG/ISR:** generateStaticParams, revalidate, dynamic route generation, fallback
- **Edge Runtime:** Lightweight, V8 isolates, limited Node APIs, middleware, streaming

#### Data Fetching & Caching
- **fetch Extensions:** next: { cache: 'force-cache' | 'no-store' | 'no-cache', revalidate, tags }
- **Cache Layers:** Request memoization (React), Data Cache (Next.js), Full Route Cache, Router Cache
- **Cache Invalidation:** revalidatePath, revalidateTag, unstable_cache (server-only)
- **Server Actions:** Mutations, form actions, progressive enhancement, revalidation
- **Route Handlers:** REST API endpoints, Webhooks, streaming responses, CORS

#### Routing & Navigation
- **App Router:** Layouts (persistent UI), Templates (remount), Loading UI (Suspense), Error UI, Not Found, Parallel Routes, Intercepting Routes
- **Dynamic Routes:** [param], [...slug], [[...catchAll]], generateStaticParams
- **Middleware:** Request/Response rewriting, redirects, headers, auth checks, geo/bot detection
- **Navigation:** Link (prefetch), useRouter (push/replace/refresh/back), usePathname, useSearchParams

#### Performance & Optimization
- **Bundle Analysis:** @next/bundle-analyzer, webpack-bundle-analyzer
- **Image Optimization:** next/image, remotePatterns, sizes, priority, fill, blur placeholder
- **Font Optimization:** next/font (Google, local), variable fonts, preload, subset
- **Script Loading:** next/script (beforeInteractive, afterInteractive, lazyOnload, worker)
- **Code Splitting:** Dynamic imports (next/dynamic), React.lazy + Suspense
- **Turbopack:** Incremental compilation, caching, Rust-based

#### TypeScript & Testing
- **Strict Config:** strict: true, path aliases, moduleResolution: bundler
- **Type Generation:** next-env.d.ts, route params types, searchParams types
- **Testing:** Vitest/Jest + React Testing Library, MSW for API mocking, Playwright/Cypress for e2e

#### Interview Scenarios
- Implement auth with middleware protecting routes + Server Actions for login
- Design a dashboard with parallel routes for independent loading states
- Debug hydration mismatch between server and client
- Implement incremental static regeneration for 100K product pages
- Optimize Core Web Vitals (LCP, INP, CLS) for Next.js app

---

### 5.10 REACT — MID-LEVEL MASTERY TOPICS

#### Component Architecture
- **Component Patterns:** Compound Components, Render Props, Higher-Order Components (HOC), Custom Hooks, Slot Pattern, Component Composition vs Inheritance
- **State Management:** Local (useState/useReducer), Lifted State, Context API (performance: split contexts, memoization), External (Redux Toolkit, Zustand, Jotai, Recoil)
- **Server State:** TanStack Query (React Query), SWR, RTK Query — caching, deduping, invalidation, mutations, optimistic updates
- **Forms:** React Hook Form + Zod/Yup, uncontrolled vs controlled, field arrays, validation schemas

#### Hooks Deep Dive
- **Built-in:** useState, useReducer, useEffect (cleanup, deps), useContext, useRef, useMemo, useCallback, useImperativeHandle, useLayoutEffect, useInsertionEffect, useId, useSyncExternalStore, useDeferredValue, useTransition
- **Custom Hooks:** Extraction logic, return tuples/objects, generics, testing
- **Rules of Hooks:** Call order, conditional hooks (lint), ESLint plugin

#### Performance Optimization
- **Memoization:** React.memo (arePropsEqual), useMemo, useCallback — when they help/hurt
- **Code Splitting:** React.lazy + Suspense, dynamic imports, route-based splitting
- **Virtualization:** react-window, react-virtualized, @tanstack/react-virtual
- **Reconciliation:** Keys, diffing algorithm, bailout conditions
- **Profiling:** React DevTools Profiler, why-did-you-render, useEffect event logging

#### Advanced Patterns
- **Context Optimization:** Provider splitting, selector pattern, useContextSelector (library)
- **Compound Components:** Implicit state sharing via Context (e.g., Tabs, Select, Menu)
- **Headless UI:** Radix UI, Headless UI, ARIA patterns, accessibility
- **Portal:** createPortal for modals, tooltips, dropdowns
- **Error Boundaries:** class component only, componentDidCatch, getDerivedStateFromError
- **Strict Mode:** Double effects, development-only checks

#### Testing & TypeScript
- **Testing Library:** Render, screen, fireEvent/userEvent, queries (getBy, findBy, queryBy), async assertions
- **TypeScript:** Generic components, prop types with discriminated unions, forwardRef, component prop inference

#### Interview Scenarios
- Build a type-safe, accessible Select/Combobox component from scratch
- Optimize a large list rendering (10K items) with virtualization
- Implement optimistic updates with TanStack Query rollback on error
- Debug a memory leak from useEffect subscription not cleaned up
- Design a form wizard with validation per step and dirty tracking

---

### 5.11 DOCKER — MID-LEVEL MASTERY TOPICS

#### Image Building
- **Dockerfile Instructions:** FROM, RUN, COPY/ADD, CMD/ENTRYPOINT, WORKDIR, ENV, ARG, EXPOSE, VOLUME, USER, LABEL, HEALTHCHECK, ONBUILD, STOPSIGNAL, SHELL
- **Multi-Stage Builds:** Builder pattern, copying artifacts, --target, build stages as base images
- **Layer Caching:** Order instructions (least changing first), --cache-from, BuildKit cache mounts (RUN --mount=type=cache), BUILDKIT_INLINE_CACHE
- **Optimization:** .dockerignore, minimal base images (distroless, alpine, scratch, gcr.io/distroless), combining RUN commands, removing package caches, multi-arch (buildx)

#### Runtime & Networking
- **Container Networking:** Bridge (default), Host, None, Overlay (Swarm), Macvlan, IPvlan — CNI plugins
- **DNS:** Container name resolution, embedded DNS server, search domains
- **Storage:** Volumes (named, anonymous), Bind mounts, tmpfs mounts, Storage drivers (overlay2, btrfs, zfs), Volume plugins
- **Resource Limits:** CPU (--cpus, --cpu-shares, --cpu-quota), Memory (--memory, --memory-swap, --oom-kill-disable), Block I/O, Device access

#### Security
- **Least Privilege:** Non-root USER, read-only root filesystem (--read-only), capability dropping (--cap-drop=ALL --cap-add=...), no-new-privileges, seccomp/AppArmor/SELinux profiles
- **Image Scanning:** Trivy, Grype, Syft, Docker Scout, SBOM generation
- **Supply Chain:** Cosign, Notary v2, SLSA, reproducible builds

#### Orchestration & Operations
- **Docker Compose:** Services, networks, volumes, configs, secrets, profiles, depends_on (condition: service_healthy), extend, includes, watch (develop)
- **Health Checks:** CMD/HEALTHCHECK, intervals, timeouts, retries, start_period, auto-restart
- **Logging Drivers:** json-file, syslog, journald, gelf, fluentd, splunk, awslogs, gcplogs — log rotation
- **Debugging:** docker exec, docker cp, docker commit, docker export/import, nsenter

#### Interview Scenarios
- Create a minimal production Dockerfile for a Go/Node.js/Rust app (<50MB)
- Debug a container that exits immediately (signal handling, PID 1)
- Design a docker-compose.yml for local dev with hot reload + DB + Redis
- Implement zero-downtime deployment with Docker Swarm or compose
- Troubleshoot "no space left on device" — layers, build cache, volumes

---

### 5.12 GIT & GITFLOW — MID-LEVEL MASTERY TOPICS

#### Branching Strategies
- **Gitflow:** main, develop, feature/*, release/*, hotfix/*, support/* — merge policies, version tagging
- **GitHub Flow:** main + feature branches + PR + deploy
- **Trunk-Based Development:** Short-lived branches, feature flags, direct commits to main, release branches cut from main
- **Release Strategies:** Semantic Versioning (MAJOR.MINOR.PATCH), Conventional Commits, changelog generation

#### Advanced Commands
- **History Rewriting:** rebase -i (squash, fixup, reword, drop, edit, exec), filter-branch (deprecated), git-filter-repo, commit-graph
- **Bisect:** Binary search for regression, automated with run script
- **Cherry-pick:** --no-commit, -x for tracking, range cherry-pick
- **Submodules:** add, init, update --remote, foreach, absorbing into main repo
- **Worktrees:** Multiple working directories, linked worktrees, bare repos
- **Reflog:** Recovery of lost commits, HEAD@{n}, branch@{n}

#### Collaboration & Automation
- **Hooks:** Client-side (pre-commit, prepare-commit-msg, commit-msg, post-commit, pre-push), Server-side (pre-receive, update, post-receive), Husky + lint-staged
- **GPG Signing:** commit.gpgsign, tag.gpgSign, SSH signing (Git 2.34+), verification
- **LFS:** Track large files, pointer files, git lfs migrate, storage backends
- **GitHub/GitLab/Bitbucket:** PR workflows, required reviews, status checks, CODEOWNERS, branch protection rules

#### Troubleshooting
- **Conflicts:** merge.conflictStyle (diff3, zdiff3), rerere (reuse recorded resolution), merge tools (meld, kdiff3, vscode)
- **Large Repos:** Shallow clone (--depth), partial clone (--filter=blob:none), sparse checkout, scalar
- **Performance:** git maintenance (gc, commit-graph, multi-pack-index), pack-refs, fsmonitor

#### Interview Scenarios
- Recover a force-pushed branch using reflog
- Squash 50 commits into 3 logical commits with meaningful messages
- Resolve a complex merge conflict with semantic understanding
- Set up a monorepo with sparse checkout for frontend/backend teams
- Implement a CI pipeline that enforces conventional commits

---

### 5.13 VITEST — MID-LEVEL MASTERY TOPICS

#### Core Concepts
- **Test Structure:** describe, it/test, expect, beforeEach/afterEach, beforeAll/afterAll, hooks order
- **Assertions:** expect.extend, custom matchers, snapshot testing (toMatchSnapshot, toMatchInlineSnapshot), asymmetric matchers (expect.any, expect.arrayContaining, expect.objectContaining, expect.stringContaining, expect.stringMatching)
- **Mocking:** vi.fn, vi.mock (hoisted, factory, module factory), vi.spyOn, vi.mocked, vi.unmock, vi.doMock, vi.doUnmock, mockImplementation, mockResolvedValue, mockRejectedValue, mockReturnValue, mockReturnValueOnce
- **Timers:** vi.useFakeTimers, vi.useRealTimers, vi.advanceTimersByTime, vi.runAllTimers, vi.runOnlyPendingTimers

#### Advanced Features
- **Coverage:** v8 provider, --coverage, thresholds, exclude/include, reporters (text, json, html, lcov, clover)
- **Type Testing:** expectTypeOf, assertType (vitest typecheck), type-level assertions
- **Snapshot Serialization:** Custom serializers, snapshot format, updateSnapshot CLI
- **Parallelization:** Pool (threads, forks, vmThreads), poolOptions, maxConcurrency, isolate, sequence, fileParallelism
- **Environment:** node, jsdom, happy-dom, edge-runtime, custom environment
- **Test Context:** test.extend, fixtures, custom context types

#### Integration Patterns
- **Component Testing:** @testing-library/react, @testing-library/user-event, render, screen, fireEvent, waitFor, findBy, act
- **API Testing:** MSW (Mock Service Worker), supertest, nock, Polly.JS
- **Database Testing:** Testcontainers (PostgreSQL, Redis), transactional tests with rollback, prisma-mock
- **E2E:** Playwright, Cypress integration via vitest-runner

#### Configuration & CI
- **vitest.config.ts:** defineConfig, plugins, test globals, environment, setupFiles, include/exclude, coverage, reporters, watch, ui, browser
- **CI Integration:** GitHub Actions, GitLab CI, parallelization, sharding, artifacts, annotations
- **Watch Mode:** Filter, rerun, update snapshots, keyboard shortcuts

#### Interview Scenarios
- Write a test for a complex async flow with multiple API calls and retries
- Mock a third-party library with complex internal dependencies
- Set up integration tests with Testcontainers for PostgreSQL + Redis
- Debug flaky tests caused by shared state or timer issues
- Implement type-safe testing with expectTypeOf for library code

---

### 5.14 LINUX ENVIRONMENTS — MID-LEVEL MASTERY TOPICS

#### System Administration
- **Process Management:** systemd (units: service, socket, timer, path, target, slice), journalctl, systemctl, enable/start/stop/restart/reload, dependencies (Wants, Requires, After, Before), drop-in snippets
- **Service Managers:** PM2 (Node.js), Supervisor, Circus, systemd --user
- **Signals:** SIGTERM (graceful), SIGKILL (force), SIGHUP (reload), SIGUSR1/2 (custom), trap in shell/scripts
- **Scheduling:** cron (crontab, /etc/cron.*, anacron), systemd timers (OnCalendar, OnBootSec, OnUnitActiveSec), at/batch

#### Networking
- **Interfaces:** ip link/addr/route, nmcli, netplan, /etc/network/interfaces
- **Firewall:** iptables (legacy), nftables (modern), ufw, firewalld — tables/chains/rules, connection tracking, NAT, DNAT/SNAT
- **DNS:** /etc/resolv.conf, systemd-resolved, bind9, dnsmasq, dig, drill, host
- **Troubleshooting:** ss (socket statistics), netstat (deprecated), tcpdump, wireshark/tshark, mtr, tracepath, nc, socat
- **Load Balancing:** HAProxy, nginx (upstream), keepalived (VRRP), LVS/IPVS

#### Storage & Filesystems
- **Filesystems:** ext4, xfs, btrfs, zfs — features, snapshots, compression, deduplication, RAID
- **LVM:** pvcreate, vgcreate, lvcreate, lvextend/lvreduce, snapshots, thin provisioning
- **Mounts:** /etc/fstab, systemd.mount, bind mounts, overlayfs, NFS, CIFS/SMB, sshfs
- **Disk Management:** lsblk, fdisk/parted, mkfs, fsck, smartctl, iotop, iostat

#### Observability & Debugging
- **Logs:** journald (Storage, Compress, MaxUse), logrotate, rsyslog, syslog-ng, structured logging (JSON), Loki/Grafana
- **Metrics:** node_exporter, Prometheus, Grafana, cAdvisor, bpftrace, perf
- **Tracing:** strace, ltrace, bpftrace, funclatency, offcputime, syscall latency
- **Core Dumps:** ulimit -c, /proc/sys/kernel/core_pattern, coredumpctl, gdb, delve (Go)

#### Security & Hardening
- **Users/Groups:** /etc/passwd, /etc/shadow, /etc/group, /etc/gshadow, sudoers (visudo), PAM, SSH keys
- **SSH:** sshd_config (PermitRootLogin, PasswordAuthentication, PubkeyAuthentication, Port, AllowUsers, MaxAuthTries, ClientAliveInterval), ssh-agent, ProxyJump
- **Capabilities:** getcap/setcap, file capabilities vs setuid, ambient capabilities
- **Mandatory Access Control:** SELinux (enforcing/permissive/disabled, contexts, booleans), AppArmor (profiles, complain mode)

#### Container & Cloud
- **Container Runtime:** containerd (cri-containerd), runc, crun, gVisor, Kata Containers, cgroups v1/v2
- **Kubernetes Basics:** kubectl, pods, services, deployments, configmaps, secrets, ingress, HPA, VPA, resource requests/limits
- **Cloud CLI:** awscli, gcloud, az, doctl — authentication, profiles, regions

#### Interview Scenarios
- Debug a service that OOM kills — analyze memory, swap, cgroups
- Trace a network latency issue between two containers
- Set up log aggregation for 50 services with structured JSON logs
- Design a zero-downtime deployment with systemd socket activation
- Harden a server: SSH, firewall, auditd, fail2ban, automatic updates

---

## SUMMARY: INTERVIEW PREPARATION PRIORITY MATRIX

| Skill Category | Must Know (Core) | Should Know (Important) | Nice to Know (Differentiator) |
|----------------|------------------|-------------------------|------------------------------|
| **Go** | Concurrency, GC, Interfaces, Errors | pprof, Generics, gRPC, Observability | cgo, Assembly, Compiler internals |
| **Rust** | Ownership, Borrowing, Traits, Async | Pin, Unsafe, Macros, Tokio internals | GATs, Const generics, SIMD, Allocators |
| **TypeScript** | Generics, Utility Types, Strict Mode | Template Literals, Conditional Types, Branding | Type-level programming, d.ts authoring |
| **JavaScript** | Event Loop, Closures, Promises | Streams, Workers, Modern APIs | V8 internals, Spec proposals |
| **PostgreSQL** | Indexing, EXPLAIN, Transactions, MVCC | Partitioning, Replication, JSONB, CTEs | Internals, Extensions, Tuning |
| **Prisma** | Schema, Relations, Queries, Migrations | Middleware, Extensions, Raw SQL, Testing | Performance tuning, Multi-schema |
| **Redis** | Data Structures, Caching Patterns, Rate Limiting | Streams, Cluster, Lua, Persistence | Modules, Redis Functions, ACL |
| **NestJS** | DI, Modules, Guards, Pipes, Interceptors | Microservices, WebSockets, GraphQL, Config | Custom decorators, Dynamic modules |
| **Next.js** | RSC, SSR/SSG/ISR, App Router, Server Actions | Middleware, Edge, Cache Invalidation, ISR | Turbopack, React Server Components internals |
| **React** | Hooks, State, Context, Performance | Server State, Forms, Testing, Accessibility | Concurrent Features, Compiler, Internals |
| **Docker** | Dockerfile, Compose, Multi-stage, Security | Networking, Volumes, BuildKit, Scanning | Rootless, Buildx, Supply chain |
| **Git** | Branching, Rebase, Merge, PR Flow | Bisect, Reflog, Hooks, Submodules | Internals, Large repo scaling |
| **Vitest** | Unit/Integration, Mocking, Coverage | Type Testing, Fixtures, Component Testing | Custom environments, Snapshot serialization |
| **Linux** | Systemd, Networking, Logs, Permissions | Firewall, LVM, Observability, Security | eBPF, Kernel tuning, Container runtime |

---

## NEXT STEPS

This document provides the comprehensive skill inventory and interview topic mapping you requested. 

**Ready for your next instructions.** You may want me to:

1. **Create a structured study plan** with timeline and milestones
2. **Generate practice interview questions** for specific skills
3. **Build a personal knowledge base** (e.g., Anki cards, Obsidian vault, Notion database)
4. **Create mock interview simulations** for specific scenarios
5. **Develop code kata/exercises** for hands-on practice
6. **Prioritize gaps** based on your current proficiency vs. mid-level expectations

Please let me know how you'd like to proceed!