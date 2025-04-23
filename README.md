# Red Rover Code Puzzle
Thank you for your interest in joining our team.  The following coding exercise helps us get a sense for your approach to turning a requirement into code. If you have any questions please reach out.

## Please do not use AI for this exercise!
We tried to keep this simple enough that it doesn't take a lot of your time, but this is exactly the type of problem that AI can solve in an instant. Please do not consult AI for any part of this exercise.  Thank you for your integrity.

## Instructions
Using the technology of your choice, convert the following string: 

`"(id, name, email, type(id, name, customFields(c1, c2, c3)), externalId)"`

To this output: 
```
- id
- name
- email
- type
  - id
  - name
  - customFields
    - c1
    - c2
    - c3
- externalId
``` 

And also to this output:
```
- email
- externalId
- id
- name
- type
  - customFields
    - c1
    - c2
    - c3
  - id
  - name
```

Please send access to the source and a runnable copy of your app. 
