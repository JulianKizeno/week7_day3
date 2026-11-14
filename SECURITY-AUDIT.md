# Security review — 2026-11-14

This is a partial remediation, not a certification that the repository is free of vulnerabilities. Changes remain in a draft pull request pending review.

## react-lifecycle

npm findings before: {"info": 0, "low": 8, "moderate": 123, "high": 43, "critical": 5, "total": 179}. After remediation: {"info": 0, "low": 8, "moderate": 124, "high": 44, "critical": 0, "total": 176}.
Counts refer to dependency findings in this project, including development dependencies. Projects without a committed lockfile were first resolved to create an auditable baseline. Production builds were checked on Node.js 24 with CI=true, npm ci --ignore-scripts --legacy-peer-deps and NODE_OPTIONS=--openssl-legacy-provider for legacy Webpack compatibility; these builds are not browser end-to-end tests.

Production build/test result: `{   "project": "week7_day3/react-lifecycle",   "install_exit": 0,   "build_exit": 0 }`.

### Remaining advisories

- `react-scripts`: high; requires dependency migration. 

Do not treat compatible lockfile updates as completion of the framework migrations above.

## react-forms

npm findings before: {"info": 0, "low": 8, "moderate": 126, "high": 41, "critical": 5, "total": 180}. After remediation: {"info": 0, "low": 8, "moderate": 129, "high": 40, "critical": 0, "total": 177}.
Counts refer to dependency findings in this project, including development dependencies. Projects without a committed lockfile were first resolved to create an auditable baseline. Production builds were checked on Node.js 24 with CI=true, npm ci --ignore-scripts --legacy-peer-deps and NODE_OPTIONS=--openssl-legacy-provider for legacy Webpack compatibility; these builds are not browser end-to-end tests.

Production build/test result: `{   "project": "week7_day3/react-forms",   "install_exit": 0,   "build_exit": 0 }`.

### Remaining advisories

- `@testing-library/jest-dom`: high; requires dependency migration. 
- `react-scripts`: high; requires dependency migration. 

Do not treat compatible lockfile updates as completion of the framework migrations above.

## react-routing

npm findings before: {"info": 0, "low": 8, "moderate": 126, "high": 42, "critical": 5, "total": 181}. After remediation: {"info": 0, "low": 8, "moderate": 129, "high": 41, "critical": 0, "total": 178}.
Counts refer to dependency findings in this project, including development dependencies. Projects without a committed lockfile were first resolved to create an auditable baseline. Production builds were checked on Node.js 24 with CI=true, npm ci --ignore-scripts --legacy-peer-deps and NODE_OPTIONS=--openssl-legacy-provider for legacy Webpack compatibility; these builds are not browser end-to-end tests.

Production build/test result: `{   "project": "week7_day3/react-routing",   "install_exit": 0,   "build_exit": 0 }`.

### Remaining advisories

- `@testing-library/jest-dom`: high; requires dependency migration. 
- `query-string`: high; requires dependency migration. 
- `react-scripts`: high; requires dependency migration. 

Do not treat compatible lockfile updates as completion of the framework migrations above.
