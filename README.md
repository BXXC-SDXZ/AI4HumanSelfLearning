# AI4HumanSelfLearning

I am a recent computer science major who has been struggling with self-study. I heavily rely on large language models, and with their help, I have learned a lot and made rapid progress.

I have found that large language models (such as ChatGPT-4o and others) are incredibly helpful to human learners due to their strong prior knowledge and RAG technology, as well as their increasingly powerful reasoning and analogical abilities.

This repository will be used to store my discoveries and insights (currently focused on human self-study in the field of computer science, but can be expanded to other areas in the future), and I would love to welcome and look forward to other like-minded friends who share their experiences of learning with large models.



## Motivation Cases
#### (1) Give you ToDoList 

You are a learner, faced with a field you have not touched, your biggest problem is often "don't know where to start." It is a little too coarse and takes too much time to start from scratch. However, the most common requirement for computer learning workers is to master a certain skill in the fastest time (one or two days or even an afternoon). Going to the official documents to learn specific content is not only easy to face problems that can not be found, but more difficult is that the cold documents often make you feel difficult at the beginning.

Now that you have your LLM, you can prompt it like this:

- **Introduce yourself**: who you are (computer science student/graduate student/specialist), what you have studied in general (already familiar with certain programming languages such as C++ or courses you have taken such as Data Structures);
- **Your needs**: What do you want to learn in how long and with what focus? (For example: I want to quickly understand java in 5 hours, the point is that I need a deep understanding of object-oriented programming principles);
- **Command**:Now please give me a todoList, let me just follow this list one by one to complete the above tasks, so as to guide me to learn this knowledge.

Then you really get a very reliable, detailed list (like the **/Motivation_Cases/JAVA_FastLearn_ToDoList.md** file in this repository); It is worth mentioning that as you complete the small tasks on your list, **you can even let the large model continue to explain these small knowledge points directly to you**, without spending more time searching for them, which greatly saves your learning time.


#### (2) Clever visualization ability

When you ask an LLM a professional question, if you just ask it, it will give you a detailed, professional answer, but also very obscure. At this point if you use the word "visualization" which I find very interesting, the LLM will give you extremely illuminating answers, because as language models, large models are really powerful metaphors.

For example, "Visualize why java's main method needs to be static."

**The following is from the generation of ChatGPT-4o:**

"When we run a Java program, the Java Virtual Machine (JM) loads the main class (that is, the class that contains the main method) and looks for the entry point.
Instead of automatically creating the object, the JVM calls the main method of the class directly.

Analogy: An automated factory

Imagine you have a factory and start the factory without hiring workers (without creating objects). You just need to press a switch (call the main method) and the machine starts running. This means that the switch itself cannot depend on the worker, but must belong to the entire factory. In Java, this "switch" is a static method because it belongs to a class, not an instance object."


