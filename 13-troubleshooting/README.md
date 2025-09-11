# Troubleshooting

### Common Issues and Fixes

Surfgeo provides diagnostic tools to help you resolve common issues that may arise when tracking GEO performance.

***

### 1. No Mentions Detected

**Symptoms:**

* Your brand shows “0 mentions” for certain prompts or topics.
* Competitors appear, but your brand does not.

**Possible Causes & Fixes:**

* **Tracking Scope Too Narrow** → Expand tracked prompts to cover broader phrasing.
* **Alias Coverage Missing** → Add alternate spellings, subdomains, and product-level terms.
* **Content Relevance Gap** → Ensure your content addresses the exact query intent (update page structure, add FAQ-style answers).

***

### 2. Duplicate Mentions

**Symptoms:**

* The same brand mention appears multiple times, inflating counts.

**Possible Causes & Fixes:**

* **Alias Overlap** → Review alias management and remove duplicates.
* **Multi-Domain Tracking Conflict** → Merge legacy domains or microsites under a single identity.
* **LLM Redundancy** → Systematically apply Surfgeo’s duplicate-detection logic; if still unresolved, file a support ticket.

***

### 3. GA4 Mismatch

**Symptoms:**

* Surfgeo mentions or visibility counts don’t align with **Google Analytics 4 traffic data**.

**Possible Causes & Fixes:**

* **Different Measurement Scopes** → Surfgeo tracks _AI mentions_ (visibility), GA4 tracks _traffic_. A high visibility score won’t always drive equivalent traffic.
* **Attribution Windows** → Check if GA4 attribution settings (7-day, 30-day) align with Surfgeo analysis windows.
* **URL Parameter Handling** → Ensure UTM codes and canonical URLs are properly tracked in GA4.
* **Fix:** Use Surfgeo’s **Attribution Reconciliation Report** to align metrics between systems.
