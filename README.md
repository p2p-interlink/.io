
# Smooth InterLink (BEP20 Ecosystem)

Smooth InterLink is a web-based decentralized application (dApp) interface built on the **Binance Smart Chain (BEP20)** network. The platform features a dark-themed user interface designed for token mining ($ITLG), interactive dashboard tracking, and BEP20 wallet validation.

---

## 🚀 Features

* **$ITLG Token Mining Dashboard:** Real-time simulated mining counters and live action controls (`mine.html`).
* **BEP20 Wallet Validation:** Interactive form for connecting and synchronizing Web3 wallets including MetaMask, Trust Wallet, and Binance Web3 Wallet (`validate.html`).
* **Responsive Dark UI:** Mobile-first layout styled using Tailwind CSS with persistent bottom navigation.
* **Zero 404 Routing:** Standardized internal relative links across all core navigation routes.

---

## 📁 Repository Structure

```text
├── index.html       # Primary landing page and ecosystem overview
├── mine.html        # App dashboard for $ITLG mining and interactive tools
├── validate.html    # Wallet verification and BSC node connection page
└── index.html.bak   # Legacy backup snapshot of the original index file

🛠️ Tech Stack
 * Frontend: HTML5, Modern JavaScript (ES6+)
 * Styling: Tailwind CSS (via CDN)
 * Blockchain Network: Binance Smart Chain (BEP20)
 * Token Standard: BEP20 ($ITLG)
⚡ Getting Started Locally
 * Clone the Repository:
   git clone [https://github.com/your-username/smooth-interlink.git](https://github.com/your-username/smooth-interlink.git)
cd smooth-interlink

 * Run the Project:
   No build step or local server configuration is strictly required. Simply open index.html in any modern web browser, or launch it with a local development server like Live Server in VS Code.
 * Deploying to GitHub Pages:
   * Go to Settings > Pages in your GitHub repository.
   * Select main (or master) branch as the source and click Save.
   * Your site will be published at https://<your-username>.github.io/<repo-name>/.
🔗 Key Routes & Navigation
| File Name | Purpose | Key Actions |
|---|---|---|
| index.html | Landing Page | Ecosystem intro, CTA buttons to mine/validate |
| mine.html | Mining Dashboard | Live $ITLG counter, BSC network indicators |
| validate.html | Wallet Validation | Address/passphrase entry, network verification |
| index.html.bak | Backup File | Rollback reference for original baseline code |
📜 License
This project is open-source and available under the MIT License.


