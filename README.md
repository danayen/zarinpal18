برای استفاده به صورت ارز تومان، ماژول تومان را قرار دهید. سپس نماد ارز ريال را به تومان تغییر دهید (فقط نماد را). چون مقدار تومان در 10 ضرب میشود و به درگاه ارسال می شود.
( خودم تست نکردم هنوز)
# Zarinpal

## Technical details

Documentation: [Payments API](https://www.zarinpal.com/docs/paymentGateway/)

This module integrates Zarinpal using tokenization and form
submission provided by the `payment` module.

## Supported features
- Tokenization with payment
- Payment with redirection flow

## Not implemented features
- Webhook notifications

## Configuration
1. First, go to the **Apps menu** and install the **Payment Provider: Zarinpal** module with the technical name **ho_payment_zarinpal**.
2. Next, go to the **Website menu** in the site management section.
3. Then, select the **Payment Providers** option from the **Configuration menu** and **eCommerce section**.
4. Open **Zarinpal** provider.
5. Change the **state** of the payment provider to **Enabled**.
6. In the **Credentials tab**, set the following fields based on the information provided by Zarinpal.
    - zarinpal_merchant_id: Zarinpan Merchant ID
7. Save payment providers configuration.
