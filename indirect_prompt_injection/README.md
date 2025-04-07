 # INDIRECT PROMPT INJECTION

This is an AI LLM vulnerability which occurs when an LLM uses external content, typically agents that uses tools from external systems, and processes that before sending a result to a user. And there, if the response from the external system has untrusted content like a prompt injection then it can hijack the subsequent actions that the LLM instructs the agent executor to make. 
