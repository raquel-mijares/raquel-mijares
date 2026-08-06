## Raquel Mijares

Developer in Calgary. I work on the parts of a product that get audited: payments, kids privacy, ad attribution, security compliance.

Five companies in six years and every one of them had someone outside checking the work. Auditors at Tugboat, emissions regulators at Validere, and now Stripe, the ad networks, a kids privacy certification body and the DRM licensors, all at once.

Most of what I do is make those parts hard to get wrong. One source of truth instead of five copies, dead code deleted, and tests around the things that cost money if they break. Over two years I have deleted almost as many lines as I have written.

### ⚡ Now

**APMC** · Software Developer · since Sep 2024
Streaming for two brands on one Nuxt monorepo, plus a smart TV app, the native mobile releases and a Flutter desktop tool the broadcast operators use during live games. **849 pull requests merged, 458 reviewed for other people.**

* **Payments.** Stripe checkout and subscriptions, mostly the ugly parts: the script fails to load, the page restores from cache, the plan gets lost in login, someone deletes an account that still has an active sub.
* **Attribution.** Meta CAPI and TikTok. Keeping last click honest across fbclid and UTM so organic doesn't take credit for paid.
* **Ad beacons.** Deduplication and quartile correctness, so what gets reported matches what actually played.
* **Playback.** DRM, and recovering from it when it fails. Seeking on DVR and VOD. Captions that stay off when you turn them off.
* **Compliance.** kidSAFE COPPA, and consent across web and TV.
* **Server side.** Node API routes, and picking what renders where across SSR, ISR and SPA.
* **Simplifying.** Platform detection centralized. A dual auth store replaced with one source of truth. AdobePass moved out of the shared layer. Plan config derived from one list instead of IDs scattered everywhere. Moved both brands onto dialogs, then deleted the old modal stack.
* **Releases.** I cut them. The last four went out across four AWS accounts.

### 🗂 Before

**Kettl** · Software Engineer · 2023 to 2024
Live event production management. User management, production control, workforce tracking, and the GraphQL side so data came in live instead of by hand. React, Next.js, Apollo, Prisma, Postgres.

**Validere** · Software Developer · 2023
Emissions reporting for oil and gas, replacing a lot of spreadsheets. Roles and permissions screens, plus a change log so people could see what had been edited. That is what gets asked for when the numbers are audited. React, TypeScript, Storybook, Vercel.

**Tugboat Logic** (bought by OneTrust) · Front End Developer · 2021 to 2023
Security compliance across SOC 2, ISO 27001, GDPR and HIPAA. Dashboard features, version comparison for audit workflows, and a component library in Storybook. React, TypeScript, Redux, Cypress.

**InceptionU** · Full Stack Developer · 2020 to 2021
Where I started. Real projects for real clients. Node.

**Before software** · 2016 to 2020
Project coordination, procurement and inventory across three Calgary companies.

### 🧰 Stack

**Languages** TypeScript · JavaScript · Dart
**Frameworks** Vue 3 · Nuxt · React · Next.js · Flutter · Node
**Data** Pinia · Redux · Apollo GraphQL · Prisma · PostgreSQL
**Testing** Vitest · Playwright · Cypress · React Testing Library · MSW · Storybook
**Infra** AWS · Docker · Vercel · GitHub Actions
**Analytics** GA4 · Google Tag Manager · Meta CAPI

### 🔗 Elsewhere

BSc in Production Engineering, Universidad Metropolitana · ISO 13485 quality management · [LinkedIn](https://www.linkedin.com/in/raquelmjrs/)
