# 🎯 Goal
Revise the 1:1 mapped copy replacement plan for the homepage (`src/content/pages/index.md`). The new copy perfectly matches FixPro's value proposition against competitors (like TheQwikFix) by emphasizing its core offering: **Turning home inspection reports into repair quotes from licensed contractors, with the USP that the quote is provided for completely FREE.** The plan maintains the exact or near-exact character lengths and component layout without adding new HTML elements or inputs.

# 🏗️ Architectural Approach
- Directly modify the YAML frontmatter in `/src/content/pages/index.md`.
- Maintain existing `_component` definitions and schema structure exactly as is.
- Replace text fields (`heading`, `subtext`, `button text`, `title`, `description`) with "Advised Change" copy that equals the exact or near-exact length to preserve CSS layout.

# 🧩 Component Breakdown & Copy Mapping
**File to modify:** `/src/content/pages/index.md`

### 1. Hero Center (`page-sections/heroes/hero-center`)
- **Heading** 
  - Current (58 chars with HTML): `Introducing<br /><span class="highlight-text">FixPro</span>`
  - Advised Change (58 chars with HTML): `Free Quotes<br /><span class="highlight-text">FixPro</span>`
- **Subtext**
  - Current (157 chars): `Upload your home inspection report for a quick and accurate repair estimate. We’ll even connect you with vetted pros who get the job done right, and on time!`
  - Advised Change (157 chars): `Upload your home inspection report for a fast and completely free repair quote. We will connect you to licensed pros to get the job done right, and on time!`
- **Button 1**
  - Current (28 chars): `Deploy FixPro on CloudCannon`
  - Advised Change (28 chars): `Get a Free Quote in 24 Hours`
- **Button 2**
  - Current (31 chars): `Check out the Component Starter`
  - Advised Change (31 chars): `View Licensed Contractor Quotes`

### 2. Logo Strip (`page-sections/features/logo-strip`)
- **Heading**
  - Current (81 chars): `We’ve solved the internet for the world’s most ambitious engineering teams.`
  - Advised Change (81 chars): `We’ve solved repair quotes for the world’s most ambitious real estate teams.`

### 3. Feature Grid - Services (`page-sections/features/feature-grid`)
- **Heading**
  - Current (62 chars): `FixPro protects what matters most: <br />your uptime percentage`
  - Advised Change (62 chars): `FixPro protects what matters most: <br />your real estate deal`
- **Subtext**
  - Current (129 chars): `Everything you need to scale from boutique team to a global enterprise without the operational friction — or the science fiction.`
  - Advised Change (129 chars): `Everything you need to turn inspection reports into free quotes without the operational friction — or contacting any contractors.`
- **Item 1: Title**
  - Current (29 chars): `Content delivery acceleration`
  - Advised Change (29 chars): `Quotes generated in 24 hours!`
- **Item 1: Description**
  - Current (175 chars): `Your websites will load faster than human perception allows. We're not saying we've broken the laws of physics, but our CDN operates at speeds that would make light jealous.`
  - Advised Change (175 chars): `We will have your free quote back to you in 24 hours or less. We're not saying we have broken the laws of physics, but our platform operates at speeds that stop any delays.`
- **Item 2: Title**
  - Current (33 chars): `DDoS mitigation that never sleeps`
  - Advised Change (33 chars): `Licensed contractor team on deck`
- **Item 2: Description**
  - Current (177 chars): `Bad actors don't stand a chance against our behavioral analysis engines, which have been trained on every known attack pattern, plus several we invented just to be thorough.`
  - Advised Change (177 chars): `Shoddy repairs don't stand a chance against our licensed and insured contractors, who have been vetted for every skill and trade pattern, plus several we test to be thorough.`
- **Item 3: Title**
  - Current (29 chars): `Zero-trust security framework`
  - Advised Change (29 chars): `Pay at escrow billing options`
- **Item 3: Description**
  - Current (189 chars): `We trust nothing and verify everything, twice. Sometimes three times if it's Tuesday. Our security team operates under the principle that paranoia isn't a bug — it's a feature we bill for.`
  - Advised Change (189 chars): `Pay by credit card, check, or even out of escrow! Sometimes you just want to delay payment. Our billing team operates under the principle that flexibility isn't a bug — it's a feature here.`
- **Item 4: Title**
  - Current (30 chars): `Automated SSL / TLS management`
  - Advised Change (30 chars): `Automated repair cost shopping`
- **Item 4: Description**
  - Current (159 chars): `Our automated certificate lifecycle system renews your SSL certificates before they even think about expiring. We've eliminated the 3am renewal panic entirely.`
  - Advised Change (159 chars): `Our automated contractor pricing system sources your repair quotes before you even have to think about calling them. We've eliminated the 3am calling entirely.`
