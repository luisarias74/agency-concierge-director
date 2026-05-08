# Examples: Specialist Output Benchmarks

This file provides the gold standard for how the Director should process messy data into clinical operational intelligence.

## Example 1: The "Flash Delivery" Onboarding (The Diagnostic Audit)

### 1. Raw Messy Intake (Context Layer)
**Source:** Sales Call Notes
"Just closed Flash Delivery. $3,500/mo. They are super hyped and want to start tomorrow. They want 'more customers' but don't have a specific number yet. Their website is live but the founder lost the login. He said his cousin has the logo files but he’s on vacation. We need to get ads running ASAP because they have a big event in 10 days."

### 2. Director’s Internal Reasoning (Reasoning Layer)
- **Revenue Potential:** $3,500 is mid-tier (10/20).
- **Strategic Clarity:** "More customers" is not a goal; it's a wish (4/20).
- **Asset Readiness:** No website access, no logo (3/20).
- **Risk Profile:** ASAP Syndrome + Missing Assets + Urgent Deadline (3/20).

### 3. The Director’s Brief (Governance Layer)
**Score: 30/100 — 🔴 Red Light (Hold)**

**The Gap (What is Missing):**
- **Numeric Success Metric:** No defined 90-day ROI target.
- **Technical Access:** No WordPress/Shopify login; no Domain access.
- **Brand Identity:** No high-res logo or brand guidelines.

**🚩 Red Flags Triggered:**
- **ASAP Syndrome:** Demand to start "tomorrow" with a 10-day hard deadline is high-risk.
- **Vague Metrics:** "Get more customers" fails the numeric accountability test.
- **Technical Hostage:** Founder does not own his own access points.

**Recommendation: CLARIFY**
This is not a "No," but a "Not Yet." Do not move to the Execution Layer. Building on this foundation will result in agency overhead and high churn risk.

### 4. Slack Approval Payload (Execution Layer)
**New Client: Flash Delivery**
**Score:** 30/100 🔴
**Flags:** ASAP Syndrome • Vague Metrics • Technical Hostage
**Note:** $3,500/mo deal. Strategy is built on sand. Founder lacks logins and clear goals. Recommend a 30-min discovery call to secure access and define a numeric "Win" before we open a Slack channel.
[Approve] [Clarify] [Hold]

### 5. Post-Approval Logic (Memory Layer)
*If [Approve] is eventually triggered:*
- Create Google Drive: `/Clients/Flash-Delivery`
- Setup Slack: `#client-flash-delivery`
- Dispatch Gmail: "Technical Access & Brand Asset Checklist" to Founder.
 
