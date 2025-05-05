# data-classification

**Author:** Bo Zhao, 206.685.3846 or zhaobo@uw.edu; **Points Available** = 50

This lab helps you critically understand how **geospatial data is classified and visualized**, building directly on Wilson (2011) and Kwan (2012). You will:

- Retrieve real-world facility data from OpenStreetMap (OSM)
- Apply **two different classification schemes**
- Visualize both schemes **side-by-side** on interactive maps
- Reflect on how categorization shapes what we see—and what we don't
- Learn how to make a **counter-map**.

> **Guiding question**: How do classification schemes shape urban narratives, planning decisions, and power relations?

Please launch the youtube crawler script by clicking this button[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jakobzhao/data-classification/blob/main/data.ipynb). This button will enable you to open the file [data.ipynb](data.ipynb) on Google Colab.

After you execute the python code on Google colab, you have now visualized the same geospatial data under two different classification perspectives:

- **Planner View**: prioritizes formal civic infrastructure.
- **Community View**: includes alternative or under-valued sites.

Now you know how to classify map objects. In this exercise, you will **design a counter-map** that centers a marginalized group’s experience (e.g., unhoused people, immigrants, youth, disabled residents). Please ask yourself, What counts as a “resource” from their perspective? What’s missing from official views?

### Part 1: Define Your Own Classification Logic

- Propose **your own categories** (e.g., `safe_space`, `environmental_risk`, `youth_value`, `invisible_infrastructure`, etc.)
- You may define **2–4 categories** and choose how to group or differentiate them.
- Justify your choices:  
  > What values, communities, or problems are you trying to highlight through your classification?

### Part 2: Implement and Visualize

- Write a custom classification function in Python.
- Apply it to the OSM facility data.
- Create a **single interactive map** with Folium (or DualMap if comparing two logics).
- Use color coding, popups, or symbols to make your perspective visible.


## Deliverable

You are expected to submit your reflections via email to your instructor. In your message, please incorporate the provided script to create your own version of place classification. At the end of your message, be sure to answer the questions provided.

Answer the following questions (300–500 words):

1. **What logic guided your classification?**  
   How is it different from the planner or community view provided in this lab?

2. **What changes appeared on your map?**  
   Which spaces became more visible or important under your scheme?

3. **How would you present your map to a specific audience** (e.g., city planners, youth groups, housing advocates)?  
   Would you change anything about how it's designed or explained?
   
> Your categories don’t need to be perfect or comprehensive—they should provoke insight and reflection. Please Consider how **color, interactivity, and narrative** shape the interpretation of your map. As we did in the previous lab, please creatively use AI to help you finish this assignment.

After you finish this exercise, please also go over the following script by clicking this button[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jakobzhao/data-classification/blob/main/rs-data.ipynb). This button will enable you to open the file [rs-data.ipynb](rs-data.ipynb) on Google Colab.

**Note:** Lab assignments are required to be submitted electronically to Canvas unless stated otherwise. Efforts will be made to have them graded and returned within one week after they are submitted.Lab assignments are expected to be completed by the due date. ***A late penalty of at least 10 percentage units will be taken off each day after the due date.*** If you have a genuine reason(known medical condition, a pile-up of due assignments on other courses, ROTC,athletics teams, job interview, religious obligations etc.) for being unable to complete work on time, then some flexibility is possible. However, if in my judgment you could reasonably have let me know beforehand that there would likely be a delay, and then a late penalty will still be imposed if I don't hear from you until after the deadline has passed. For unforeseeable problems,I can be more flexible. If there are ongoing medical, personal, or other issues that are likely to affect your work all semester, then please arrange to see me to discuss the situation. There will be NO make-up exams except for circumstances like those above.
