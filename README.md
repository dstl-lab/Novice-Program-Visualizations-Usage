# Novice Program Visualizations Usage

This repository contains the study materials of the paper, *"How Novices Use Program Visualizations to Understand Code that Manipulates Data Tables."* The study investigates how novices interpret code with visual tool, particularly in tasks involving data table manipulation.


### Key Findings

| Finding                                                             | Description                                                                                                                                                 | Representative Quote                                                                                                                                                                                                                       |
|---------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **In-notebook visualizations were usable and useful**               | Participants appreciated that the tool visualized code within their familiar notebook environment, finding it easy to use and useful with minimal instruction. | "Yeah, since you actually do [the groupby and aggregate] step by step, I'm like, oh, I get it." (P4)                                                                                                                                      |
| **Visualizations helped to verify assumptions**                     | The tool lowered the effort required to visualize intermediate program results, giving novices more confidence in their understanding of code.               | "Good visualization gives me more hints and gives me a clear understanding of what's going on." (P1)                                                                                                                                     |
| **Revealing normally-hidden table rows can highlight salient information** | Participants noted that the default output only shows the top and bottom rows of a dataframe, while middle rows might contain relevant information.          | "It's not that clear what has happened within each step since there might be 1,010,000 rows of information inside [hidden in the dataframe output]." (P8)                                                                                |
| **Visualization tools can generate complicated diagrams, but interaction can help users manage cognitive load** | In complex cases, the tool generated diagrams with many visual elements (e.g., arrows), which were overwhelming. However, interactions enabling selective filtering were helpful for understanding. | "I see when you put it like this, it looks very complicated, but as soon as you put the allow hovers, the hovers make it a lot easier." (P11)                                                                                             |
| **Limitations of the tool**                                         | The tool was better for understanding code rather than writing code because it lacked direct support for debugging.                                          | "I think it's better for checking instead of writing." (P4)                                                                                                                                                                               |



## Study Protocol

### Procedure

Each study session is designed to last a maximum of 60 minutes.

| Task                          | Time   | Time out of 60 | Description                                                                                             |
|-------------------------------|--------|----------------|---------------------------------------------------------------------------------------------------------|
| **Intro**                     | 5    | 5              | Introduce the study procedure and reconfirm participants' consent to record. |
| **Section 1**                 | 20     | 5–25           | 20 min total; not all tasks need to be completed. **Hard stop at 20 minutes.**                          |
| **Task 1.1**                  |        |                | Complete task.                                                                                          |
| **Task 1.2**                  |        |                | Complete task.                                                                                          |
| **Task 1.3**                  |        |                | Complete task.                                                                                          |
| **Section 2**                 | 20     | 25–45          | 20 min total; not all tasks need to be completed. **Hard stop at 20 minutes.**                          |
| **Task 2.1**                  |        |                | Complete task.                                                                                          |
| **Task 2.2**                  |        |                | Complete task.                                                                                          |
| **Task 2.3**                  |        |                | Complete task.                                                                                          |
| **Open-Ended**                | 5     | 45–50             | Fill-in-the-blank coding task. Complete task.                                                           |
| **Interview**                 | 10     | 60             | Conduct an interview with four prepared questions and collect additional comments. |



### Task Notebook Details

The task notebooks used in the study are included in this repository under the folder [`task_notebooks`](./task_notebooks). Participants were assigned one of four versions of a task notebook. Each notebook contained two sections with three tasks each and a fill-in-the-blank task at the end. The two sections in the same notebook use different but structurally similar dataset. One section provides step-by-step diagrams for the code, while the other section provides default Python output. The three tasks in the two sections correspond one by one, with similar topics and structures. The tasks are randomly shuffled within one section and named with Greek letters.

#### Notebook Versions

| Version | First Section                | Dataset | Second Section            | Dataset |
|---------|-------------------------------|---------|----------------------------|---------|
| A       | Default Output                | Sales   | Step-By-Step Diagram       | Student |
| B       | Default Output                | Student | Step-By-Step Diagram       | Sales   |
| C       | Step-By-Step Diagram          | Sales   | Default Output             | Student |
| D       | Step-By-Step Diagram          | Student | Default Output             | Sales   |

#### Task Mapping

| Task   | Sales Task | Student Task |
|--------|------------|--------------|
| Task 1 | epsilon    | theta        |
| Task 2 | zeta       | gamma        |
| Task 3 | lambda     | kappa        |

### Interview Questions

Participants were asked the following questions during the interview phase of the study:

1. How did you find the tasks? Were any particularly easy or difficult?  
2. Did the visualizations help you understand the code better? If yes, how?  
3. How comfortable do you feel working with code in general?  
4. Did you have any strategies for approaching the open-ended task?  
5. Any other feedback, comments, or questions?


### Participant Responses

Participants completed each task at their own pace, verbalizing their thought process. Afterward, they described their understanding of the code and recorded their confidence level in a Google form ([Template](https://docs.google.com/forms/d/e/1FAIpQLSe9Qxz3RSC1ZNapNS1LShJF28lUFAWzCM2njkyKgp0Z4d2iZg/viewform?usp=sharing)).

## Contact Information

**Sam Lau**  
GitHub: [@SamLau95](https://github.com/SamLau95)  
Email: sel011@ucsd.edu  

**Ylesia Wu**  
GitHub: [@ylesia-wu](https://github.com/ylesia-wu)  
Email: q7zheng@ucsd.edu  

**Qirui Zheng**  
GitHub: [@Qz07](https://github.com/Qz07)  
Email: xw001@ucsd.edu  
