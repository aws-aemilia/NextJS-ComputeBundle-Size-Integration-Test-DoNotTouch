# NextJS Latest

## What is this repo?

- Uses the `15.0.1` version of next.js always.
- The index page shows the actual version of Next.js deployed. 
- A directory of features is located by visiting the index page.
- DO NOT modify any text files in this repo (their size must be unchanged) otherwise integration tests can fail.

## Override Next.js version

To use a different version of Next.js instead of `latest`, specify the version in the environment 
variable `NEXTJS_VERSION_OVERRIDE` in Amplify Hosting. The `patch-next.sh` file take care of 
installing the desired version during the build (see amplify.yml). For example you can specify 
`canary` or `13.4.12`.
