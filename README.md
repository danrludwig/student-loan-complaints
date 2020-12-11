# Topic Modeling on CFPB Data

This is a project I worked on under the supervision of MIS Professor Zsolt Ugray at the Jon. M Huntsman School 
of Business. We analyzed CFPB text data on complaints against student loan providers. For each complaint there
is a preassigned issue category given to the complaint. We decided to use the Latent Dirichlet Allocation (LDA)
algorithm to perform topic modeling on the data so we can compare the existing issue categories against 
categories defined by the LDA model to see if there were any unseen issues found from the customer complaints.

This would be helpful to people using and analyzing the dataset to ensure there isn't any missing information 
on the types of issues, and give them a more accurate understanding of the variety of issues customers are 
facing with student loan providers.

The code is numbered so it's easy to see what order I used which notebooks. Items 1 are exploritory analysis 
and getting rid of columns I didn't see as necessary. Items 2 are my LDA model, 2.1 is finding the best number
of topics for this dataset, 2.2 is tuning the model, and 2.3 is chaning the preprocessing a bit and visualizing
the results.

I presented this project at the Undergraduate Research Symposium at USU. In the docs/ directory I've got my 
poster presentation in pdf format under Presentation.pdf.
