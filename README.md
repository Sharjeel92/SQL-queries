# SQL-queries

Query to take out most repeated Names corresponding to each ID


select FLName, MRN,MAX(Date), count(1) as CodeCount from MRNTest group by FLName, MRN order by count(FLName) desc

select MRN,Fname, Date, MAX(count) from MRNTestresult group by MRN
