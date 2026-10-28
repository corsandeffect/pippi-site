# PIPPI: Sensory Screen Tint & Contrast Suppressor

A health-first accessibility tool that applies a sensory shield with ambient screen tints, contrast suppression and layout motion freeze for help with eye strain and migraines. Transform your Chrome browser into a gentle, non-intrusive workspace, allowing you to surf and work more comfortably. 

---

## 🛡️ Key Features
* **Out-of-the-Box Relief:** Get immediate sensory relief across a predefined list of over 50 of your favorite platforms, grouped logically for instant protection (for the full list of automatically supported sites, please visit our website [GitHub.io]):
     — Search Engines: Google, Yahoo, DuckDuckGo;
     — AI Platforms: ChatGPT, Claude, and OpenAI;
     — Articles & Forums: Wikipedia, Medium, and Reddit.

* **Sensory Profiles:** Toggle seamlessly between specialized modes. Choose Day Focus for soft-light filtering, Sensory Guard for medium protection, or Deep Calm for advanced multi-layer dimming and layout motion freeze.

* **Layout Motion Freeze (Deep Calm):** Instantly forces CSS animations, smooth-scrolling behaviors, and transition flashes to zero duration — an absolute necessity for mitigating vestibular nausea and sensory strain.

* **Manual Calibration Sliders:** Tailor your environment in real-time with precise slider controls for Tint Warmth and background-dyeing Contrast Suppression.

* **Selective Pause:** Temporarily pause PIPPI on a specific predefined site without needing to toggle off the entire extension.

* **My Custom Sanctuary (20 Slots):** Extend PIPPI's protection beyond our predefined list. Dynamically save and lock your custom calibration settings onto up to 20 additional websites (like personal blogs or local reading domains).

---

## 💡 How To Get Started
1. Click 'Add to Chrome' and pin **PIPPI** to your toolbar.

2. Open **PIPPI** and select your preferred **Sensory Profile** (Day Focus, Sensory Guard, or Deep Calm).

3. If a website is on our predefined list, **PIPPI** applies automatically.

4. To protect a site outside the list, simply click **'Save to Sanctuary'**.

5. Keep surfing!

***Additional Permissions:** When saving a site to My Custom Sanctuary, Chrome will ask you to allow additional permissions. This is strictly required so PIPPI can apply its protective styles to that specific domain. We **do not** track, collect, or view any of your data or browsing activity.

---

## 📞 Support & Feedback
If you encounter any bugs, have feature requests, or need technical assistance, please reach out via email:

**Email:** mailto:corsandeffect@gmail.com

---

## 🔒 Privacy Policy
Last Updated: October 28, 2026

PIPPI ("we," "our," or "the extension") is a health-first browser extension designed to provide ambient screen tinting, contrast suppression, and layout motion freeze controls for users dealing with chronic migraine, severe sensory hyperactivity, eye strain, photophobia, and vestibular disorders.
We take user privacy with the utmost seriousness and confirm that PIPPI **does not** collect, store, transmit, or monetize your personal data.

### 1. Data Handling
To provide its core functionality, PIPPI interacts with two specific types of data: **User Activity** and **Website Content**.

* **E-Commerce Scraping Scope:** The extension only reads web page content when a user actively triggers a script generation while viewing a supported URL (**Amazon (.com, .co.uk, .ca)** or **TikTok Shop** product listing pages).

* **Data Fields Extracted:** Extraction is strictly limited to public product metadata required to build the script deck, including **product names, core technical specifications, and listed features**.

* **No PII or Tracking**: The extension **does not** read, collect, store, transmit or monetize any of your personal data or browsing activity.
  
### 2. Local Processing & Data Retention
We believe in absolute data minimization. **We do not run a central database or external developer server.** 

* **Zero Server Footprint:** None of your extracted product text, selected structure settings or generated script drafts are ever transmitted to, or stored on, an external server owned by the developers.

* **Local Storage Limits:** Extracted product metadata, user-configured structure templates, and the active script deck are stored entirely within your browser's local sandbox using the chrome.storage.local API.

* **Volatile & Persistent States:** Your API keys and custom configuration settings remain securely in local storage until you manually delete them or uninstall the extension. Active script text and extracted product data are treated as temporary working assets; they live on your device and can be cleared instantly by resetting the panel or clearing your browser cache.

### 3. API Key Security & Network Sandbox
* **Storage Encryption:** Your personal API keys are saved locally on your device using the browser's isolated native sandbox structure.

* **Network Isolation:** The extension operates under a strict **Content Security Policy (connect-src)**. It cannot send information to unauthorized third-party trackers, marketing endpoints, or developer analytics servers.

* **Direct-to-API Transmission:** Your user-selected framework choices, extracted product details, and API keys travel securely and exclusively via encrypted HTTPS connections directly to the official AI infrastructure endpoints:
  * OpenAI (`https://api.openai.com*`)
  * Anthropic Claude (`https://api.anthropic.com*`)
  * Google Gemini (`https://generativelanguage.googleapis.com*`)

