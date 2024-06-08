# Artificial-intellegence
def chatbot_response(user_input):
    user_input = user_input.lower()
    
    if 'hello' in user_input or 'hi' in user_input:
        return "Hello! How can I assist you today?"
    elif 'how are you' in user_input:
        return "I'm just a chatbot, but I'm here to help you!"
    elif 'your name' in user_input:
        return "I'm a simple rule-based chatbot. What's your name?"
    elif 'weather' in user_input:
        return "I'm not connected to the internet, so I can't provide weather updates."
    elif 'bye' in user_input or 'goodbye' in user_input:
        return "Goodbye! Have a great day!"
    else:
        return "I'm sorry, I don't understand that. Can you please rephrase?"

# Example interaction
print(chatbot_response("Hello"))
print(chatbot_response("What's your name?"))
print(chatbot_response("How are you?"))
print(chatbot_response("Can you tell me the weather?"))
print(chatbot_response("Goodbye"))
