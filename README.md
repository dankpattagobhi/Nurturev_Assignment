# Nurturev_Assignment

Data Given was very comprehensive and was covering following details:
['id',
 'domain_name',
 'ticker',
 'mic_exchange',
 'summary',
 'name',
 'linkedin_url',
 'profiles',
 'tags',
 'employee_count',
 'website',
 'funding_stages',
 'funding_details',
 'employee_growth_rate',
 'employee_count_by_month',
 'employee_count_by_month_by_role',
 'employee_count_by_country',
 'top_previous_employers_by_role',
 'top_next_employers_by_role',
 'employee_count_by_month_by_level',
 'recent_exec_hires',
 'recent_exec_departures',
 'created_at']

 To find the decline in the sales team in past 6 months we first have to extract the data from  'employee_count_by_month_by_role' column and from this table we have to get data only for sales department

 Then we have to take tail of this dataframe to get past 6 months data

 Since the variation in the No. of mployees in sales departmrnt in large across various companies it would be great to calculate relative decline rather than absolute decline

After the analysis it was found that GROM has the largest decline in the sales team in past 6 months




 
