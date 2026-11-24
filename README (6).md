# Telecom Order-to-Cash Walkthrough

I made this project to understand how a telecom company goes from "a customer picks a plan" to "the customer pays a bill". These are the systems a presales or solution consulting team talks about every day: product catalog, CRM, order management, charging and billing.

This is a learning exercise. The plans, prices and customers are made up, and I built it from public reading. It does not describe any real company's systems. I used generative AI tools to help me research and draft, and I checked and edited the work myself.

## Files
- `01_Order_to_Cash_Explainer.md`: the customer journey as a flow chart, and what each system does
- `02_Bill_Calculator.xlsx`: a small Excel model that works out a monthly bill from plan, usage and tax
- `03_Customer_Need_to_Requirements.md`: three examples of turning what a customer says into solution requirements

## What I learned
- Each system does one job, and a mistake in one (for example the catalog) shows up later in another (the bill)
- Prepaid and postpaid customers are charged differently, and a convergent system handles both
- Good requirements start from a customer's words and a clear question, not from features
