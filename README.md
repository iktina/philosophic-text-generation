# Philosophic Text Generation
Philosophic Text Generation service for SingularityNET
## Welcome
## What’s the point?
The service receives a textual seed in English and uses it as input to the neural GPT-2 model trained to solve diverse text generation task using large-scale Reddit-dump based dataset and outputs the generated text for a given seed.
The basic commonsense model generates diverse text adapting to the style and content of the given text seed.
## Model details:
### The user must provide the following inputs in order to start the service and get a response:
#### Inputs:
`request`: json string

Example of input file content:

`{"start_text": "Hi!", "max_len": 512, 'temperature': 0.7, 'top_k': 0, 'run_name': "philosopher_355M"}`

#### Outputs:
`answer`: json string

Example of output file content:
`{"result": "some text as an answer"}`

## What to expect from this service?
### Inputs:
```"start_text": What can I```
### Outputs:
```"result": What can I do, in the presence of a young woman, who, in the crisis I have described, has her eyes fixed upon her mouth; I ask why she is so pale? The young woman is very puzzled. I ask why this is so. Is she not very much in love?```
