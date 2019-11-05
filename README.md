# Agile-Developper-Skills
Description of skills needed for efficient agile developpement teams

## The Clean Coder Skills

### Having the good mindset & Planning efficiently
 How to become better programmer ?
 How to plan efficiently and split vertically for more predictable and efficient sprints?
 How to measure craftsmanship success based on the product success?
### Doing Safe refactoring
 Simplify the code complexity and improve readability so a human being can read and understands what it does.
 Simplify corrective and evaluative maintainibility by reducing time to find and understand the details.
 Logging and exception's handling is mandatory for any project.
### Writing unit Tests
 As the project grows the unit tests guaranty non regression about previous and ongoing usecases.
 Unit tests are live documentation about use cases and possible scenarios. 
 They talk the same ubiquitous language and are understundable by the business.
 Testing with nested dependencies can be complicated. This can be solved using mocking frameworks
 Unit tests focus on behaviour and not dependencies.

## Advanced Craftsmanship Skills			

### Test Driven Development
 Test driven development is a design technique for crafting complex algorithms. 
 It teaches the developper how to counter over-engineering and rework design with very quick feedback and safely.
 TDD have a very nice side effect: it creates Tests, 100% code coverage, and 0% dead code!
 
### Use BDD or ATDD for creating your acceptance tests
 Test-first technique that injects acceptance tests senarios for features in the beggining of milestones.
 Acceptance tests are customer-facing tests. 
 Facilitates workshops with steakholders representives(PO, Business analystes…)
 Global feature design and creation of common vocabulary.
 Clear contracts for developpers during milestones.
 
### Integration Testing
 Test as soon as possible the usecase's dependencies, the real adapters and without mocking.
 These tests assert that usecase's dependencies integrates well with frameworks used and give the required outputs.
 
### End to End Testing / System tests
 E2E testing verify that the system performs the requested behaviour from the user side and using production dependencies.
 System tests exercise the entire system end-to-end, they are runned on production like environment.
 Writing system tests first addresses integration concerns early in the development process and ensures that the system is always ready  for deployment.
 
## Expert Craftsmanship Skills

### Legacy with TDD
Low quality software is hard to refactor. Fully rewriting may lead to incomplete work and slow progress due to hidden usecases and poor documentation.
Instead, using TDD it is possible to capture usecases from existing code and cover behaviours with unit tests first to enable safe refactoring.

### Design Pattern
Patterns let you customize ready-made solutions rather than reinvent the wheel. 
Your code has fewer mistakes because you are using a proven, standard solution covering all hidden problems.
When used correctly patterns accelerates adding new features significantly.

### Mutation Testing
100% code coverage but 50% mutation testing score => half of the usecases are not really tested
understanding and deploying mutation testing is a step forward for better quality.

### Organising Your Tests
Do you have a test strategy? Structure and organisation of tests is crucial.
Tests are to maintain and use properly. How to integrate with your production pipelines correctly?
