## Dec 11, 2024

### Direct selling API

#### Membership checkout as a guest

### Trade for Venues

#### Configure payment method

### Trade for Resellers

#### Change in the order flow if Direct payment method is configured

### Insight

#### Enhancement

The endpointCheckout basketnow supports membership checkout as a guest. For this purpose, at least the visitor's firstName, lastName, and email must be provided.

At the reseller-level, the venue can define the payment method as Invoice or Direct payment.

The main difference between the two payment methods is that with the Invoice payment method, the amount owed to the venue is paid monthly, whereas, with the direct payment method, the reseller pays the venue at the time of confirming a reserved order.

For a detailed description, refer to partnerconfigurations.

If a venue partner has configured Direct payment method for your reselling organisation, you can directly pay the payable amount to the venue on a per-order basis.

You can consult the configured payment method on the offer details page as Invoice or Direct payment.

If Direct payment method is configured, it will affect theorder flow.

When an order is reserved, you will have the payment link to pay the amount payable to the venue for that order. This amount is the venue's product price minus the commission.

The status of the amount paid to the venue is shown in the order details, tab Payment.

Important to know when the Direct payment method is configured:

At the time of checkout, you will only be able to reserve the order. The options to 'Buy now' and 'Confirm order' willnotbe available on the Checkout page.

If the payment to the venue is pending, you willnotbe able to Confirm or Update the reserved order. However, you can cancel the order.

Once the payment is made to the venue via the payment link, the order will automatically be confirmed. You can then cancel the order partially or completely as well as get the passes.

The payment configuration is applicable to Enviso Trade. This means the reseller can still confirm the order from the Reselling API.

Offers of the venues with different payment methods configured for your organisationcannotbe added to the cart at the same time. You will need to create separate orders in this case.

Added visitorData in vw_orders and vw_task_info. The views have been updated for individual form fields and visitor data.

[Prev](UUID-8137a4e0-1fca-0537-6f87-412f61307a16.html)

[Next](UUID-f183b3ae-22be-3dac-11d4-d44c5df78338.html)

[](#)

[](#)

[](#)

[Checkout basket](https://help.vintia.com/enviso/developers/direct-selling-api/en/index-en.html#UUID-36cc21a7-582d-d2d8-6e16-f6cb1e5bbb56)

[](#)

[](#)

[configurations](https://help.vintia.com/enviso/en/136639-1030408-configurations.html)

[](#)

[](#)

[](#)

[](#)

[Prev](UUID-8137a4e0-1fca-0537-6f87-412f61307a16.html)

[Up](UUID-8c91cf65-b493-dafc-6b18-13d422537b92.html)

[Next](UUID-f183b3ae-22be-3dac-11d4-d44c5df78338.html)

[Home](index-en.html)

![9.png](media/uuid-4c69f113-d5ca-abb9-4adb-2b818244c2f1.png)

![10.png](media/uuid-3e8d35a5-1033-85ba-7359-2c4bcc423ddd.png)

![11.png](media/uuid-69e7baa4-62e4-96c9-034d-eed93f6a28a5.png)

![12.png](media/uuid-8e3097ad-3f31-273b-4f9f-760c4d6effad.png)

![14.jpg](media/uuid-83ecb253-eef0-aca6-d77f-451d2502c103.png)

![16_.png](media/uuid-dc3886af-875c-409a-a7a8-a7a4bcf0708e.png)

![15_.png](media/uuid-7664f624-af39-1116-9aa2-803b1c86fefe.png)