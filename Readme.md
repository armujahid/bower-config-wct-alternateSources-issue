This repo demonstrate `bower-config#1.4.2` issue with `bower-alternative-source-resolver`

WCT tests can be executed using `npm run test` on all brances

Brances:
1. master (tests works fine without bower-alternative-source-resolver)
2. bower-config-1.4.2issue (tests show "Error: Environment variable used in .bowerrc is not defined: ${package}")
3. bower-config-1.4.1-fix (tests work fine after downgrading `bower-config` to v1.4.1)