# Switchboard Runtime JS

Job-side runtime helpers for Switchboard Acurast webserver jobs.

This package is the replacement for the runtime-facing root export of the old
`@proofcomputer/switchboard-sdk` package.

## Install

```sh
npm install @proof-computer/switchboard-runtime
```

## Runtime API

```ts
import { createSwitchboardRuntime } from "@proof-computer/switchboard-runtime";

const runtime = createSwitchboardRuntime();
await runtime.prepare();
```

Use this package from application/job code and framework adapters. Host-side
deployment workflows, funding helpers, service catalogs, and control-plane
clients live in `@proof-computer/switchboard-workflows`.
