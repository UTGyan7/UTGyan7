# **Hello!👋** It's **Utkarsh** here
- I'm **Utkarsh Gyan**
- Enthusiastic **14 y/o**
- Passionate about **Coding** and **AI**
- Currently working on [CloudScissors](cloudscisors.streamlit.app)
## 🌟 About Me

- Keen interest in **Coding** and **Artificial Intelligence**
- Basic understanding of **Python** programming
- Beginning to learn **Java**
- Aspiring to explore **AI**, **ML** and **Data Science**

## 💻 Technical Skills

- **Python**: Basic knowledge
- **AI** and **ML:** Knows fundamentals
- **Web Scrapping:** Very basic knowledge and experience
- **Java**: Introductory understanding
- Quick learner and **adaptable to new technologies**

## 🚀 Future Goals

- Advance skills in **Python and Java programming**
- Explore **Artificial Intelligence, Machine Learning** and **Data Science**
- Gain knowledge about **Web Scrapping**
- Learn about **Quantum Computing**
- Develop **freelancing** skills in the **tech industry**

## 🏆 Achievements and Projects

- Basic Calculator in Python.
    
    https://replit.com/@utku210411/Basic-Calculator-in-Python
    
- Electronic Voting Machine (EVM) with Python
    
    ```python
    import os
    import time
    
    # Candidates and their vote counts stored in a dictionary
    candidates = {
        "cristiano ronaldo": 0,
        "lionel messi": 0,
        "taylor swift": 0,
        "bts": 0,
        "black pink": 0,
        "narendra modi": 0,
        "rahul gandhi": 0,
        "donald trump": 0,
        "joe biden": 0,
        "vladimir putin": 0,
        "adolf hitler": 0,
        "israel": 0,
        "palestine": 0
    }
    
    def clear_screen():
        os.system("cls" if os.name == "nt" else "clear")
    
    while True:
        print("Electronic Voting Machine (EVM)")
        print()
        time.sleep(2)
    
        # Display candidates
        print("Vote for any ONE of the following:")
        for candidate in candidates:
            print(f"- {candidate.title()}")
        print()
        time.sleep(7)
    
        # Get the vote input
        vote = input("> ").strip().lower()
    
        # Check if the vote is valid
        if vote in candidates:
            candidates[vote] += 1
        else:
            print("Invalid vote. Please try again.")
            time.sleep(2)
            continue
    
        time.sleep(1)
        clear_screen()
    
        # Display current results
        print("Results till now:")
        for candidate, votes in candidates.items():
            print(f"{candidate.title()}: {votes}")
        print()
        time.sleep(10)
    
        # Ask if the user wants to vote again
        again = input("Once more? (yes/no): ").strip().lower()
        if again != "yes":
            break
    
        clear_screen()
    
    ```
    
- [Rock Paper Scissors Game](https://github.com/UTGyan7/Rock-Paper-Scissors/blob/main/rock%20paper%20scissors%20game.py)
    
- [AI Chatbot (Cloud Scissors)](cloudscisors.streamlit.app) : A Cohere API powered AI Chatbot
    
## 📚 Courses attended

- [Java Fundamentals by Coddy](https://coddy.tech/courses/java_fundamentals) | [Certificate](https://coddy.tech/certifications/YXgU36-cpiHhr)
- [100 Days of Code by Replit](https://replit.com/learn/100-days-of-python?from=hub)

## 📞 Contact Information

- Email: [utku210411@gmail.com](mailto:utku210411@gmail.com)
- GitHub: https://github.com/UTGyan7
- Replit: https://replit.com/@utku210411

Thank you for visiting! 

I'm excited about the possibilities in technology and look forward to learning and growing in this field.
