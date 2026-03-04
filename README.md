# tippitytappity-design

tippitytappity is a program to practice typing


## Data model

```mermaid
classDiagram
class User{
  - userId: int
  - setUserId(userId): int
  + getUser(signIn): int
  + signOut(): void
  }
  class Accuracy{
       - test_phrase: string
       - user_input: string

  }
  class Speed{
        - count
        - startTime(): int
        - endTime(): int
        - setTimer(): time
        + getTime(): string
  }
  class generatePhrase{
      - setPhrases: string
      + getPhrases: string
  }
  class Test{
    - window size: int,int
    - setPhrase(rand): string
    - setUserInput(): string
    - getTest_phrase(): string
    + getInput: string
    + printPhrase(): void
    + getUserInput(): string
    + getTest_phrase():string
  }
  class history{
    - userId: int
    + getUserId(userId)
    + savehist()
  }
```
