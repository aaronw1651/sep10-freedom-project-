# Entry 2
##### X/X/XX
## Reflection:
This unit on GitHub was incredibly valuable for learning how to collaborate on code. I now understand how to work effectively with others, which speeds up the development process. Key commands I learned were git add, git commit, and git push. These are essential for managing changes and updating repositories.
## Challenges
One challenge I faced was consistently navigating to the correct directory using cd. For example, instead of cd wd/classwork, I should have been using the full path or a more specific directory structure. This organizational step is crucial for keeping projects tidy.
Another point of confusion was resolving merge conflicts. When encountering markers like <<<<<<< HEAD, =======, and >>>>>>> branch-name, I initially wasn't sure how to proceed. Now, I understand that I need to manually resolve the conflict by choosing the correct code, removing the conflict markers, and then committing the changes.
Example of a more general merge conflict:


<<<<<<< HEAD
// Code from your current branch
function greet(name) {
  return "Hello, " + name + "!";
}
=======
// Code from the incoming branch
function greet(name) {
  return `Hi, ${name}!`;
}
>>>>>>> feature/new-greeting


To resolve this, you would edit the file to choose the desired version (or combine them), remove the conflict markers, and then commit:


function greet(name) {
  return `Hello, ${name}!`; // Resolved to use template literals
}


Key takeaways:
Detailed Notes: I've learned the importance of thorough note-taking to avoid forgetting crucial details.
Resource Review: Regularly reviewing course materials is essential.
Collaborative Learning: Asking for help from peers is a valuable resource.
Patience: Coding can be challenging, and patience is key.
Concluding Remarks:
While this unit was challenging due to the new terminology and concepts, it was also very rewarding. My notes proved to be invaluable, and I now feel more confident in my ability to collaborate using GitHub.



[Previous](entry01.md) | [Next](entry03.md)

[Home](../README.md)
