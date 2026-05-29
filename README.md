# Banking-intent-from-customers
## What is this project?
 This is an end-to-end AI engineering project for NLP text classification task by finetuning a modern transformer-based model with LoRA. It also has a comprehensive PII protection strategy to handle sensitive customer financial data needed to build production ready AI systems in highly regulated industries.

## Business Understanding
Understanding customer queries in banking is about determining the exact intent (the underlying goal of customer) behind what they type or say. Resolving this is so critical, as data shows that about 70-73% of financial service consumers will switch to a competitor after multiple bad experiences.

The problem boils down to bridge the gap between raw data which includes what custoer says and the resolutions is what bank needs to do. Addressing this would not debounce their customers to their competitors but enhances the existing relationship and customer might even stay with the bank for a long time as long as there is understanding! (a good experience)

Banks receive massive volumes of unstructured customer data daily through chat, email, and voice logs. Without automated intent recognition, banks face severe operational inefficiencies

## Objectives
The primary goal of this project is to automate the identification and routing of transaction disputes, billing inquiries, and transfer anomalies.
- Reduce Operational Costs: Deflect high-volume, repetitive inquiries (e.g., fee explanations) via automated self-service.- Accelerate Resolution Times (SLA): Instantly route high-risk transaction anomalies (e.g., unrecognized charges) to specialized risk teams.
- Enhance Retention: Minimize customer churn caused by frustrating delays during "missing money" kind of situations.

## Business Value & ROI
Implementing an effective intent recognition system yields measurable financial benefits:
- 70%+ Deflection Rate: AI chatbots instantly resolve routine intents without human intervention. Reduce the Average Handling Time (AHT) for transaction disputes by 30%.
- Smart Routing: High-value or complex intents route instantly to specialized human agents, boosting conversion. Achieve an automated query routing accuracy of >85% across the top categories.
- Decrease manual ticket triage volume by 50% through automated categorization.
- Proactive Analytics: Banks can track sudden spikes in specific intents 

Few of the top intents in the data:
``Index(['card_payment_fee_charged', 'direct_debit_payment_not_recognised',
       'balance_not_updated_after_cheque_or_cash_deposit',
       'wrong_amount_of_cash_received', 'cash_withdrawal_charge',
       'transaction_charged_twice', 'declined_cash_withdrawal',
       'transfer_fee_charged', 'balance_not_updated_after_bank_transfer',
       'transfer_not_received_by_recipient', 'request_refund',
       'card_payment_not_recognised', 'card_payment_wrong_exchange_rate',
       'extra_charge_on_statement', 'wrong_exchange_rate_for_cash_withdrawal'],
      dtype='object', name='category')``

![alt text](image.png)