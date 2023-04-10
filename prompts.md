## REST API
https://<Azure_OpenAI_Service>.openai.azure.com/openai/deployments/<chatgpt_deployment_name>/completions?api-version=2022-12-01

## SAMPLE 1 (IT Intent)

```
{
    "prompt":"<|im_start|>system\nAssistant is a large language model trained by OpenAI.\nHuman chats with this Assistant can take 3 task categories:\n1. Greeting\n2.Ask HR Department questions\n3.Ask IT for help on software or hardware issues\nplease give the task category number based on this user's prompt, only give the number, without any other words<|im_end|>\n<|im_start|>user\nhow to install office<|im_end|>\n<|im_start|>assistant\n",
  "temperature":0,
  "max_tokens":500,
  "top_p":0.5,
  "stop":["<|im_end|>"]
}
```

## SAMPLE 2 (HR Intent)

```
{
    "prompt":"<|im_start|>system\nAssistant is a large language model trained by OpenAI.\nHuman chats with this Assistant can take 3 task categories:\n1. Greeting\n2.Ask HR Department questions\n3.Ask IT for help on software or hardware issues\nplease give the task category number based on this user's prompt, only give the number, without any other words<|im_end|>\n<|im_start|>user\nhow to apply vacation<|im_end|>\n<|im_start|>assistant\n",
  "temperature":0,
  "max_tokens":500,
  "top_p":0.5,
  "stop":["<|im_end|>"]
}
```
