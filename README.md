Core Capabilities
Speech Recognition

Converts spoken input to text via Google's Speech Recognition API.

Intelligent Response Generation

Utilizes Cohere's language model for contextual replies.

Voice Synthesis

Converts text responses to speech using pyttsx3.

Conversation Memory

Maintains dialogue context for coherent interactions.

Voice Customization

Adjust speech rate, volume, and voice profiles.

Prerequisites
Python 3.6+

Cohere API Key (Free tier available)

Hardware: Functional microphone and speakers

Installation
bash
pip install SpeechRecognition pyttsx3 cohere pyaudio  
Configuration
Obtain Cohere API Key:

Register at cohere.com

Replace 'your-cohere-api-key' in the script with your key.

Customize Voice (Optional):

Modify speech parameters in the text_to_audio() function:

Rate: Words per minute

Volume: 0.0 to 1.0

Voice ID: Select from available system voices

Execution
bash
python chatbot.py  
Start Speaking: When prompted, speak clearly into your microphone.

End Session: Say "exit" to terminate the conversation.

Troubleshooting
Issue	Solution
Microphone not detected	Check connections/default audio devices
Low speech accuracy	Reduce background noise; speak slower
Cohere API errors	Verify key validity/network connectivity
No audio playback	Confirm speaker settings in OS/pyttsx3
Contribution Guidelines
Contributions are welcome!

🪄 Fork the repository

🐛 Submit issues for bugs/feature requests

🔄 Create pull requests for enhancements

Enjoy natural conversations with your AI assistant! 🎤🤖
