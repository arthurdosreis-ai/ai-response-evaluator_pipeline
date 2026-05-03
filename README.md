# AI Response Evaluation Pipeline (Python)

This project started as a simple attempt to compare two AI-generated responses, but quickly turned into a deeper exploration of how evaluation actually works in practice.

At the beginning, the process was not smooth. Dealing with errors, fixing indentation issues, and understanding how to structure data in Python was often frustrating. However, that phase turned out to be essential — it helped me build control over the environment and develop a more structured way of thinking.

Once the code was stable, the focus shifted from “making it run” to “making it meaningful”. Instead of relying on simple comparisons, I introduced a basic rubric (relevance, clarity, completeness) to simulate how real evaluation tasks are performed.

From there, I implemented A/B comparison, added an automatic decision (winner_auto), and then introduced a human perspective (human_choice) to measure agreement between model output and human judgment.

Finally, the results were structured and exported as JSON, turning the script into a small but complete evaluation workflow.

## What this project represents

More than just code, this project reflects:
- the transition from trial-and-error to structured problem solving  
- the importance of frustration as part of the learning process  
- the ability to turn simple ideas into more realistic evaluation systems  

## Tech used
- Python  
- JSON  

## Outcome
A working prototype that simulates how AI responses can be evaluated, compared, and analyzed — similar to workflows used in data annotation and response evaluation tasks.

## How to run

1. Open the notebook  
2. Run all cells  
3. The script will generate results.json  

## Project Structure

- ai-response-evaluator.ipynb  
- results.json  

## Example Output

The results.json file includes:

- scores for each response (relevance, clarity, completeness)  
- total scores  
- automatic winner (winner_auto)  
- human comparison (agreement
