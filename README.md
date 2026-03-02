# tippitytappity-design

tippitytappity is a program to practice typing


## Data model

```mermaid
classDiagram
  class Accuracy{
       - test_phrase: string
       - user_input: string
      -setUserInput(): string
      -getTest_phrase(): string
      + getUserInput(): string
      + getTest_phrase():string
  }
  class Speed{
        - count
        - setTimer(): time
        +getTime(): string
  }
  class generatePhrase{
      - phrases: string
      - 

  }
```
