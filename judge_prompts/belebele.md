BELEBELE_PROMPT_TEMPLATE = """[Passage]
    {flores_passage}

[Question]
    {question}

[Choices]
    A. {mc_answer1}  
    B. {mc_answer2}  
    C. {mc_answer3}  
    D. {mc_answer4}

[Correct Answer]
    {correct_answer}

[Model Answer]
    {content}

[Instructions]
You are an expert evaluator. Determine whether the model selected the correct answer based on the passage and the question.

Only consider whether the selected choice matches the correct answer. Do **not** evaluate explanation quality or reasoning.

Respond with your judgment in this JSON format:

{{
  "decision": true
}}

Only return this JSON in your final answer.
"""