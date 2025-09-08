# Ollama Studio
Ollama Studio - Research Tool

OllamaStudio:
1. Enable to test different prompt-engineered with various LLM models
2. Enable to choose the best suitable performance for a specific prompt among various models
3. All the results from testing various models are show in one big output pane
4. The output pane with the results can be save to clean html file
5. The encoded context for each model and in any turn in the conversation - enable to return to any turn in the chat for any model
6. Enable to choose whether to memorize each turn (context) and if the output is streamed
7. Enable to set model parameters as: temperature, and more
8. Simple UI that works in any browser and almost any desktop
9. Beside of LLM, enable to test javascript and html syntax and functionality

<br><br>

<pre>
Requirements:
1. Install Ollama if not installed: https://ollama.com/
2. Install Java (min. JDK8) if not installed: https://openjdk.org/

Run Ollama Studio:
1. Download and extract the latest release tool (zip)
2. Run the shell file (.bat or .sh) according to your OS

Ollama Models:
1. Check prefered model from the model list in Ollama Studio (bottom-left drop-down-list)
2. If the model not installed, pull it from: https://ollama.com/library
3. Verify suggested models are downloaded in the "supported-models.txt" file
</pre>

<br><br>

OllamaStudio is writen in pure java and works in Windows, Linux and macOS.
<br>
If not loaded automatically in the browser, open: http://localhost:8000/
<br>
Note on popup alert-message in windows: 
<br>
- Allow the Windows Firewall to open port 8000 for localhost
<br><br>

Supported Ollama-Models in OllamaStudio 
<br>(list is updated in each OllamaStudio-release)
<br>- available in the "supported-models.txt" file
<br> ** Almost all LLM models in the OllamaStudio list are capable of running with 8GB-GPU. 

<br><br>
Screenshorts - Examples
<br><br>
![alt text](img/example-1.png?raw=true)
<br><br>
Dark mode
<br>
![alt text](img/example-2.png?raw=true)

<br><br>
Suggested Hardware:
<br> GPU 8GB or higher
<br> Fast NVMe

<br><br>
UI Options
<br>----------
<br><br>== Top-Bar ==
<br>1) Chat Command (Prompt Engineering): Summarize,...
<br>2) Increase/Decrease Input and Output Panels 
<br>3) Increase/Decrease Font-Size
<br>4) Theme (Light Mode,...,Dark Mode) and Dark-Mode Variations
<br>5) Reset: reset output (LLM response) on freeze

<br><br>Chat Command
<br>![alt text](img/top/top-1.png?raw=true)
<br>![alt text](img/top/top-1a.png?raw=true)

<br><br>Increase/Decrease Font-Size 
<br>![alt text](img/top/top-2.png?raw=true)
<br>![alt text](img/top/top-2a.png?raw=true)

<br><br>Theme (Light Mode,Dark Mode) 
<br>![alt text](img/top/top-3.png?raw=true)
<br>![alt text](img/top/top-3a.png?raw=true)

<br><br>Dark-Mode Variations  
<br>![alt text](img/top/top-4.png?raw=true)
<br>![alt text](img/top/top-4a.png?raw=true)

<br><br>== Bottom-Bar ==
<br>1) General/Model Options
<br>2) Session Control: Chat with/without context (memory between chats) 
<br>3) Stream Control: Chat output stream of token-by-token or final answer rewsponse
<br>4) Text Direction: Left-To-Right or Right-To-Left
<br>5) Save all chat history including prompt,context, and more
<br>6) Print basic help of Ollama-Studio
<br>7) Clear input/output panels

<br><br>General/Model Options
<br>![alt text](img/bottom/bt-1.png?raw=true)
<br>![alt text](img/bottom/bt-1a.png?raw=true)

<br><br>Session Control
<br>![alt text](img/bottom/bt-2.png?raw=true)
<br>![alt text](img/bottom/bt-2a.png?raw=true)

<br><br>Stream Control
<br>![alt text](img/bottom/bt-3.png?raw=true)
<br>![alt text](img/bottom/bt-3a.png?raw=true)

<br><br>Text Direction 
<br>![alt text](img/bottom/bt-4.png?raw=true)
<br>![alt text](img/bottom/bt-4a.png?raw=true)

<br><br>







