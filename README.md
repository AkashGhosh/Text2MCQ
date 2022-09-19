# Text2MCQ
Creating MCQS from passages using AI
Used Multipartite keyPhrase Extraction Algorithm to extract keywords from the passages and keep the top 4 keywords
which are present both in summarized(Use T5 for summarization) and original passages. • Using passages and Keywords
as input we use T5 model to generate questions from the passages.We create a question for each corresponding keyword
extracted. • We use Sense2vec algorithm to extract distractors corresponding to the keywords and to filter the generated
distractors we use MMR algorithm. • Use gradio tool to visualize the MCQ generated given a text passage
