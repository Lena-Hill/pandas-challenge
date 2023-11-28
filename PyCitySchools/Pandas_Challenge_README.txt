Pandas Challenge 
PyCity School Analysis

In this exercise we are asked to analyze data for the local school district. The objective is to explain to the school board and mayor how education outcomes and budgets are related. We need to combine student and school data using pd.merge after loading and reading our files.  

We start by looking at key metrics such like student performance in math and reading, school size, total students, and budget. Next we used the .groupby function to group data by school name. For each school we calculated: 
	school type
	total students
	per student budget
	average math score
	average reading score
	% passing math
	% passing reading
	% passing both math and reading

Next we sorted schools by overall passing percentage in descending order. Using .sort_values. We used the same technique for the lowest-performing schools. We then looked at math and reading scores by grade. 

We then established bins and labels to analyze academic scores by school spending using pd.cut to see average scores by spending range. Interesting to see an inverse relationship between per student spending and average test scores. In schools spending $645-680 per student had lower academic scores. We also looked at: score by school size and scores by school type. 

Many thanks to all the course materials and classmates.  

