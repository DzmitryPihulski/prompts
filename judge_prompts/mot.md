REASONING_PROMPT_TEMPLATE = """[Query]
    {inputs}

[Reference Answer]
    {targets}

[Model Answer]
    {content}

[Instructions]
You are an expert evaluator. Determine whether the model's final answer is factually correct and satisfies the requirements of the query.

Ignore the reasoning steps. Focus solely on the **correctness of the final answer**.

Use the reference answer as the source of truth. Do not accept alternative answers that differ from it unless they are mathematically or logically equivalent.

Respond with your final judgment in this JSON format:

{{
  "decision": true
}}

Only return this JSON in your final answer.
"""