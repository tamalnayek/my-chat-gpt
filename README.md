# my-chat-gpt
Spring Boot and Chat GPT openai integration
# Important Links
https://platform.openai.com/playground

https://platform.openai.com/account/api-keys
# Request
https://api.openai.com/v1/completions
Body:
{
  "model": "text-davinci-003",
  "prompt": "date of today",
  "temperature": 1,
  "max_tokens": 256,
  "top_p": 1,
  "frequency_penalty": 0,
  "presence_penalty": 0
}

# Response :
{
    "id": "cmpl-7LGV7ZbFIsxkKdRxu4kYjZMVD4C7K",
    "object": "text_completion",
    "created": 1685302673,
    "model": "text-davinci-003",
    "choices": [
        {
            "text": "\n    \n    The date today is June 8, 2020.",
            "index": 0,
            "logprobs": null,
            "finish_reason": "stop"
        }
    ],
    "usage": {
        "prompt_tokens": 3,
        "completion_tokens": 13,
        "total_tokens": 16
    }
}

# My-local-Request :
http://localhost:8080/bot/chat?prompt=What is best way to learn coding

