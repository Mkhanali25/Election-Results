# Election-Results
## Overview
In this challenge we helped Seth and Tom collect information on voters and voter counties. We collected information such as voter turnout, the percentage of votes from each county out of the total count, and the county with the highest turnout. I also created an output txt file from the information that was given.
## Election Audit Results
The amount of people that showed up for this election was a whopping 369,711. Each county had a significant amount of people show up, but the county with the highest turnout was Denver had 82.8% (306,055). The next two counties don't even come close to the amount of voter turnout Denver had. Jefferson was the second highest at 10.5% (38,855) and Arapahoe had 6.7% (24,801). The candidate results mirrored that of the counties, one candidate left the other two in the dust. Diana DeGette had the highest votes at 73.8% (272,892), next was Charles Casper Stockham: 23.0% (85,213), and last but not least was Raymon Anthony Doane: 3.1% (11,606). It was an easy conclusion to make that Diana DeGette was the winner of the election with 272,892 votes, out of the total amount of votes that were cast 73.8% were hers.
## Election Audit Summary
This script had given me a lot of trouble at first, but after much hard work I finally got the output I needed. This script is interchangeable with any election, you just have do tweak it a little to match your data. First and foremost you have to change the path to the file that you're pulling your data from. All you have to do is change "file_to_load = os.path.join("../Analysis/election_results.csv")" that line to the correct path. Also depending on how your data is set up you would have to match the rows with the variables. For example in our data set "candidate_name = row[2]" we had our candidate names in row 2, so you would have to match that with your data set.
