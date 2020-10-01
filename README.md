# Test Reproduction

### Running locally

1) Clone this repo
2) Update submodules: `git submodule update --recursive --init`
3) Install dependencies of the submodule: `cd site && npm ci`
4) Serve a backend by running `npx netlify-cms-proxy-server`
5) Run the local version by `cd netlify-cms-images-issue-submodule` and `npm run dev`

