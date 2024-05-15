# GenAI Homepage

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Code annotation Examples

### code blocks
Some `code` goes here.

### A plain codeblock:

``` py linenums="1" hl_lines="2 3"
from crewai import Agent, Task, Crew
from langchain_openai import ChatOpenAI
import os

os.environ["OPENAI_API_KEY"] = "NA"


llm = ChatOpenAI(
model = "mixtral_q4",
base_url = "http://localhost:11434/v1")
```