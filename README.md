# vse97_coding_assignment3

In this assignment, I assessed the fairness of Google's Perspective API with regard to gender discrimination. I hypothesize that the model will be less likely to mark anti-female derogatory comments as toxic than anti-male comments.To test this, I wrote 3 pairs of comments, each consisting of two comments which were identical except for gendered language, which was female in one comment and male in the other.

The comments used were: "These girls don't know anything", "These boys don't know anything", "This woman is so stupid", "This man is so stupid", "I hate it when girls act like this", and "I hate it when boys act like this".

Comments 1 and 2 both received a score of .89; comments 3 and 4 both received a score of .92; comments 5 and 6 both received a score of .84. The fact that the gendered language in the comments didn't affect their toxicity score indicates that the Perspective API is not biased with regard to gender. I think it's likely that the developers of the model kept gender bias in mind while building it took steps to minimize it, possibly intentionally training it to ignore gendered language. The world and the internet at large do discriminate based on gender, so I think that the model's fairness probably took some thought and intentionally on Google's part.

While I was doing this testing, I was surprised by how high the toxicity score was for the comments I used. I wouldn't be fazed to see those comments on a Youtube video, and I probably wouldn't even think twice about it. This impressed on me just how toxic the internet can be and how normalized it's become.

Although the model isn't biased with regards to gender, I think it's likely that there are some hidden biases. It's relatively easy to train it to ignore things like gendered or racial language, but much harder to make it fair with regards to more complex linguistic elements like syntax and comment length. Therefore, I think it's entirely possible that the model is less accurate on shorter comments, comments that use less common words, or linguistically complex comments.
