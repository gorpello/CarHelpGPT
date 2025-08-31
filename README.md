# CarHelpGPT  

**CarHelpGPT** is a SwiftUI application that allows users to ask questions about car problems and car improvements. The app integrates with ChatGPT to provide helpful and focused answers about cars, while refusing to answer questions outside of this domain.  

## The Purpose  

Use the power of large language models to build a domain-specific assistant. This app demonstrates how to limit responses to a specific topic (car-related help), ensuring accurate and focused answers.  

## Features  

- Ask questions about car problems.  
- Get suggestions for car improvements.  
- Receive clear, helpful answers powered by ChatGPT.  
- Refuses to answer questions that are not car-related.  

## Exercise  

Your task is to create a new iOS project based on the demo app and transform it into a **CarHelpGPT App**. This will require modifying the logic so that ChatGPT only provides car-related answers and politely refuses to answer unrelated topics.  

### Requirements  

The project type is a SwiftUI application with at least one main View and shall run on the simulator.  

- The project shall allow the user to input a question.  
- The project shall send the question to ChatGPT.  
- The project shall return an answer only if the topic is related to car problems or car improvements.  
- If the user asks a question outside of cars, the app shall politely refuse to answer.  
- The app shall run without crashing.  

* For extra credit:  
- Add categories of help, such as **Maintenance**, **Repairs**, and **Upgrades**, so the user can choose before asking.  
- Provide example questions to guide the user.  

## How to Use  

1. **Run the app** in Xcode on a supported Apple platform (iOS or macOS*).  
2. **Enter a question** about a car problem or improvement.  
3. Tap **Ask CarHelpGPT** to send the question.  
4. View the answer displayed in the app.  
5. If the question is not car-related, the app will refuse to answer.  

## Requirements  

- Xcode 15 or newer  
- Swift 5.9 or newer  
- SwiftUI  
- OpenAI API or equivalent integration for ChatGPT  
- iOS 17+ or macOS 14+ (depending on your deployment target)  

## Getting Started  

1. Clone the repository.  
2. Set up your OpenAI API key (or equivalent) in the app.  
3. Open the project in Xcode.  
4. Select a simulator or device and run.  

## Credits  

Created by Gianluca Orpello.  
Uses the OpenAI API for ChatGPT responses.  

## License  

MIT License. See [LICENSE](LICENSE) for details.  

