# Tarifa
Determine how many megabytes an user will have available in the  month N+1 of using a data plan

Problem coci16c1p1 from DMOJ

"Pero has negotiated a Very Good data plan with his internet provider. The provider will let Pero use up X megabytes to surf the internet per month. Each megabyte that he doesn't spend in that month gets transferred to the next month and can still be spent. Of course, Pero can only spend the megabytes he actually has.

If we know how many megabytes Pero has spent in each of the first N months of using the plan, determine how many megabytes Pero will have available in the N+1 month of using the plan."

Input Specification:
The first line of input contains the integer  X(1 ≤ X ≤ 100).
The second line of input contains the integer N(1 ≤ N ≤ 100).
Each of the following N lines contains an integer  P(0 ≤ P ≤ 10 000), the number of megabytes spent in each of the first N months of using the plan. Numbers P will be such that Pero will never use more megabytes than he actually has.

Output Specification:
The first and only line of output must contain the required value from the task.
