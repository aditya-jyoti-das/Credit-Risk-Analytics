
1. **id**: A unique identifier for each loan.
2. **member_id**: A unique identifier for each borrower.
3. **loan_amnt**: The total amount of the loan applied for by the borrower.
4. **funded_amnt**: The amount of the loan that was funded by investors.
5. **funded_amnt_inv**: The total amount funded by investors for the loan.
6. **term**: The length of the loan (e.g., 36 months or 60 months).
7. **int_rate**: The interest rate on the loan.
8. **installment**: The monthly payment amount for the loan.
9. **grade**: The loan grade assigned by the lending platform (e.g., A, B, C).
10. **sub_grade**: A more detailed grading of the loan (e.g., A1, A2, B1, etc.).
11. **emp_title**: The job title of the borrower.
12. **emp_length**: The length of time the borrower has been employed in years.
13. **home_ownership**: The home ownership status of the borrower (e.g., Rent, Own, Mortgage).
14. **annual_inc**: The annual income of the borrower.
15. **verification_status**: Indicates whether the borrower's income was verified (e.g., Verified, Source Verified, Not Verified).
16. **issue_d**: The month and year when the loan was issued.
17. **loan_status**: The current status of the loan (e.g., Fully Paid, Charged Off, Current).
18. **pymnt_plan**: Indicates if the borrower is on a payment plan.
19. **url**: A URL linking to additional data for the loan (usually for internal use).
20. **desc**: A description of the loan provided by the borrower.
21. **purpose**: The purpose of the loan (e.g., Debt consolidation, Home improvement).
22. **title**: The title/summary of the loan provided by the borrower.
23. **zip_code**: The first three digits of the borrower's zip code.
24. **addr_state**: The state of the borrower’s address.
25. **dti**: Debt-to-income ratio, calculated as monthly debt payments divided by monthly gross income.
26. **delinq_2yrs**: The number of times the borrower had been 30+ days past due on a payment in the past 2 years.
27. **earliest_cr_line**: The date when the borrower’s earliest reported credit line was opened.
28. **inq_last_6mths**: The number of inquiries in the borrower’s credit report in the past 6 months.
29. **mths_since_last_delinq**: Months since the borrower’s last delinquency.
30. **mths_since_last_record**: Months since the last derogatory public record.
31. **open_acc**: The number of open credit lines in the borrower's credit file.
32. **pub_rec**: The number of derogatory public records.
33. **revol_bal**: Total credit revolving balance (e.g., credit card balance).
34. **revol_util**: Revolving line utilization rate, or the amount of credit used relative to all available revolving credit.
35. **total_acc**: The total number of credit lines in the borrower’s credit file.
36. **initial_list_status**: The initial listing status of the loan (e.g., W for whole, F for fractional).
37. **out_prncp**: The remaining principal amount of the loan.
38. **out_prncp_inv**: The remaining principal amount funded by investors.
39. **total_pymnt**: Payments received to date for the loan.
40. **total_pymnt_inv**: Payments received to date for the loan funded by investors.
41. **total_rec_prncp**: Principal received to date.
42. **total_rec_int**: Interest received to date.
43. **total_rec_late_fee**: Late fees received to date.
44. **recoveries**: Post charge off gross recovery.
45. **collection_recovery_fee**: Fees paid for recovery efforts.
46. **last_pymnt_d**: The date of the borrower’s last payment.
47. **last_pymnt_amnt**: The amount of the last payment made by the borrower.
48. **next_pymnt_d**: The date of the next payment due.
49. **last_credit_pull_d**: The most recent date when the borrower’s credit was pulled.
50. **collections_12_mths_ex_med**: The number of collections in the past 12 months excluding medical collections.
51. **mths_since_last_major_derog**: Months since the most recent 90-day or worse rating.
52. **policy_code**: The publicly available policy code for the loan.
53. **application_type**: Indicates whether the loan is an individual application or a joint application with two co-borrowers.
54. **annual_inc_joint**: The combined annual income of co-borrowers.
55. **dti_joint**: The combined debt-to-income ratio of co-borrowers.
56. **verification_status_joint**: Indicates whether the co-borrowers' incomes were verified.
57. **acc_now_delinq**: The number of accounts on which the borrower is currently delinquent.
58. **tot_coll_amt**: Total collection amounts ever owed.
59. **tot_cur_bal**: Total current balance of all accounts.
60. **open_acc_6m**: Number of open credit lines in the last 6 months.
61. **open_il_6m**: Number of open installment accounts in the last 6 months.
62. **open_il_12m**: Number of open installment accounts in the last 12 months.
63. **open_il_24m**: Number of open installment accounts in the last 24 months.
64. **mths_since_rcnt_il**: Months since most recent installment account opened.
65. **total_bal_il**: Total current balance of all installment accounts.
66. **il_util**: Ratio of the total current balance to the original loan amount on installment loans.
67. **open_rv_12m**: Number of open revolving credit lines in the last 12 months.
68. **open_rv_24m**: Number of open revolving credit lines in the last 24 months.
69. **max_bal_bc**: Maximum current balance on a bank card.
70. **all_util**: Balance to credit limit on all trades.
71. **total_rev_hi_lim**: Total revolving high credit/credit limit.
72. **inq_fi**: Number of personal finance inquiries.
73. **total_cu_tl**: Number of finance trade lines.
74. **inq_last_12m**: Number of credit inquiries in the last 12 months.

These columns provide a comprehensive view of a borrower's credit profile, loan details, and repayment history, which are crucial for predicting credit defaults.