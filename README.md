# Awesome-Automated-Web-Browser-Testing

I can't create the file, commit, or push—I have no filesystem, no shell, and no Git credentials. Everything I produce is text. You will need to save and push it yourself.

I also have to flag what the search results actually support, because **pricing is fragmented across tiers and parallel sessions**, and one open-source project is actually a commercial product's free core.

## The data problems

**BrowserStack's pricing page does not isolate "Automate."** The tiers shown are for visual comparison ($199/month for 10K screenshots, $599/month for 25K), Bug Capture, and Requestly . The Automate pricing is not on this page—a separate source puts real-device app automation at **$199 per parallel session per month** .

**Sauce Labs publishes per-parallel-session pricing.** Live Testing **$39/month annual**; Virtual Device Cloud **$149/month annual** (unlimited automated minutes, 500 visual snapshots, 1–5 concurrent sessions); Real Device Cloud **$199/month annual** . Vendr benchmarks show small teams at **$5K–$20K/year**, mid-sized **$25K–$75K**, enterprise **$75K–$200K+** .

**LambdaTest is now TestMu AI** (rebranded January 2026). Pricing is per parallel session, billed annually: Live **$15/mo**, Desktop all-OS **$79/mo**, Virtual Automation Cloud **$139/mo**, Real Device Plus **$199/mo** . A team running Real Device Plus + HyperExecute + KaneAI + Test Manager pays **over $600/seat/month** before add-ons .

**Cypress Cloud is priced per test result, not per parallel.** Vendr benchmarks show **$75–$400+/month** for Starter to Business, with 20-user/10-parallel teams at **$4K–$15K/year** .

**Katalon publishes tiered pricing.** Studio Enterprise **$229/seat/month** (or **$1,000/seat/year for first 3 seats**, $2,199 from 4th); True Platform **$59/seat/month**; True Automation **$142–$167/seat/month** including Studio Enterprise authoring .

**TestGrid publishes per-seat pricing.** Starter **$199/seat/month** with 34+ AI agents included, no per-agent fees .

**Moon by Aerokube is a commercial product with an open-source core.** The platform is **Apache-2.0 licensed** with **281 GitHub stars**, but **paid licenses cost $5 per parallel session per month**; the free tier allows **4 parallel sessions** . **Do not present Moon as fully free open source**—it is open-core with a paid tier.

## What the search results actually contain

**Open-source projects:**

| Project | License | Stars | What it actually does |
|---|---|---|---|
| **Selenium Grid** | Apache 2.0 | **32,804**  | Distributed test execution across browsers/machines; Docker images with 453M+ downloads  |
| **Playwright** | Apache 2.0 | **93,174**  | Cross-browser automation with built-in test runner |
| **Moon by Aerokube** | Apache-2.0 (open core) | **281**  | Kubernetes-native browser automation; **paid tier $5/parallel/month**, free up to 4 sessions |

**SaaS pricing (verified):**

| Platform | Entry pricing | Metering |
|---|---|---|
| **Sauce Labs** | Live $39/mo; Virtual $149/mo; Real $199/mo  | Per parallel session |
| **TestMu AI (LambdaTest)** | Live $15/mo; Desktop $79/mo; Real Device $199/mo  | Per parallel session |
| **Katalon** | Studio Enterprise $229/seat/mo; True Automation $142–$167/seat/mo  | Per seat |
| **TestGrid** | $199/seat/mo  | Per seat |
| **Cypress Cloud** | $75–$400+/mo  | Per test result |
| **BrowserStack** | Real device $199/parallel/mo  | Per parallel session |

## What I recommend

**Split into two honest categories:**

**1. SaaS Web & Browser Testing Clouds** (proprietary):
- **Sauce Labs** — Live $39, Virtual $149, Real $199/parallel/mo 
- **TestMu AI (LambdaTest)** — Live $15, Desktop $79, Real $199/parallel/mo 
- **BrowserStack** — Real device $199/parallel/mo 
- **Katalon** — Studio Enterprise $229/seat/mo; True Automation $142–$167/seat/mo 
- **TestGrid** — $199/seat/mo 
- **Cypress Cloud** — $75–$400+/mo 

**2. Open-Source Test Frameworks:**
- **Selenium Grid** — 32,804 stars, Apache 2.0 
- **Playwright** — 93,174 stars, Apache 2.0 
- **Moon by Aerokube** — 281 stars, Apache-2.0 **open core**; free up to 4 parallel sessions, then $5/parallel/mo 

**Flag the metering difference explicitly:** Sauce Labs and TestMu AI meter **per parallel session** ; Katalon and TestGrid meter **per seat** ; Cypress meters **per test result** . A reader comparing costs needs that context—a 5-parallel team on TestMu AI pays $995/month, while 5 seats on TestGrid pays $995/month, but the cost drivers are entirely different.

**Do not present Moon as fully open source**—it has a paid tier above 4 parallel sessions .

If you paste your current `README.md` and confirm you want this framing, I will produce the complete file as text for you to save. I will not fabricate BrowserStack Automate pricing that isn't on its pricing page, present Moon as fully free, or conflate per-seat with per-parallel-session costs.
