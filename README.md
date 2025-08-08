# Hexagonal Architecture Base in Go

This is a clean starter template for Go projects following the Hexagonal Architecture (Ports & Adapters).
## Structure
- **domain/**: Entities, value objects, and business rules.
- **application/**: Use cases and orchestration.
- **infrastructure/**: Adapters, repositories, controllers, configuration.
- **test/**: Builders, mocks, and test utilities.
- **migration/**: Database migrations.
- **pkg/**: Shared utilities.
- **scripts/**: Project scripts.
