# Overview
This project asks how, when faced with uncertain enrollment trends and a need to maintain a proper assignment of resources to students, a school district might set a fair resource policy by maintaining a tolerable student-to-resource ratio, for example, maintaining a certain student-to-school ratio $R$, for example 200 students in each school.

I will address this question by using a two-agent simulation of school openings and closings in a single school district, played out over 50 to 100 time steps ("school years"). One agent represents the population of public school students, which undergoes random demographic variation across years. The other agent represents the policy-making body of the district, which attempts to maintain a tolerable student-to-school ratio in the face of these demographic changes by using historical data to predict the change in enrollment at the end of each school year and opening or closing schools in response. The district administration agent will update its prediction-making method based on whether its predictions have led to good decisions (maintaining a tolerable student-to-school ratio) or poor ones (failure to maintain the ratio).