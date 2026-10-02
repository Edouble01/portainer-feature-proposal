# Acceptance Criteria

## Feature: Environment Comparison Viewer

### Scenario 1: Compare Services

Given two Docker Compose environments

When a comparison is performed

Then all services should be listed

And missing services should be highlighted.

---

### Scenario 2: Compare Images

Given two Docker Compose environments

When image versions differ

Then the difference should be displayed.

---

### Scenario 3: Compare Environment Variables

Given two Docker Compose environments

When environment variables are different

Then the differences should be highlighted.

---

### Scenario 4: Compare Ports

Given two Docker Compose environments

When exposed ports differ

Then the differences should be displayed.
``