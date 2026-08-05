## Raquel Mijares

Developer in Calgary. I work on the parts of a product that get audited: payments, kids privacy, ad attribution, security compliance.

Five companies in six years, and every one of them had someone outside checking the output. Auditors at Tugboat, emissions regulators at Validere, and now Stripe, the ad networks, a children's privacy certification body and the DRM licensors, all at once.

### 🔎 What I tend to find

The failures nobody instrumented. Three that were mine:

* A **500 on every URL carrying a query string.** Every paid campaign link to the home page was dead. The bare URL returned 200, so monitoring stayed green and nobody knew.
* **Ad beacons double firing**, quartile events counted twice, inflating the view numbers being sold against.
* A **deploy pipeline that had been failing silently for six weeks** on a product I had just inherited.

I learned this in production engineering before I learned it in software. A process failing quietly is still failing, and somebody has to reconstruct why afterwards.

### ⚡ Now

**APMC** · Software Developer · since Sep 2024
Two streaming brands on one Nuxt monorepo, plus a smart TV app, the native mobile releases and a Flutter desktop tool the broadcast operators use during live games. **849 pull requests merged, 458 reviewed for other people.**

* **Payments.** Stripe checkout and subscriptions, mostly the ugly parts: the script fails to load, the page restores from cache, the plan gets lost in login, someone deletes an account that still has an active sub.
* **Attribution.** Meta CAPI and TikTok. Keeping last click honest across fbclid and UTM so organic doesn't take credit for paid.
* **Playback.** DRM, and recovering from it when it fails. Seeking on DVR and VOD. Captions that stay off when you turn them off.
* **Compliance.** kidSAFE COPPA, and consent across web and TV.
* **Server side.** Node API routes, and picking what renders where across SSR, ISR and SPA.
* **Shipping.** I cut the releases. Last four went out across four AWS accounts.

### 🗂 Before

**Kettl** · Software Engineer · 2023 to 2024
Live event production management, where the deadline is the auditor. User management, production control, workforce tracking, and the GraphQL side so data came in live instead of by hand. React, Next.js, Apollo, Prisma, Postgres.

**Validere** · Software Developer · 2023
Emissions reporting for oil and gas, replacing a lot of spreadsheets. Roles and permissions screens, plus the change log, which is the artifact an emissions audit actually asks for. React, TypeScript, Storybook, Vercel.

**Tugboat Logic** (bought by OneTrust) · Front End Developer · 2021 to 2023
Security compliance across SOC 2, ISO 27001, GDPR and HIPAA. I built the tooling companies use to survive an audit: dashboard features, version comparison across audit cycles, and a component library in Storybook. Stayed through the acquisition. React, TypeScript, Redux, Cypress.

**InceptionU** · Full Stack Developer · 2020 to 2021
Where I started. Real projects for real clients. Node.

**Before software** · 2016 to 2020
Project coordination, procurement and inventory across three Calgary companies. A wrong number there is a physical shortage, not a failed test.

### 🧰 Stack

**Languages** TypeScript · JavaScript · Dart
**Frameworks** Vue 3 · Nuxt · React · Next.js · Flutter · Node
**Data** Pinia · Redux · Apollo GraphQL · Prisma · PostgreSQL
**Testing** Vitest · Playwright · Cypress · React Testing Library · MSW · Storybook
**Infra** AWS · Docker · Vercel · GitHub Actions
**Analytics** GA4 · Google Tag Manager · Meta CAPI

### 🔗 Elsewhere

BSc in Production Engineering, Universidad Metropolitana · ISO 13485 quality management · [LinkedIn](https://www.linkedin.com/in/raquelmjrs/)
