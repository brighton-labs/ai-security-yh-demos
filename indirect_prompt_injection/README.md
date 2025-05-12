 # INDIRECT PROMPT INJECTION

This is an AI LLM vulnerability which occurs when an LLM uses external content, typically agents that uses tools from external systems, and processes that before sending a result to a user. And there, if the response from the external system has untrusted content like a prompt injection then it can hijack the subsequent actions that the LLM instructs the agent executor to make. 

https://gist.github.com/yousshark/9413c9fe3cf161f3328077ae9b0f12e1

le script en rapport avec le gist :
https://github.com/brighton-labs/ai-security-yh-demos/blob/main/indirect_prompt_injection/ipinjec_script_openchatHF2.py
