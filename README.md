# Coding-Assignment-3

While creating the model, I hypothesized that it would have some biases, as the model cannot understand tone. In intended on picking a few clear positive comments, a few clear negatives, but a few comments that can be taken either way, in order to see what the model would do, and whether or not one or two key words has an effect on the model, or if some comments just stood out. That was certainly the case. After looking at some data analysis from the persepective model I confirmed my hypothesis, that the model was very inconsisteny and would occasionally misclassify comments as toxic or untoxic based on certain tones(the main issue was opinions or personal preferences. One potential source that could've caused this bias is the training data that was used to create the model. If that training data was mainly consisted of negative or aggressive comments, the model might be significantly leaning more towards toxic for most comments. This model also could not have picked up on certain aspects of the comments, like mild sarcasm, friendly teasing, so it is super difficult for it do differentiate. As a result of completing this assignment, some takeaways I had are that sometimes machine learning models can be very unreliable, and it raises a lot of questions as we move towards such reliance on them, is it trustworthy? How can we ensure that we have fair and unbiased models? And more specifically relatable to this assignment, can we assure that this model can accurately classify content in a way that respects the principles of free speech and respects peoples right to having an opinion? 
Overall, this went as expected. The model was very accurate in terms of some exceedingly toxi comments, and it easily caught those and graded them properly. However its performance with some strong opinion based and even political comments was very poor. 


MIT License

Copyright 2023 Patrick Traynor

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
