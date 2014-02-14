---
title: How to create recurring invoice
description: Make an invoice create automatically till you want without any extra efforts
layout: article
---
You can make an invoice recurs for a particular number of times and duration by simply specifying values in recurrence form while creating that particular inovice.


1. Login into your Gaurilla account and set the workspace in which you wish to generate an invoice.

2. As you land on the dashboard with all sort of options around you, click on the **Slips** button which you will find just below the dashboard icon (the red G).

    ![slips-navigation]({{site.url}}/images/slip/slips-navigation.png)

3. At the top right corner the **New** button is what you are looking for in order to generate an invoice.

    ![slips-new]({{site.url}}/images/slip/slips-new.png)

4. The new invoice window will have all the options to enter all the details which you need to specify in order to generate your invoice.

    ![slip-create]({{site.url}}/images/slip/slip-create.png)

5. Now follow steps you usually do while creating normal invoice.

6. Now when you are done with filling all options in invoice, you will find a checkbox adjacent to **Publish** button followed by a line **is recurring?** which is by default unchecked. When you check that checkbox, a recurrence form will be visible to you just below the **Publish** window. Invoice number and date will not be considered if the invoice is recurring, so they will be replaced by a text **Recurring Invoice**.

	![slip-recurrence-checkbox]()

7. Now fill in the recurrence form as follows:

	![slip-recurrence-form]()

	1. Fill the **Start** date as you want, which sets the first recurrence date of recurring invoice. If **Start** date is today's date then a copy of this invoice will be created spot on else it will create on the date you will enter.

		> **Pro Tip:** Start date is not editable so while creating recurring invoice fill it accordingly else you have to create a new one.

	2. Next you have to fill **Every**, which sets the interval after which the copy of recurring invoice to be created. In this you have to fill two fields, first is number field and second field is for selecting duration out of day, month and week.

	3. At last you have to fill **End**, which sets the last recurrence of the recurring invoice. 	

		1. If you select **On date** option in drop down menu then an input field will be visible to you just below it in which you have to mention the end date.

			> **Pro Tip:** End date should be later than the date which is calculated as sum of start and every.

			> **Note:** 1. End date should be later than start date.

						2. If end date is before the next recurrence date then next recurrence will happen on that end date instead of next recurrence date and will not consider any further dates.

		2. If you select **After count** option in the drop down menu then an input field will be visible to you just below it in which you have to enter the number of times invoice should recur.

			>**Pro Tip:** Select this option only when you know the exact number of times you want the invoice to get recurred.

8. Once done, click on **Publish** button and the recurring invoice will be created.

	>**Note:** The recurring invoice you create will not affect the accounting and inventory at all, but copies of this invoice which will be created on specified intervals will affect both. 
