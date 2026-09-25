# Grand Crown Platform

Grand Crown member/rewards platform with customer dashboard and administrator controls.

## Reference flow
The customer experience follows the same general mobile-first flow as the supplied reference: registration/login, dashboard, plans, deposit, withdrawals, referral/team, account, and transaction status. Grand Crown branding and content are used instead of third-party Coca-Cola branding.

## Payment flow
- Customer selects a product and taps **Continue to Payment**.
- A payment modal opens; the full checkout URL is not shown as raw text.
- The customer can open the configured secure checkout button, then submit the payment/reference number.
- The purchase stays **Pending** until an administrator approves it.
- Current configured payment method: **PesaJet**.

## Admin controls
- Dashboard, analytics, users, deposits, withdrawals, products, transactions, referrals, settings, and activity log.
- User management popup: **Credit wallet, Debit wallet, Ban/Unban, Delete user**.
- Credit/debit actions create transaction records.
- Banned users cannot log in.
- Deposit approval creates the purchase and referral commission only after approval.

## Current Grand Crown defaults
- Welcome bonus: UGX 2,100
- Daily check-in: UGX 100
- Minimum top-up: UGX 22,000
- Minimum withdrawal: UGX 3,000
- Withdrawal fee: 12%
- Withdrawal hours: 10:00–17:00 EAT
- Referral: Level 1 = 10%; Level 2 = 0%; Level 3 = 0%
- Support: @Grandcrown01
- Telegram: https://t.me/+zNDnaz_xKfdiMTlk
- PesaJet checkout: https://pay.pesajet.com/pay/d9c18ef87c

## Render
Build command: `npm install`
Start command: `npm start`

For production, set `ADMIN_USER` and a strong `ADMIN_PASS` in Render Environment Variables.
