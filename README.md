Scheme Engine

The rules folder consists of three Schemes and the description of the schemes are listed below:
- BUY 3 GET 1:Distributors located in the North region who are classified as "green" customers and purchase at least 3 units of BINGO products are eligible to receive 1 unit of "Lays Chips 50g" (PRD-LAYS50) free.
- Slab based: Distributors in the South region who are classified as "green" customers and purchase MAGGI products are eligible for a flat discount based on their total billing amount. The discount slabs are as follows    ₹100 off for billing between ₹5,000 and ₹9,999,₹300 off for billing between ₹10,000 and ₹19,999 ,₹800 off for billing of ₹20,000 or more
- FLAT DISCOUNT: Retailers located in the East region, who are classified as "amber" customers and purchase BINGO products with a total value of ₹1,000 or more, are eligible to receive a flat 10% discount on their purchase amount.

Only for the above schemes ,rules are applied.If no rules matched ,no discounts are applied.


About Business Rules:
- Business rules are designes for evaluating rules.

In the Code:
   - The CustomerVariables class defines all the fields (variables) that are referenced in the rules (i.e., the JSON files).
   - The CustomerActions class defines the actions that should be executed when a rule condition is met.
   - The run_all function evaluates all the loaded rules, and if any rule conditions are satisfied, it applies the corresponding actions.

Note:

The run_all function from the business-rules Python package is synchronous.
This means:
- It processes the rules one after another, in the order they appear in the list.
- Each rule is evaluated, and if the conditions are met, the corresponding actions are executed immediately and in sequence.
- The program waits for run_all to finish before moving on to the next step.

