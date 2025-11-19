# MyBambu Cash-Flow Risk Assessment Model

An interactive web-based documentation for the MyBambu Credit Evaluation Framework.

## Features

- **Interactive Score Calculator** - Input values for all 6 criteria and see the composite risk score in real-time
- **Responsive Design** - Works on desktop, tablet, and mobile devices
- **Collapsible Sections** - Detailed formulas and calculations available on-demand
- **Easy Navigation** - Fixed sidebar with quick links to all sections
- **Visual Risk Indicators** - Color-coded risk levels and badges

## Quick Start

### Local Preview

Simply open `index.html` in your web browser:

```bash
open index.html
```

### Deploy to GitHub Pages

1. **Create a new GitHub repository:**
   - Go to https://github.com/new
   - Name it `mybambu-risk-assessment` (or any name you prefer)
   - Choose Public visibility
   - Do NOT initialize with README (we already have one)
   - Click "Create repository"

2. **Push this code to GitHub:**

   ```bash
   cd /Users/claudiamontengrogonzalez/mybambu-risk-assessment
   git init
   git add .
   git commit -m "Initial commit: MyBambu Risk Assessment interactive website"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/mybambu-risk-assessment.git
   git push -u origin main
   ```

3. **Enable GitHub Pages:**
   - Go to your repository on GitHub
   - Click **Settings** (gear icon)
   - Click **Pages** in the left sidebar
   - Under "Source", select **Deploy from a branch**
   - Select **main** branch and **/ (root)** folder
   - Click **Save**

4. **Access your site:**
   - Wait 1-2 minutes for deployment
   - Your site will be available at: `https://YOUR_USERNAME.github.io/mybambu-risk-assessment/`

## Contents

### 6 Key Criteria (with weights)

1. **Transaction History** (20%) - Banking relationship depth and stability
2. **Parcel Affordability** (25%) - Ability to afford loan payments
3. **Debt** (20%) - Existing obligations impact on cash flow
4. **Employment** (15%) - Income stability and consistency
5. **Behavior** (10%) - Financial conduct and red-flag behaviors
6. **Bank Account Stability** (10%) - Banking relationship health

### Decision Framework

- **70-100**: Low Risk → Auto-Approve
- **60-69.99**: Moderate Risk → Manual Review
- **50-59.99**: Elevated Risk → Enhanced Scrutiny
- **0-49.99**: High Risk → Auto-Deny

## Technical Details

- **Single-file application** - All HTML, CSS, and JavaScript in one file for easy deployment
- **No dependencies** - No build process or npm packages required
- **Print-ready** - Includes print styles for documentation export
- **Accessible** - Semantic HTML with proper headings and navigation

## License

Internal documentation for MyBambu credit evaluation.

---

**Model Version:** 1.0
**Date:** November 2025
