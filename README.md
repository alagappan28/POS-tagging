Hello World ;)

A python program "tagger.py", will take as input a training file containing part of speech tagged text, and a file containing text to be part of speech tagged. 

The training data is pos-train.txt, and the text to be tagged is pos-test.txt. There is also a gold standard (manually tagged) version of the test file found in pos-test-key.txt that will be uses to evaluate the tagged output.

tagger.py program should be run from the command line.

"$python tagger.py pos-train.txt pos-test.txt", this will generate a text file "pos-test-with-tags.txt"

To evaluate the output "$python scorer.py pos-test-with-tags.txt pos-test-key.txt ", this will generate another text file "pos-tagging-report.txt" with the results(Accuracy and confusion matrix).

Thank you!
