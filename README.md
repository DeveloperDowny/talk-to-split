# Talk-to-Split

TLDR: 
This project helps you in calculating accurate food bill split according to who ate what.
While apps like SplitWise exist, this project focuses on taking the information about who ate what in the most natural form - speech - saving the hassle of typing the bill amount, person name, etc.

## About this project

This project was born by my lethargy in doing the food split calculations by myself.
Food splits are pretty easy when there are around 3 people involved and everyone shared all the items.
It's simple math then 1 pizza costing 300. 3 people ate. Split for all people is 100

But when there are more than 3 (let's say 8) and everyone didn't eat the same thing, calculations become a problem.

3 person shared pizza
2 shared biryani
3 people ate paneer lababdar
out of the 3, 2 ate 3 plain roti each; one butter garlic roti

You'll be having another dinner party until you procrastinate calculating the splits for the previous meal! Phew phew

Add this to multiple encounters where the food bills were not paid by the same person. Then tracking who owes how much to whom is a herculean effort.

So, to solve this problem. I thought of building convo-split. Converse with the AI Agent to get accurate food bill splits.

This will start as food bill splits but will be extrapolated to any kind of splits.

And to start with the actual project, I'll be breaking this project to simplest version possible and will increase the complexity gradually.

1. 1st version
- Food bills entered via any modality (speech, text, image)
- Information to calculate split via any modality (speech, text, image)
- Split given in any modality (speech, text, image)

Though I'll plan the code such that any modality will be accepted, I'll only implement the code for one.

2. 2nd version
- Food bill information
    - entered via any modality (speech, text, image)
    - but it is not required that the food bill be known at the start
- Information to calculate split
    - entered via any modality (speech, text, image)
    - the agent would ask for confirmation if it has correctly captured the information and ask follow-up questions if it has not or if it has found any inconsitent input
    - 


- Split given in any modality (speech, text, image)



