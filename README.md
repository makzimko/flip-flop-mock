# flip-flop-mock
Mock server for flip-flop


#### Environments
```GET /api/environments``` - list of environments

```POST /api/environments``` - create new environment

```GET /api/environments/:id``` - get single environment

```PATCH /api/environments/:id``` - edit single environment

```DELETE /api/environments/:id``` - remove single environment

#### Components
```GET /api/components``` - list of components

```POST /api/components``` - create new component

```GET /api/components/:id``` - get single component

```PATCH /api/components/:id``` - edit single component

```DELETE /api/components/:id``` - remove single component

#### Predicates
```GET /api/predicates``` - list of predicates

```POST /api/predicates``` - create new predicate

```GET /api/predicates/:id``` - get single predicate

```PATCH /api/predicates/:id``` - edit single predicate

```DELETE /api/predicates/:id``` - remove single predicate

#### Feature flags
```GET /api/featureFlags``` - list of feature flags

```POST /api/featureFlags``` - create feature flag

```GET /api/featureFlags/:id``` - get single feature flag

```PATCH /api/featureFlags/:id``` - edit single feature flag

```DELETE /api/featureFlags/:id``` - remove single feature flag

```GET /api/flags/:id``` - get list of available feature flags for provided component if
