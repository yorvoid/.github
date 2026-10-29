**Identity and access management for PHP, built for systems in which people, services and AI agents all act.** By YorvoLabs.

YorvoID is a library your application embeds, not a server you run beside it. It covers who someone is, how they proved it, what they may do, under whose authority, and why: passkeys first, sessions, step-up, recovery, and operations a passkey signed exactly. It works in any PHP 8.5 application, with or without a framework, and integrates with Symfony first.

- **Code, issues and pull requests:** [yorvoid/yorvoid](https://github.com/yorvoid/yorvoid), the monorepo where all of YorvoID is developed.
- **Documentation:** [docs/](https://github.com/yorvoid/yorvoid/tree/main/docs), from the Symfony quickstart to the threat model.
- **Security:** report vulnerabilities privately, as [the security policy](https://github.com/yorvoid/yorvoid/security/policy) describes.

The other repositories here, such as `yorvoid/core` or `yorvoid/symfony`, are read-only copies of the monorepo's `packages/`, which Composer installs. Please open issues and pull requests in [yorvoid/yorvoid](https://github.com/yorvoid/yorvoid).

> YorvoID is in early development. Licensed under the [Apache License 2.0](https://github.com/yorvoid/yorvoid/blob/main/LICENSE).
