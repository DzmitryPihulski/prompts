AYA_PROMPT_TEMPLATE = """[Query]
    {inputs}

    [Reference Answer]
    {targets}

    [Model Answer]
    {content}

    [Instructions]
    You are an expert evaluator. Determine whether the model's answer is appropriate and factually relevant with respect to the query.

    The reference answer is an **exemplary** response that illustrates what a good answer might look like. However, it is not the only valid answer.

    Prioritize evaluating whether the model's answer satisfies the intent and requirements of the query. Use the reference answer as a guide, but do not require the model to match it exactly.

    Respond with the final judgment in this JSON format:

    {{
    "decision": true
    }}

    Only return this JSON in your final answer.
"""