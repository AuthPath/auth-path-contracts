# Contract architecture

## Responsibility

A developer tool that explains which addresses and authorization branches are required for a Soroban invocation, making complex multi-party authorization easier to review.

## Security boundary

Every state-changing operation must authenticate the actor that is allowed to cause
the change. Contract storage is intentionally smaller than the application database.

## Future specification

The generic development contract in this baseline must be replaced with the
project-specific state model before production deployment.
