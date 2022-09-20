# JavaScriptFrameVisualizer
A Javascript Scope/Frame Visualizer that keeps track of method calls.

One concept that was taught to my client-side scripting class by our instructor was JavaScript frames that were generated upon each function call. This program uses CodeMirror to gather JavaScript code from the user. It takes this information, saves it to local storage, parses the instructions into tokens, and then uses them to build the frames recursively for each method call.
