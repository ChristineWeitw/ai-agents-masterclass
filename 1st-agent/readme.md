run the agents.py file and expected outputs looking like:

(ai-agents-mastereclass) christinewei@Dodos-MacBook-Pro 1st-agent % python agents.py

Chat with AI (q to quit): hey

[DEBUG] response_message object:
ChatCompletionMessage(content='Hello! How can I assist you today?', refusal=None, role='assistant', audio=None, function_call=None, tool_calls=None, annotations=[])
Hello! How can I assist you today?
Chat with AI (q to quit): create a task for me to be in the office on Wednesday, assign to me

[DEBUG] response_message object:
ChatCompletionMessage(content=None, refusal=None, role='assistant', audio=None, function_call=None, tool_calls=[ChatCompletionMessageToolCall(id='call_Bd49XIM5jSa1zI38jPSwFINb', function=Function(arguments='{"task_name":"Be in the Office","due_on":"2025-05-28"}', name='create_asana_task'), type='function')], annotations=[])

[DEBUG] second_response object:
Choice(finish_reason='stop', index=0, logprobs=None, message=ChatCompletionMessage(content='I\'ve created a task for you to be in the office on Wednesday, May 28, 2025. The task is assigned to you and is in the "agents-mastereclass" project under the "To do" section. \n\nHere\'s the [link to the task in Asana](https://app.asana.com/1/68/project/58/task/585). Let me know if you need any more help!', refusal=None, role='assistant', audio=None, function_call=None, tool_calls=None, annotations=[]))
[DEBUG] second_response.content:
ChatCompletionMessage(content='I\'ve created a task for you to be in the office on Wednesday, May 28, 2025. The task is assigned to you and is in the "agents-mastereclass" project under the "To do" section. \n\nHere\'s the [link to the task in Asana](https://app.asana.com/1/1522/project/285/task/2582). Let me know if you need any more help!', refusal=None, role='assistant', audio=None, function_call=None, tool_calls=None, annotations=[])

I've created a task for you to be in the office on Wednesday, May 28, 2025. The task is assigned to you and is in the "agents-mastereclass" project under the "To do" section. 

Here's the [link to the task in Asana](https://app.asana.com/1/8252/project/252/task/252). Let me know if you need any more help!
Chat with AI (q to quit): 2