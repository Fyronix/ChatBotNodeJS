────────────────┐
│ High          │ Denial of Service in mongodb                                 │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Package       │ mongodb                                                      │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Dependency of │ connect-mongo                                                │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Path          │ connect-mongo > mongodb                                      │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ More info     │ https://github.com/advisories/GHSA-mh5c-679w-hh4r            │
└───────────────┴──────────────────────────────────────────────────────────────┘


┌───────────────┬──────────────────────────────────────────────────────────────┐
│ High          │ Deserialization of Untrusted Data in bson                    │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Package       │ bson                                                         │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Dependency of │ connect-mongo                                                │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Path          │ connect-mongo > mongodb > mongodb-core > bson                │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ More info     │ https://github.com/advisories/GHSA-v8w9-2789-6hhr            │
└───────────────┴──────────────────────────────────────────────────────────────┘


# Run  npm install mongoose@6.0.13  to resolve 1 vulnerability
SEMVER WARNING: Recommended action is a potentially breaking change
┌───────────────┬──────────────────────────────────────────────────────────────┐
│ Critical      │ Type confusion in mpath                                      │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Package       │ mpath                                                        │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Dependency of │ mongoose                                                     │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Path          │ mongoose > mpath                                             │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ More info     │ https://github.com/advisories/GHSA-p92x-r36w-9395            │
└───────────────┴──────────────────────────────────────────────────────────────┘


# Run  npm update ansi-regex --depth 8  to resolve 5 vulnerabilities
┌───────────────┬──────────────────────────────────────────────────────────────┐
│ Moderate      │  Inefficient Regular Expression Complexity in                │
│               │ chalk/ansi-regex                                             │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Package       │ ansi-regex                                                   │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Dependency of │ @tensorflow/tfjs-node                                        │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Path          │ @tensorflow/tfjs-node > @tensorflow/tfjs > yargs > cliui >   │
│               │ strip-ansi > ansi-regex                                      │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ More info     │ https://github.com/advisories/GHSA-93q8-gq69-wqmw            │
└───────────────┴──────────────────────────────────────────────────────────────┘


┌───────────────┬──────────────────────────────────────────────────────────────┐
│ Moderate      │  Inefficient Regular Expression Complexity in                │
│               │ chalk/ansi-regex                                             │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Package       │ ansi-regex                                                   │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Dependency of │ @tensorflow/tfjs-node                                        │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Path          │ @tensorflow/tfjs-node > @tensorflow/tfjs > yargs > cliui >   │
│               │ string-width > strip-ansi > ansi-regex                       │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ More info     │ https://github.com/advisories/GHSA-93q8-gq69-wqmw            │
└───────────────┴──────────────────────────────────────────────────────────────┘


┌───────────────┬──────────────────────────────────────────────────────────────┐
│ Moderate      │  Inefficient Regular Expression Complexity in                │
│               │ chalk/ansi-regex                                             │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Package       │ ansi-regex                                                   │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Dependency of │ @tensorflow/tfjs-node                                        │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Path          │ @tensorflow/tfjs-node > @tensorflow/tfjs > yargs > cliui >   │
│               │ wrap-ansi > strip-ansi > ansi-regex                          │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ More info     │ https://github.com/advisories/GHSA-93q8-gq69-wqmw            │
└───────────────┴──────────────────────────────────────────────────────────────┘


┌───────────────┬──────────────────────────────────────────────────────────────┐
│ Moderate      │  Inefficient Regular Expression Complexity in                │
│               │ chalk/ansi-regex                                             │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Package       │ ansi-regex                                                   │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Dependency of │ @tensorflow/tfjs-node                                        │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Path          │ @tensorflow/tfjs-node > @tensorflow/tfjs > yargs > cliui >   │
│               │ wrap-ansi > string-width > strip-ansi > ansi-regex           │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ More info     │ https://github.com/advisories/GHSA-93q8-gq69-wqmw            │
└───────────────┴──────────────────────────────────────────────────────────────┘


┌───────────────┬──────────────────────────────────────────────────────────────┐
│ Moderate      │  Inefficient Regular Expression Complexity in                │
│               │ chalk/ansi-regex                                             │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Package       │ ansi-regex                                                   │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Dependency of │ @tensorflow/tfjs-node                                        │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Path          │ @tensorflow/tfjs-node > @tensorflow/tfjs > yargs >           │
│               │ string-width > strip-ansi > ansi-regex                       │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ More info     │ https://github.com/advisories/GHSA-93q8-gq69-wqmw            │
└───────────────┴──────────────────────────────────────────────────────────────┘


found 8 vulnerabilities (5 moderate, 2 high, 1 critical) in 245 scanned packages
  run `npm audit fix` to fix 5 of them.
  3 vulnerabilities require semver-major dependency updates.
