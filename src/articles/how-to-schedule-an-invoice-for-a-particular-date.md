---
title: How to schedule an invoice for a particular date
description: Schedule invoices in advance and subside your overhead
layout: article
---
You can schedule an invoice for a particular date in advance and only one copy of that scheduled invoice will create on that particular date. 

1. Login into your Gaurilla account and set the workspace in which you wish to generate an invoice.

2. As you land on the dashboard with all sort of options around you, click on the **Slips** button which you will find just below the dashboard icon (the red G).

    ![slips-navigation]({{site.url}}/images/slip/slips-navigation.png)

3. At the top right corner the **New** button is what you are looking for in order to generate an invoice.

    ![slips-new]({{site.url}}/images/slip/slips-new.png)

4. The new invoice window will have all the options to enter all the details which you need to specify in order to generate your invoice.

    ![slip-create]({{site.url}}/images/slip/slip-create.png)

5. Now follow steps you usually do while creating normal invoice.

6. Now when you are done with filling all options in invoice, you will find a checkbox adjacent to the **Publish** button followed by a line **is recurring?** which is by default unchecked. When you check that checkbox, a recurrence form will be visible to you just below the **Publish** window. Invoice number and date will not be considered if the invoice is recurring, so they will be replaced by a text **Recurring Invoice**.

	![slip-recurrence-checkbox]()

7. Now fill in the recurrence form as follows:

	![slip-recurrence-form]()

	1. Fill the **Start** date as you want, which sets the first recurrence date of recurring invoice. If **Start** date is today's date then a copy of this invoice will be created spot on else it will create on the date you will enter.

		> **Pro Tip:** Start date is not editable so while creating recurring invoice fill it accordingly else you have to create a new one.

	2. Next you have to fill **Every**, which sets the interval after which the copy of recurring invoice to be created. In this you have to fill two fields, first is number field and second field is for selecting duration out of day, month and week.

	3. At last you have to fill **End**, which sets the last recurrence of the recurring invoice. 	

		1. If you select **On date** option in drop down menu then an input field will be visible to you just below it and in that simply fill the date same as **Start** date.			

		2. If you select **After count** option in the drop down menu then an input field will be visible to you just below it and in that fill **1**.

8. Once done, click on **Publish** button and the recurring invoice will be created.

	>**Note:** The recurring invoice you create will not affect the accounting and inventory at all, but copies of this invoice which will be created on specified intervals will affect both. 
