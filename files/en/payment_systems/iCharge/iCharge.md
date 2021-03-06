iCharge
==================

**iCharge** is a Splynx add-on. It allows to refill balance and pay invoices via Xilo payment gateway - https://xilo.com.**

Add-on can work with different credit cards, if cards are saved, then addon allows to charge all customers using *Direct debit order*.


To install *splynx-icharge* add-on, use following commands:


```bash
apt-get update
apt-get install splynx-icharge
```
or you can install it from Web UI:

*Config → Integrations → Add-ons:*

![1.png](1.png)

![2.png](2.png)

![3.png](3.png)

After installation you have to configure addon:

*Config → Integrations → Modules list:*

![4.png](4.png)

Set those parameters from your https://xilo.com account and set here your server IP address (IP address from where Xilo will take requests):

![6.png](6.png)

![5.1.png](5.1.png)

After that, customers can pay their invoices by using iCharge system. They will see a new button *"Pay by iCharge"* as on the screenshot:

![7.png](7.png)

also you can turn on entry point in *config -> integrations -> modules list -> Splynx iCharge Add-on* as on the screenshot:

![18.png](18.png)

![15.png](15.png)

after that customer will be able to pay his invoice from dashboard:

![16.png](16.png)

To refill balance customers can use the link - *“http://yoursplynxurl/icharge/”*:

![10.png](10.png)

or you can turn on entry point in *config -> integrations -> modules list -> Splynx iCharge Add-on* as on the screenshot:

![18.png](18.png)

![17.png](17.png)

after that customer will be able to refill his balance from dashboard:

![19.png](19.png)

Customers can save pay-card details for the next payments in "Financ" menu:

![12.png](12.png)

or he can add it, from payment window as on the screenshot:
![8.png](8.png)

![9.png](9.png)

When customers saved their credit cards, you can charge all customers, using one button! Go to *Finance → Invoices*, set the period and click "Charge" as at the screenshot:

![13.png](13.png)

![14.png](14.png)
