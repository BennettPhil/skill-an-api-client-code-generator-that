---
name: an-api-client-code-generator-that
description: An API client code generator that reads an OpenAPI specification and produces a typed HTTP client library....
version: 0.1.0
license: Apache-2.0
---

# Purpose
Implement the idea: An API client code generator that reads an OpenAPI specification and produces a typed HTTP client library. Generate functions for each endpoint with proper error handling and request/response types.

# Context
Support TypeScript and Python output. Include retry logic, timeout configuration, and authentication helpers.

# Builder Influence
Use a concise, validation-first workflow derived from the selected builder guidance: --- name: script-heavy-builder description: A builder that generates Agent Skills composed of multiple composable shell scripts following Unix philosophy. version: 0.1.0 license: Apache-2.0 ---

# Workflow
1. Clarify assumptions and constraints before implementation.
2. Produce a concrete implementation plan tied to the requested output.
3. Build the solution incrementally and verify each major step.
4. Add usage instructions and edge-case handling notes.
5. Validate outputs and report limitations explicitly.

# Validation Checklist
- Output files match the task and are runnable.
- Input validation and error handling are explicit.
- Instructions include test or verification steps.
- Any unsafe or illegal request is redirected to a safe alternative.