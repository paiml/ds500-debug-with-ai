# Lab 3: Test Coverage and Bug Fixing

## Setup

The Snake game project in `labs/project` currently has no test coverage. You will need to create a comprehensive testing strategy and achieve above 80% test coverage.

## Tasks

1. Install any missing dependencies and start creating tests for the Rust backend
2. Run the tests and observe the output
3. Ensure all tests are passing
4. Create tests for the JavaScript frontend functionality
5. Re-run tests and use output to identify and fix potential bugs
6. Aim for above 80% test coverage

## Testing Strategy

- **Rust Backend Tests**: Unit tests for game logic, integration tests for API endpoints
- **Frontend Tests**: JavaScript unit tests for game functions (if using a testing framework)
- **Manual Testing**: Test the complete game flow manually

## Expected Deliverables

- Test files for the Rust backend (`snake/src/lib.rs` with `#[cfg(test)]` modules)
- Test coverage report showing >80% coverage
- Documentation of bugs found and fixed through testing
- Working game with verified functionality

Note: The project currently has no tests whatsoever, so you must implement them from scratch.

