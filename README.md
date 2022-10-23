# preact-signals-nextjs

This is a simple NextJS app to demonstrate how preact-signals can break fast refresh in local development.

See https://github.com/preactjs/signals/issues/250 for more details.

## Steps to reproduce

1. Edit the contents of [pages/index.tsx](pages/index.tsx) and save the file. The page should fast refresh, but does not.

2. Comment out the `@preact/signals-react` package and repeat step 1. The page should fast refresh as expected.
