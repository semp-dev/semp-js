# semp-js

This directory is intentionally a redirect.

The JavaScript implementation of SEMP is provided by [`semp-ts`](../semp-ts).
TypeScript is JavaScript with type annotations; `semp-ts` compiles to plain
JavaScript with `.d.ts` type definitions, and the published npm package
serves both JS and TS callers from the same artifact. Maintaining a
parallel hand-written JavaScript implementation would double the work
without producing a different binary.

If you want to consume SEMP from JavaScript: use the published package
that `semp-ts` produces. If you want to consume from TypeScript: same
package, with types.

If you want to contribute: open issues and PRs against `semp-ts`.