### 4. Third-Party Disclaimers
Because DeckBro AI utilizes a Bring Your Own Key (BYOK) architecture, your user-selected framework choices, extracted product descriptions, and generation habits are governed directly by the respective developer terms of service and data privacy agreements of the platforms you choose to connect:
* [OpenAI](https://openai.com/policies/row-privacy-policy/)
* [Anthropic Claude](https://www.anthropic.com/legal/privacy)
* [Google Gemini](https://support.google.com/gemini/answer/13594961?hl=en)

### 5. Policy Updates & Compliance
Any future updates to this policy will be posted transparently on this page. For inquiries regarding data handling or code review verification, please contact us at: corsandeffect@gmail.com.

---

Privacy Policy for PIPPI: Sensory Screen Tint & Contrast Suppressor

Effective Date: October 15, 2026
Last Updated: October 15, 2026
PIPPI ("we," "our," or "the extension") is a health-first browser extension designed to provide ambient screen tinting, contrast suppression, and animation controls for users dealing with photophobia, chronic migraines, eye strain, and vestibular disorders.
We take user privacy with the utmost seriousness. This Privacy Policy outlines our strict data minimization practices and confirms that PIPPI does not collect, store, transmit, or monetize your personal data.

1. Information Collection and Use

PIPPI operates entirely locally on your client device. Because the extension runs completely offline within your browser sandbox:
• No Personal Information: We do not collect or request names, email addresses, ages, identification numbers, or account details.
• No Browsing History Tracking: While the extension utilizes browser APIs to identify active website hostnames, it does not record, log, or store a history of the web pages you visit. Hostname evaluation happens strictly in temporary browser memory to determine if a visual shield should be applied.
• No Telemetry or Analytics: We do not use third-party tracking scripts, network monitoring, or analytics tools. We have zero visibility into how or when you use the extension.

2. Local Browser Storage

To deliver a seamless accessibility workflow across browser sessions, PIPPI saves your functional app preferences locally using the chrome.storage.local API. This data includes:
• Your active sensory profiles (e.g., Day Focus, Sensory Guard, Deep Calm).
• Granular slider values for your custom tint warmth and contrast suppression.
• Your 20-slot "Custom Sanctuary" personal website exception list.
This configuration data is restricted entirely to your local device. It is never uploaded to a cloud database, shared over a network, or made accessible to external entities. You can wipe this data at any time by clearing your extension cache or uninstalling the extension.

3. Third-Party Services and Payments

The initial release (v1) of PIPPI is 100% free and includes no payment processing mechanics. Future updates introducing premium tiers will process billing directly through secure, separate external platforms (such as Stripe or ExtensionPay) in strict compliance with the Chrome Web Store Developer Terms. PIPPI itself will never handle or see your credit card details or financial statements.

4. Permissions Disclosures

PIPPI requests specific technical permissions within the browser architecture solely to deliver accessibility functionality:
• activeTab & host_permissions: Used strictly to determine if the active webpage matches a safe configuration domain so the extension can automatically inject its visual shield.
• scripting: Used on demand to apply client-side ambient color matrices and disable rapid CSS transitions or smooth-scrolling behaviors to suppress vestibular nausea triggers.
• storage: Used purely to save your local UI preferences on your machine.

5. Changes to This Policy

We may update our Privacy Policy to reflect future changes to the extension's functional components. Any updates will be published openly on this page and will strictly uphold our foundational commitment to user data privacy and local storage security.

6. Contact Us

If you have any questions or feedback regarding our privacy architecture, please contact us directly through our official developer support portal on the Chrome Web Store.

"For a full list of all 55+ automatically supported websites, visit our [Supported Sites Page/GitHub/Help Center]."




📝 Privacy Policy for PIPPI

Last Updated: October 2026
Your privacy is paramount. PIPPI is built with absolute empathy and a strict commitment to user privacy. This Privacy Policy explains how PIPPI handles data.

1. Data Collection and Usage

PIPPI does not collect, track, store, or transmit any personal data, web content, user activity, or browsing history.
• No External Servers: PIPPI operates entirely within your local browser environment.
• No Analytics: There are no tracking scripts, telemetry, or analytics cookies embedded in the extension.

2. How Permissions Are Used

To provide sensory relief, PIPPI requires permission to interact with your browser tabs and web content.
• Predefined & Custom Sites: PIPPI injects local CSS and JavaScript styling into web pages strictly to alter visual layouts, apply color-filtering layers, override smooth scrolling, and freeze animations. This is done entirely on your machine.
• Storage Permission: Your preferred sensory profiles and your custom "My Custom Sanctuary" website lists are stored 100% locally on your own device using Chrome’s local storage API.

3. Third-Party Sharing

Because we collect zero data, we do not—and cannot—sell, trade, or share any of your information with third parties.

4. Contact

If you have any questions about this privacy policy, you can contact the developer via the support channel on our official [GitHub repository link].
