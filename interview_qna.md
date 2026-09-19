# Interview Questions & Answers

**1. How do you calculate the average salary?**[span_10](start_span)[span_10](end_span)
**Answer:** Average salary nikalne ke liye, sabse pehle hum built-in `sum()` function ka use karke list ki sabhi salaries ka total karte hain. Phir us total ko `len()` function dwara nikale gaye kul employees ke count se divide kar dete hain (Total Salary / Number of Employees).

**2. What is the difference between total salary and average salary?**[span_11](start_span)[span_11](end_span)
**Answer:** Total salary sabhi employees ki salaries ka addition hoti hai, jo batati hai ki pura salary payout kitna hai. Dusri taraf, average salary ek mean value hoti hai jo yeh darshati hai ki on-average har employee ko kitni amount mil rahi hai.

**3. How would you analyze salary data using Pandas?**[span_12](start_span)[span_12](end_span)
**Answer:** Pandas library ka use karke hum list ko ek Series ya DataFrame mein convert kar sakte hain. Uske baad statistical analysis ke liye seedhe Pandas ke built-in methods jaise `.sum()`, `.mean()`, `.max()`, aur `.min()` apply kiye ja sakte hain. Ek line mein poori summary dekhne ke liye `.describe()` function ka use kiya ja sakta hai.