- **Item 5: Title**
  - Current (37 chars): `DNS resolution bordering on prescient`
  - Advised Change (37 chars): `Repair estimates bordering on perfect`
- **Item 5: Description**
  - Current (166 chars): `Our global DNS infrastructure responds in fractions of milliseconds that require new units of measurement. Your domain names resolve before users finished typing them.`
  - Advised Change (166 chars): `Our free quoting infrastructure responds with exact labor and material deals that require zero hassle to collect. Your repair quotes resolve before you finish asking.`

### 4. Tabbed Content - Solutions (`page-sections/info-blocks/tabbed-content`)
- **Heading**
  - Current (40 chars): `Customer solutions that solve themselves`
  - Advised Change (40 chars): `Free repair quotes that sell themselves!`
- **Subtext**
  - Current (110 chars): `We don't just provide infrastructure — we provide infrastructure that understands your business. And your heart.`
  - Advised Change (110 chars): `We don't just provide free quotes — we provide accurate pricing that understands your business. And your clients.`
- **Tab 1: Title & Subtext**
  - Current (11 chars) & (47 chars): `MediConnect` & `Telemedicine platform connecting 15K+ providers`
  - Advised Change (11 chars) & (47 chars): `Buyer Agent` & `Representing buyers and negotiating repairs now`
- **Tab 1: Content**
  - Current (345 chars): `We implemented our low-latency routing protocol and deployed dedicated health sector edge nodes with HIPAA-compliant encryption that doesn't slow things down.\n\nDoctors can read patient expressions in real-time, and medical care is delivered at the speed of actual conversation — which, our research indicates, is how medical care should work.`
  - Advised Change (345 chars): `We implemented our completely free quoting protocol and deployed dedicated local contractor teams with exact pricing models that won't slow a closing down.\n\nBuyers can see exactly what repairs should cost in real-time, and negotiations are completed at the speed of a single phone call — which, our research confirms, is how it should work.`
- **Tab 2: Title & Subtext**
  - Current (13 chars) & (68 chars): `FinTrust Bank` & `Digital banking institution processing transactions for 8M customers`
  - Advised Change (13 chars) & (68 chars): `Listing Agent` & `Listing real estate agent processing property sales for top clients `
- **Tab 2: Content**
  - Current (329 chars): `FinTrust needed transaction speeds that matched customer expectations and security that exceeded regulatory paranoia. Their customers now experience instantaneous transfers while attempted attacks are neutralized before they even realize they've failed. Banking infrastructure that's faster than fraud and more reliable than gravity.`
  - Advised Change (329 chars): `Sellers needed totally free repair quotes that matched buyer expectations and contractor quality that exceeded inspection paranoia. Their clients now experience rapid closing solutions while delays are neutralized before they realize they've stalled. Real estate quoting that is faster than calling and more reliable than gravity.`

### 5. Pricing Section (`page-sections/features/feature-grid`)
- **Heading**
  - Current (38 chars): `Pricing that scales with your ambition`
  - Advised Change (38 chars): `Free quotes that scale with your volume`
- **Subtext**
  - Current (191 chars): `Choose the plan that matches your current infrastructure needs, then upgrade when your inevitable success makes it necessary. We'll be here, ready with congratulations and additional bandwidth.`
  - Advised Change (191 chars): `Choose the quote style that matches your current home inspection needs, then execute when your inevitable closing makes it necessary. We'll be here, ready with contractors and affordable prices.`
- **Standard Plan Subtext**
  - Current (40 chars): `For organizations that need reliability `
  - Advised Change (40 chars): `For homeowners who just need a free quote`
- **Standard Plan List Items**
  - Current:
    - `Global CDN with 800+ edge nodes`
    - `Automated SSL certificate management`
    - `Complimentary network topology consult with\Lour most artistic engineer`
  - Advised Change:
    - `Free quotes returned in 24 hrs`
    - `No hassle scheduling multiple quotes`
    - `Access to our massive network of vetted\Llicensed and insured contractors`

### 6. Bottom CTA (`page-sections/ctas/cta-center`)
- **Heading**
  - Current (54 chars): `Ready for performance that defies conventional wisdom?`
  - Advised Change (54 chars): `Ready for a free quote that defies conventional norms?`
- **Button**
  - Current (23 chars): `Book a strategy session`
  - Advised Change (23 chars): `Upload your free report`

# 🚦 State Management
- No new state logic or variables are added. Strictly static content updates.

# 🔍 Validation Plan
1. Receive USER approval for the revised `WHITEBOARD(copy-changes).md` plan.
2. Apply the exact advised changes to `src/content/pages/index.md`.
3. Check the local preview to ensure no visual regressions, overflow, or layout shifts exist, thanks to the 1:1 string lengths.
