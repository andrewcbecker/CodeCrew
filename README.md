README.md
# CodeCrew

A fork of CrewAI emphasizing multi-model collaboration for improving code generation and quality control. CodeCrew leverages the `function_calling_llm` feature within CrewAI to orchestrate tasks across LLMs specialized in code understanding and analysis.

## Key Features

* **Code Generators:** Agents using code-focused LLMs (e.g., Gemini-Pro, Code LLama) produce diverse candidate solutions to coding prompts.
* **Quality Control Chain:** Specialized agents apply a combination of logic and code-aware LLMs for tasks like:
    * Error Identification and explanation
    * Readability assessment
    * Comparative analysis of outputs
* **Best Code Selection:** Custom scoring or logic-based mechanisms to find the most reliable and effective code from the output pool.

## Motivation

Code generation with large language models is powerful, but outputs can be inconsistent. CodeCrew aims to mitigate risks by introducing:

* **Redundancy:** Multiple models generate candidates, increasing the odds of finding exceptional solutions.
* **Specialized QC:** Utilizing models trained on code understanding improves error detection beyond simple execution testing.
* **Flexibility:** CodeCrew empowers user-defined quality standards, letting you control what criteria to prioritize.


