# Fetchly Shopify Theme

Development repository for a Shopify storefront using the Horizon theme, customized to replicate the provided Figma design for the Fetchly test.

## 🚀 Setup

1. Install [Node.js](https://nodejs.org) (v18+ recommended).
2. Install Shopify CLI globally:
   ```bash
   npm install -g @shopify/cli

- Authenticate with your development store:
shopify auth login --store=lucasalvespereira.myshopify.com

- Pull the Horizon theme:
shopify theme pull --store=lucasalvespereira.myshopify.com

🛠 Development Workflow- Start local development server:
shopify theme dev --store=lucasalvespereira.myshopify.com

- Push changes to the store:
shopify theme push --store=lucasalvespereira.myshopify.com

- Commit changes to GitHub:
git add .
git commit -m "feat: add hero section"
git push

📌 Commit Guidelines- feat: for new sections or features (e.g., hero, products, testimonials, footer).
- fix: for bug fixes or responsive adjustments.
- style: for design tweaks or CSS changes.
- refactor: for code restructuring without changing functionality.