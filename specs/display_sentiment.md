# Display Sentiment

#### Description:

Create a CLI tool that interfaces with a public NLP API and send user input for analysis. Display the output result in a user-friendly message.

#### Behavior:

-   Users should be able to call the program via terminal like `sentiment <string>` providing a sentence to be analyzed.
-   Your program should try to parse the string and if successful, it should send it to the API of your choice.
-   It should then display the result with a scale that you can fine tune. e.g. `Positive/Neutral/Negative - Confident Positive` etc.

*You should handle the following error cases and display the appropriate message to the user:*

- Invalid user input.
- API Service not responding.
