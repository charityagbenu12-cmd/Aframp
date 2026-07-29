# Changelog

All notable changes to Aframp will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## 1.0.0 (2026-07-29)


### ⚠ BREAKING CHANGES

* **onramp:** Removes entire Aframp app structure; onramp functionality now lives in root app directory

### Features

* **a11y:** improve accessibility in bills payment form ([581e117](https://github.com/kellymusk/Aframp/commit/581e117532032b05e452f43c3ff8d8927e887b74))
* add bill dashboard page ([d8a21ed](https://github.com/kellymusk/Aframp/commit/d8a21edd43379e31e0c134f560f413781225bbb1))
* add bill payments dashboard design documentation ([35c37d3](https://github.com/kellymusk/Aframp/commit/35c37d36c604a6de0b45d5cf4ce9728b4528ee37))
* add confirmation dialog before submitting onramp/offramp orders ([acf14c4](https://github.com/kellymusk/Aframp/commit/acf14c44445f55b00165beea9b587b87641e700a)), closes [#327](https://github.com/kellymusk/Aframp/issues/327)
* add confirmation dialog for onramp/offramp orders ([e18d5ac](https://github.com/kellymusk/Aframp/commit/e18d5ac39a197d2bcd2b8ace3ed9e4f9e4cf3095))
* add Cookie Consent Banner and legal pages for privacy and terms ([b754e6a](https://github.com/kellymusk/Aframp/commit/b754e6a3a352ee76af18e047125e33a6f3448e58))
* add empty states design documentation ([20ef87f](https://github.com/kellymusk/Aframp/commit/20ef87f18de8ca4c62a42257ab36657b87802ddd))
* add highlights carousel ([93569cf](https://github.com/kellymusk/Aframp/commit/93569cf6e76454c06cd1ca38e0dd62f556796138))
* add interactive transaction history component with filtering, sorting, and pagination ([9030f80](https://github.com/kellymusk/Aframp/commit/9030f805ce3edfbc3c12fd8afa1b806db2233321))
* add IP-based rate limiting on API routes via Upstash ([9e9bd3a](https://github.com/kellymusk/Aframp/commit/9e9bd3a15b80c1b2d3c7663f680c5b9c72f2c191)), closes [#164](https://github.com/kellymusk/Aframp/issues/164)
* add mobile navigation design documentation ([86b8ce2](https://github.com/kellymusk/Aframp/commit/86b8ce2ffe477f56b0b1ae0e5cf589de944817b9))
* add offramp flow documentation ([a2811fc](https://github.com/kellymusk/Aframp/commit/a2811fc1c6a0cb7fec6e802347a151bf597d28c3))
* add onramp flow documentation ([e046f7b](https://github.com/kellymusk/Aframp/commit/e046f7b922e133d0258803b6dee3944403f53bb4))
* add Portfolio page with asset breakdown, PnL, and net worth ([2447e6b](https://github.com/kellymusk/Aframp/commit/2447e6b9e2431658720499c2be3d9bc07f624f65)), closes [#177](https://github.com/kellymusk/Aframp/issues/177)
* add PostCSS configuration and global styles with Tailwind CSS ([5fb37ff](https://github.com/kellymusk/Aframp/commit/5fb37ff9c53cc501d259cf1e8cf754a958e9483e))
* add price alert modal ([0c26534](https://github.com/kellymusk/Aframp/commit/0c2653493c6b5574c27c067273593e560479c7f2))
* add price alert notifications ([4e6ffe1](https://github.com/kellymusk/Aframp/commit/4e6ffe154060a3e458d970b6610704a80a0f0c62))
* add PWA install prompt ([74503e2](https://github.com/kellymusk/Aframp/commit/74503e26775b242535cf2eeeedb30b9d72074b89))
* add referral program design documentation ([4ab0f9a](https://github.com/kellymusk/Aframp/commit/4ab0f9a54ae1077e29d3f132e751bd9dc5ca7497))
* add Sentry error tracking and security audit pipeline ([41f00cb](https://github.com/kellymusk/Aframp/commit/41f00cb69c2c6e803c2a3ee35d5d03448b6011e6))
* add settings page with profile, notifications, security (2FA), and connected wallets tabs ([8856542](https://github.com/kellymusk/Aframp/commit/8856542c17ac57519c5b5eda050380f3f24f1d85))
* add Stellar wallet provider and client-safe app layout ([03d1ec1](https://github.com/kellymusk/Aframp/commit/03d1ec1892d0d499bea182e929baceef422f6998))
* add team invites and API keys business features ([75dcc9c](https://github.com/kellymusk/Aframp/commit/75dcc9cc6d24531c88a03135c92d7c4c49f8cf88))
* add Zod schemas and test suite for all biller providers ([ba1c3c6](https://github.com/kellymusk/Aframp/commit/ba1c3c6a6baac6e1d5a23e5d79402392270b9142))
* **admin:** add gated admin panel with orders, KYC, and user views ([6aa13b5](https://github.com/kellymusk/Aframp/commit/6aa13b55797dd17b3e87df6c6245491ed189a8bf))
* Aframp branding ([32d6b35](https://github.com/kellymusk/Aframp/commit/32d6b351ff79211165be0d64a3dfb445546a82b3))
* **bills:** add bills payment receipt page with export functionality ([72ab07c](https://github.com/kellymusk/Aframp/commit/72ab07c6b892d9b285db89a877cffbd70e77f306))
* **bills:** add QR invoice generation and payment landing page ([524915c](https://github.com/kellymusk/Aframp/commit/524915c52cdab86a6a2463b2d0821efa5fcca7bc))
* **bills:** fix linting errors and remove unused imports ([914d982](https://github.com/kellymusk/Aframp/commit/914d982628a9e41beef2ebe87b7e73fe9c5669da))
* **bills:** jsPDF receipt download with embedded QR, print button, tx explorer ([567c0ee](https://github.com/kellymusk/Aframp/commit/567c0eef74e4af151a7b73d1277ee93b54829c88))
* **bills:** Scheduled Bill Payments spec  cron backend, payment vault, edit/cancel UI ([7b440a1](https://github.com/kellymusk/Aframp/commit/7b440a15255735d8d77f8107211b753828d36e5c))
* **ci:** Lighthouse CI autorun  90+ scores all categories ([d8e0cf9](https://github.com/kellymusk/Aframp/commit/d8e0cf99fc8fb202ac2e75eb43f54b24d66bf26f))
* enforce fiat withdrawal limits by KYC tier ([f078fd9](https://github.com/kellymusk/Aframp/commit/f078fd97ba68905b65518d83ccaa3e74dac5d4c7))
* enhance onramp success page with animations and comprehensive receipts ([282aa42](https://github.com/kellymusk/Aframp/commit/282aa422085b77107eea8490cc3e5d548c217fd0))
* error boundaries ([eaeddd1](https://github.com/kellymusk/Aframp/commit/eaeddd188123a140a315bc03cb13fbdd55235351))
* fix wallet hydration, add MSW tests, and update Jest coverage ([66ca5f5](https://github.com/kellymusk/Aframp/commit/66ca5f54ac44e59eec403f02259df4c3e6092a16))
* GitHub Actions CI workflow ([3671ddb](https://github.com/kellymusk/Aframp/commit/3671ddb61ace8c7bd855a2967be1e76f11c83e23))
* **growth:** Vercel Analytics events + split testing spec ([25a61c1](https://github.com/kellymusk/Aframp/commit/25a61c110810fa2deb5477d6f2af6197c6cc1d4a))
* **helpcenter:** Help Center with Algolia search  90+ Lighthouse scores ([7cbf96e](https://github.com/kellymusk/Aframp/commit/7cbf96ee6cd8e478e61a7a89a1ae9e486f6313f4))
* implement backend integration for onramp and offramp forms ([e16d1cc](https://github.com/kellymusk/Aframp/commit/e16d1cc1c107d11be7974747679c1c785897c22b))
* implement bank account verification ([a4262c8](https://github.com/kellymusk/Aframp/commit/a4262c8f77cf3e994b551e8afe6400c7ba0d849f))
* implement business ui design ([902ec2e](https://github.com/kellymusk/Aframp/commit/902ec2e62eb4f2346acea84c9cc68b4bcb074093))
* implement first purchase tutorial onboarding screen ([e13db32](https://github.com/kellymusk/Aframp/commit/e13db32f9697ad29e91a052751f1844a4812783c))
* implement off-ramp transaction success page with PDF receipt generation and sharing capabilities. ([1615a2a](https://github.com/kellymusk/Aframp/commit/1615a2a3306e71cd7decd1dbf70eee33d42ef6ac))
* implement onramp processing page with real-time status updates ([ad02eb7](https://github.com/kellymusk/Aframp/commit/ad02eb76d8148bf9ab56c5550c788165d3875ecf))
* implement premium visual overhaul and responsive layout enhancements for the bills module ([bfe5d9d](https://github.com/kellymusk/Aframp/commit/bfe5d9dea7db0d1e68d04f986eda658f430c957d))
* implement PWA install prompt with manifest and service worker ([9fe8ec4](https://github.com/kellymusk/Aframp/commit/9fe8ec44b48608c3fea6e5890845c4925f7506a4))
* implement real freighter wallet integration ([c58baac](https://github.com/kellymusk/Aframp/commit/c58baac7672a73a8342ac8f3129da635d0972654))
* implement recieve and send  page in app routes ([9f36e60](https://github.com/kellymusk/Aframp/commit/9f36e60110473ce3b4d450b863da0279d60fcf49))
* implement responsive filter panel with date presets and mobile bottom-sheet ([0cd46ab](https://github.com/kellymusk/Aframp/commit/0cd46ab83ac0e064e29a319cb45d20d8282309dc))
* implement settlement status page and fix hydration issues ([47c22a9](https://github.com/kellymusk/Aframp/commit/47c22a9926d010a0a50f714d49b5370dcf7549f8))
* implement signup OTP flow and verified badge ([ed982ee](https://github.com/kellymusk/Aframp/commit/ed982ee9ae8747f1bee570f8358a47949b7c368d))
* implement transaction history filters and charts ([f7fee0a](https://github.com/kellymusk/Aframp/commit/f7fee0a8458c0b5b02e85cc699fb12ca33f62456))
* implement user-add billers feature ([f50bfb2](https://github.com/kellymusk/Aframp/commit/f50bfb21e2a364c56ad11eed55ff9a7900d77497))
* integrate Paystack/Flutterwave for bill payments with receipt generation ([eb81667](https://github.com/kellymusk/Aframp/commit/eb8166752be703e34d7cc8a36029101af3c0583d))
* KYC flow in onboarding ([bfd6cf8](https://github.com/kellymusk/Aframp/commit/bfd6cf8503d88a19b1ab77d421c6fb1e485f54a3))
* **landing:** compose root page from existing components ([dfe144b](https://github.com/kellymusk/Aframp/commit/dfe144bc2a72053281ceb1a3333e4d5e7947f739))
* localstorage wallet persistence ([7104304](https://github.com/kellymusk/Aframp/commit/7104304489e016110838899163f7d37dfd4160fc))
* mobile nav — vaul drawer + bottom nav + gesture close ([82b8cf6](https://github.com/kellymusk/Aframp/commit/82b8cf6a0c1f27838c9ecbeae81084171ab59ccb)), closes [#176](https://github.com/kellymusk/Aframp/issues/176)
* **nav:** standardize nav pill style and active state ([30f21ee](https://github.com/kellymusk/Aframp/commit/30f21ee78eab576224b0ca0829628b464b5a9aa3))
* offline receipt support via IndexedDB cache ([c881a7d](https://github.com/kellymusk/Aframp/commit/c881a7de94d7a0b61d0bccc03dc5da36e0a14a05)), closes [#179](https://github.com/kellymusk/Aframp/issues/179)
* **offramp:** add offramp page and calculator for selling crypto ([a6ac9dc](https://github.com/kellymusk/Aframp/commit/a6ac9dc7acd0153db4cc2a88a6d9b79bb9c7a130))
* **offramp:** implement crypto offramp review flow and UI refinements ([279b873](https://github.com/kellymusk/Aframp/commit/279b873222303af731117a34c5c912f4339274d2))
* **offramp:** multi-currency calculator support ([#133](https://github.com/kellymusk/Aframp/issues/133)) ([8320841](https://github.com/kellymusk/Aframp/commit/832084145f662f3693437cb15fbf31e9f1b82f3c))
* **offramp:** refactor bank details flow with client components and wallet guard ([7379c58](https://github.com/kellymusk/Aframp/commit/7379c583fa4596bbb61814ac8bed74a8683af362))
* **onboarding:** implement welcome screen and feature highlights placeholder ([14b6ccf](https://github.com/kellymusk/Aframp/commit/14b6ccf037feb185522c6154837a980e346d4b80))
* **onramp:** add suspense fallback to payment and success pages ([7625ca4](https://github.com/kellymusk/Aframp/commit/7625ca4b56df8e1b33b7c161583e7ffb51b264e9))
* **onramp:** implement onramp page with fiat to crypto conversion (closes [#4](https://github.com/kellymusk/Aframp/issues/4)) ([bfed88a](https://github.com/kellymusk/Aframp/commit/bfed88ae33d56308a7a97725fdc9ac6eb585500f))
* **onramp:** implement payment page with order summary, payment status tracking, and countdown timer ([1cf37d1](https://github.com/kellymusk/Aframp/commit/1cf37d1f01c98ab456618a9edc29d751326acd35))
* **payments:** add M-Pesa STK Push and MTN MoMo mobile money integration ([f27b80c](https://github.com/kellymusk/Aframp/commit/f27b80c8c46a7210b3ccb940f0659e78a6b4bcfa))
* Receive-QR-code-generation ([2e089ef](https://github.com/kellymusk/Aframp/commit/2e089efdbe9d30d47532bdadcddc1fe47432a7a6))
* redesign transaction list and align CI checks ([3e0b168](https://github.com/kellymusk/Aframp/commit/3e0b168d39513c0320c413f773f5817736e31627))
* **referral:** add click tracking and conversion analytics ([#325](https://github.com/kellymusk/Aframp/issues/325)) ([5b181c0](https://github.com/kellymusk/Aframp/commit/5b181c06c61979f2dd780683d1b182e7c90de5db))
* **referral:** unique codes, backend tracking, 10% fee rebate on first ramp ([f34ba2d](https://github.com/kellymusk/Aframp/commit/f34ba2d3ef87a409bc5b2d01081af21acf7dd24b))
* **send:** implement Stellar P2P crypto transfer ([#131](https://github.com/kellymusk/Aframp/issues/131)) ([a16d8ec](https://github.com/kellymusk/Aframp/commit/a16d8ecf868ae4489a2ec8452d7153bf2df7b50a))
* setup CI CD pipeline ([289bb5e](https://github.com/kellymusk/Aframp/commit/289bb5e1a219897ddba7f4c32ec4a3cc8a008121))
* step 3 onboarding flow for wallet creation ([451c8d1](https://github.com/kellymusk/Aframp/commit/451c8d1cc79693fabe21ca7cda5401c5e43b79ae))
* swap interface ui ([53f6185](https://github.com/kellymusk/Aframp/commit/53f6185a51b5ac38fa171b9d875aae54c2e5126a))
* **swap:** integrate Stellar DEX aggregator with slippage, simulation, and tx preview ([7a2a34a](https://github.com/kellymusk/Aframp/commit/7a2a34a517d4f08d23952aadb609e14216681ce8))
* ui help center ([6d95de1](https://github.com/kellymusk/Aframp/commit/6d95de1b9f2db10fd0807831f8c9685c4ae07b25))
* ui price alert ([5537548](https://github.com/kellymusk/Aframp/commit/5537548a48bcc8c3996fff2fbbc8a3e39e717451))
* ui setting  page ([9cd0c66](https://github.com/kellymusk/Aframp/commit/9cd0c665ab9d961cf14efb5eaf20f0691909815d))
* ui transaction ([cdc1bcd](https://github.com/kellymusk/Aframp/commit/cdc1bcda7a5c21504151c2577d9fa5c1962e4e25))
* ui transcation state ([97cbf2e](https://github.com/kellymusk/Aframp/commit/97cbf2ee6234ad76eb9e8ce8f86475377e1e1bc9))
* ui wallet connection ([a3a7626](https://github.com/kellymusk/Aframp/commit/a3a762650c81fdc12e178b53f5b10176cf5e90d6))
* **ui:** theme-aware illustrations ([6d27893](https://github.com/kellymusk/Aframp/commit/6d27893f77afc7e1db2e64b5024f82b4e3e6ae35))
* update PWA install components and hooks ([5cd3dd9](https://github.com/kellymusk/Aframp/commit/5cd3dd9d36f0f2749439339e27af870692a6798d))
* **ux:** add skeleton loading states to balance cards and transaction history ([92664b3](https://github.com/kellymusk/Aframp/commit/92664b3285fc3f90386753a2e54d5ef4bf3923f3)), closes [#321](https://github.com/kellymusk/Aframp/issues/321)
* **ux:** add transaction explorer links to history component ([b671dff](https://github.com/kellymusk/Aframp/commit/b671dffdf14747b03ea895cf78f2e35e23ca5ec2))
* validation on mock stellar addresses ([84b994c](https://github.com/kellymusk/Aframp/commit/84b994c809e9dd4feab662139ff42c77091ee6ac))
* **wallet:** add wallet management and switch to Freighter ([b366f3e](https://github.com/kellymusk/Aframp/commit/b366f3ee7e5a2beb1724f352233a786f6d75b995))


### Bug Fixes

* add empty states for transactions and bills views (closes [#175](https://github.com/kellymusk/Aframp/issues/175)) ([1b355ac](https://github.com/kellymusk/Aframp/commit/1b355ac7f3278714fdbcb0559bb45421d0c1746d))
* **bills:** final linting and logic cleanup for Wave 3 ([302eb4f](https://github.com/kellymusk/Aframp/commit/302eb4fbdde19ac70a4562a56c85b86faabaa6c5))
* ci lint fix ([4f10464](https://github.com/kellymusk/Aframp/commit/4f104643c11843a947dc36af2f79ad9550237a81))
* **ci:** fix Lighthouse CI run failures ([0b5f11f](https://github.com/kellymusk/Aframp/commit/0b5f11f11640ecc32a8f659db1a7cf3b9947281e))
* **ci:** skip preview deploy when Vercel secrets missing, fix uptime monitor noise ([3d2eb70](https://github.com/kellymusk/Aframp/commit/3d2eb70ee10b85209ac199deeee9a80fee8674b1))
* exclude helpcenter vitest suite from root Jest runner ([bdf3eb9](https://github.com/kellymusk/Aframp/commit/bdf3eb9a6edfce679887b6e232dbd3d3cb595269))
* fixed theme toggle and wallet address position ([ed75968](https://github.com/kellymusk/Aframp/commit/ed759688ebce04e8477a97ab6815bc80c5b2d713))
* implement demo mode security for wallet connections ([973ab87](https://github.com/kellymusk/Aframp/commit/973ab873ad7f1dfe075fe551423469de3c264987))
* make WalletModal responsive with touch-friendly UI and mobile bottom-sheet (closes [#136](https://github.com/kellymusk/Aframp/issues/136)) ([af9e7b5](https://github.com/kellymusk/Aframp/commit/af9e7b573da04ef003d2972fb8b70c16012b6f88))
* resolve all ESLint and TypeScript errors for CI/CD pipeline ([abbe716](https://github.com/kellymusk/Aframp/commit/abbe7162a0c54fa5ab0e99c56fb40b887f10ad76))
* resolve conflicts and apply final formatting ([bab189b](https://github.com/kellymusk/Aframp/commit/bab189b718df1c420db0c5d99a8dcebd3e31db24))
* resolve landing/bills routing, icon rendering, and global wallet sync ([781577a](https://github.com/kellymusk/Aframp/commit/781577a45bfa82ab83f4de712ed965b58d466c4c))
* resolve pre-commit hook issues for offramp success page ([eff2e1e](https://github.com/kellymusk/Aframp/commit/eff2e1e61a5a480d62717e68cf5448cb85499886))
* resolve pre-commit hook issues with temporary override ([0b74be3](https://github.com/kellymusk/Aframp/commit/0b74be36d6abe9fe85244e186d70c3cdc0a9b913))
* resolve test failures and exclude helpcenter from jest ([b06372c](https://github.com/kellymusk/Aframp/commit/b06372c11020c5b834bcf39705221bbf9cb395ca))
* **types:** update next-env import path for routes types ([2587eec](https://github.com/kellymusk/Aframp/commit/2587eecff76d14e1c7765afc38d48c86b113a08a))

## [1.0.0] - 2026-07-29

### Added
- **Core Platform Features**: Onramp, Offramp, P2P transfers, and Bill payment flows.
- **Stellar Horizon Integration**: Smart contract streaming and automated Stellar payment settlement.
- **Fiat Payment Gateways**: Full integrations for Paystack, M-Pesa Daraja (STK Push), and MTN MoMo.
- **KYC Verification System**: Document and selfie upload flow, verification status polling, and tiered withdrawal limits.
- **Business Suite**: Team invites, API key management dashboard, and webhooks.
- **Notifications & Price Alerts**: Real-time notifications and crypto price tracking alerts.
- **CI/CD Pipeline**: GitHub Actions for automated testing, linting, security scanning (Snyk, OWASP), and deployment previews.
- **System Documentation**: Comprehensive guides for CI/CD, environment variables, architecture overview, and payment integrations.
