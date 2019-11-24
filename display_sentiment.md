# Display Sentiment

#### Description:

Create a CLI tool that interfaces with a public NLP API and send user input for analysis. Display the result in a user-friendly scale.

#### Behavior:

-   Users should be able to call the program via terminal like `sentiment "I'm not sure if I agree with what you're saying."` providing a single string argument.
-   Your program should try to parse the string and if successful, it should send it to the API of your choice.
-   It should then display the result with a scale that you can fine tune. e.g. `Positive/Neutral/Negative - Confident Positive` etc.

*You should handle the following error cases and display the appropriate message to the user:*

- Invalid user input.
- API Service not responding.
