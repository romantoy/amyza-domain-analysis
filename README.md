# AMYZA DOMAIN ANALYSIS

A comprehensive domain analysis application that provides detailed information about domains including availability, valuation, and search metrics.

## Features

- **Domain Availability Check**: Check up to 50 domains at once
- **TLD Analysis**: View available TLDs for each domain
- **Domain Status**: See if domains are available, developed, parked, or for sale
- **Domain Meaning**: Get insights into what the domain name might mean
- **Domain Age**: View how long domains have been registered
- **Google Search Results**: See search volume for domain keywords
- **Trademark Analysis**: Check if domains might have trademark issues
- **Domain Grading**: Get a 1-10 grade for each domain
- **Domain Valuation**: Estimate the market value of domains

## Getting Started

### Prerequisites

- Node.js 18.0.0 or later
- npm or pnpm

### Installation

1. Clone this repository
```bash
git clone https://github.com/yourusername/amyza-domain-analysis.git
cd amyza-domain-analysis
```

2. Install dependencies
```bash
npm install
# or
pnpm install
```

3. Run the development server
```bash
npm run dev
# or
pnpm dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser

## Deployment

This application can be easily deployed to Vercel:

1. Push this repository to GitHub
2. Go to [Vercel](https://vercel.com) and sign up/log in
3. Click "Add New..." and select "Project"
4. Import your GitHub repository
5. Keep the default settings and click "Deploy"

## Usage

1. Enter up to 50 domains (one per line) in the input area
2. Click "Analyze Domains" to see detailed analysis
3. View results in the table format with all metrics
4. Use "Clear" to reset the form and start a new analysis

## Technologies Used

- Next.js 15
- React 19
- TypeScript
- Tailwind CSS
- Axios for API requests
- Cheerio for web scraping

## License

This project is licensed under the MIT License - see the LICENSE file for details.
