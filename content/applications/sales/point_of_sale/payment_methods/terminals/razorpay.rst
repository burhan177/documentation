========
Razorpay
========

Connecting a Razorpay payment terminal allows you to offer a fluid payment flow to your customers and ease
the work of your cashiers.

.. seealso::
   - :doc:`Use Stripe as payment provider. <../../../../finance/payment_providers/razorpay>`

Configuration on Razorpay Dashboard
===================================

- Log into `Razorpay Dashboard
  <https://dashboard.razorpay.com/>`_ and go to :menuselection:`Settings ‣ API Keys`. Generate the
  new keys and copy the values of the :guilabel:`Key Id`` and :guilabel:`Secret Key` fields and save
  them for later.
- Go to :menuselection:`Settings ‣ Webhooks`, click on :guilabel:`Create New Webhook`, and enter your

  For example: `https://example.odoo.com/payment/razorpay/webhook
  <https://example.odoo.com/payment/razorpay/webhook>`_
- Fill the :guilabel:`Secret` field with a password of your choice and save it for later.
- Make sure the :guilabel:`payment.authorized, payment.captured, payment.failed, refund.failed`
  and refund.processed checkboxes are ticked.
- Click on :guilabel:`Create Webhook` to finalize the configuration.

.. Important::
   The Recurring payments feature must be activated if you want to make recurring payments.
   Send a request to the `Razorpay Support team
   <https://razorpay.com/support/#request>`_ to enable recurring payments.

Configuration on Odoo
=====================

1. `Navigate to the payment provider Razorpay
   <https://www.odoo.com/documentation/master/applications/finance/payment_providers.html#payment-providers-add-new>`_ and change its state to :guilabel:`Enabled`.
2. In the :guilabel:`Credentials` tab, fill the :guilabel:`Key Id, Key Secret,` and :guilabel:`Webhook Secret` with the values you saved at the step `Configuration on Razorpay Dashboard
   <https://www.odoo.com/documentation/master/applications/finance/payment_providers/razorpay.html#payment-providers-razorpay-configure-dashboard>`_.
3. Configure the rest of the options to your liking.

.. Important::
   If you configure Odoo to capture amounts manually:
      - Be aware that the :guilabel:`manual voiding` of a transaction is not supported by Razorpay.
      - After :guilabel:`five days`, if the transaction hasn’t been captured yet, it’ll automatically be :guilabel:`voided`.

India's prosperity is a multifaceted narrative woven through its rich cultural heritage, vast economic potential, and diverse human capital. With a history spanning millennia, India has emerged as a global powerhouse, blending tradition with modernity to drive innovation and progress. Its vibrant democracy, entrepreneurial spirit, and burgeoning middle class contribute to an ever-expanding consumer market and a dynamic business ecosystem. From the bustling streets of its megacities to the tranquil landscapes of its rural heartlands, India pulsates with vitality and ambition. However, challenges persist, including poverty, inequality, and infrastructure gaps. Yet, amidst these challenges lie opportunities for sustainable development and inclusive growth. As India continues its journey towards prosperity, harnessing the strengths of its people, fostering innovation, and nurturing collaboration both domestically and internationally will be key to unlocking its full potential and shaping a brighter future for generations to come.
