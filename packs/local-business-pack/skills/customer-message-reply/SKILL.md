---
name: customer-message-reply
description: Draft privacy-safe customer message replies for inquiries, bookings, service questions, complaints, and after-sales issues using only known business facts.
---

# Skill: customer-message-reply

## 中文注释

这个 skill 用于客户私信回复，适合咨询、预约、售后、投诉和服务问题。回复必须基于已知商家信息，不能暴露私人客户数据，不能承诺未确认的价格、档期、补偿或结果。

## Purpose

Draft clear, polite, and privacy-safe replies to customer messages.

## Best for

Booking inquiries, service questions, pricing questions, complaints, after-sales issues, and follow-up messages.

## Not for

Private data disclosure, legal advice, medical advice, fake promises, or unconfirmed compensation.

## Input

- Business type
- Customer message
- Customer intent
- Known facts
- Service details
- Booking policy
- Tone
- Escalation rules
- Things to avoid
- Language

## Output

1. Customer intent summary
2. Suggested reply
3. Follow-up questions
4. Booking or service details
5. Escalation notes
6. Tone notes
7. Private data warnings
8. Risky wording to avoid
9. Final checklist

## Process

1. Identify the customer intent.
2. Use only known facts and policies.
3. Draft a concise reply.
4. Add follow-up questions when details are missing.
5. Flag privacy and escalation risks.

## Quality Bar

- Reply is clear and polite.
- Uses known business facts only.
- Does not expose private data.
- Does not promise unconfirmed outcomes.
- Includes follow-up questions when needed.

## Example Input

Business type: nail salon
Customer message: Do you have availability this Saturday for gel manicure?
Known facts: customer should contact booking channel for final availability
Tone: friendly

## Example Output

Suggested reply: Thanks for reaching out! We may have gel manicure slots this Saturday, but availability changes quickly. Could you share your preferred time window? We can then confirm the closest available appointment.

## Safety / Compliance Notes

Do not reveal private customer data, fabricate availability, promise compensation, provide legal/medical advice, invent business policies, or create unsupported claims, credentials, metrics, reviews, ratings, or awards.
