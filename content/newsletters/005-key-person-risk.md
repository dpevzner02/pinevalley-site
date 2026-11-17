TITLE: When one person is the moat
SUBTITLE: Nvidia's CEO exit is a live lesson in key-person risk. Plus a simple way to read Anthropic's IPO filing yourself.

Hi friends,

This week the most important company in AI lost its founder-CEO in a matter of days, and the shock rippled out to its customers and partners. It's a good moment to ask a quiet question about everything we own, and even about our own work: what happens if one person is suddenly gone?

## 3 ideas

1. **Key-person risk was hiding in plain sight.** Jensen Huang resigned as Nvidia's CEO on Thursday after a week of reports about his personal relationships, and CFO Colette Kress was named interim CEO. Nvidia had not publicly disclosed a succession plan. Its filings never named Huang as a key person, saying instead that it is "highly dependent on the services of our longstanding executive team." The stock fell about 11% in the week through Thursday. [CNBC](https://www.cnbc.com/2026/11/09/jensen-huang-affair-nvidia-succession.html) · [Business Insider](https://www.businessinsider.com/jensen-huang-nvidia-flat-structure-leadership-succession-risk-2026-11) · [Yahoo Finance](https://finance.yahoo.com/technology/ai/articles/ai-roundup-nvidia-ceo-exit-091457648.html)

2. **Risk travels through relationships.** On Friday, Nvidia-backed neoclouds CoreWeave and Nebius fell 8.8% and 9% as investors worried about AI financing that Nvidia had helped provide under Huang. Yet earlier in the week CoreWeave beat forecasts and said cash flow from existing contracts would cover its debt repayments, and the S&P 500 still gained 2.5% for the week. Second-order exposure is real, and so is overreaction. [Reuters via Investing.com](https://www.investing.com/news/stock-market-news/neoclouds-ai-stocks-slide-again-as-nvidia-turmoil-rattles-sector-5026205) · [AP](https://apnews.com/article/stocks-markets-ai-us-oil-f8edd0eeb1494d4d2584715686c5e619)

3. **Read the commitments, not just the growth.** Anthropic plans to price its IPO on Nov 18 and start trading on Nasdaq on Nov 19, at $70 to $78 a share, a valuation of about $1.3 to $1.45 trillion. Revenue for the first nine months of the year was $33.2 billion. The filing also shows $895.4 billion of committed spending, mostly compute, with $69.8 billion due in the next 12 months. CNBC's sources say it is targeting about 20% retail allocation, far above the usual. [Yahoo Finance](https://finance.yahoo.com/technology/article/anthropic-sets-ipo-date-for-thursday-nov-19-173011206.html) · [CNBC](https://www.cnbc.com/2026/11/10/anthropic-sets-price-range-of-70-to-78-in-upcoming-ipo.html)

## 1 tool: AskS1

A small, independent site that lets you ask questions about Anthropic's S-1 (and SpaceX's) and get answers with the printed page numbers, so you can check every claim in the filing. It runs on Claude, a conflict its builder discloses up front. No price is listed, and each browser session is capped at 8 questions. An investor might use it to find governance details, risk factors or commitments before reading what others say about the IPO. It indexes the original Oct 26 filing, so confirm the latest numbers against the amended S-1 on EDGAR. [AskS1](https://asks1.com) · [How it was built](https://www.sparsevector.ai/p/adding-anthropic-to-asks1-rag)

## 1 prompt to try

> Act as a careful governance analyst. I'll paste the risk factors and management sections from a company's latest annual report or prospectus: [paste]. 1) Which named people does the business seem to depend on most, and for what (strategy, customers, suppliers, regulators, capital)? 2) Is there a disclosed succession plan or a deep bench? 3) Who controls the votes, and can outside shareholders change the board? 4) What would likely break first if a key leader left tomorrow? Quote the filing for each point, say when something isn't disclosed, and don't recommend buying or selling any security.

## 1 experiment: the bus-factor audit

Pick your three largest holdings, or the top holdings of your largest fund. Run the prompt on each one's latest filing and give each a key-person score from 1 to 5. Then turn it around: write a one-page "if I'm unavailable" note for your own household finances or your job, listing what only you know. Share your scores and what surprised you in #weekly-experiment on our Discord.

## 1 discussion question

Is a visionary leader an asset worth paying up for, or a risk worth discounting? What would you look for from the outside to tell the difference?

*For education only, not investment advice.*
