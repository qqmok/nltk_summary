# nltk_summary
## Problem
Goal of this exercise is to generate summarization of two texts, following the pipeline:
* Measure the length of the two documents;
* Compute the target lengths in a proportional way with respect to the length of the documents;
* Slice the first document from start to a point within the context window;
* Summarize the slice with no request for size of the target;
* Repeat the previous two steps until the end of the document;
* Collate the summaries above; 
* Repeat the shrinking activities until the summary size is within the context window;
* Save the document;
* Repeat the summarization for the second document;
* Generate the query.
