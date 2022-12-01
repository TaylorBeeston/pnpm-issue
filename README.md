This repo will cause pnpm to hang when running the build script, but _only_ during a recursive `pnpm i`.

To reproduce, run `pnpm i`. You can test that the build script works correclty by running `cd packages/shared-helpers && pnpm build`.
