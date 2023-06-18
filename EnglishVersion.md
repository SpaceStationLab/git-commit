
<p align="center">
  <img src="https://cdn.inflearn.com/public/files/courses/328008/291d3a74-4c8a-434c-b2e3-73112724da17/328284-1.png" height="150">
</p>


## Github

Until now, github has been a space for one person to write project code or blog posts.

Therefore, I didn't care about the contents of the commit message, <br>
Recently, as I worked with my friend, I felt the need to unify the commit message

When we worked together, we didn't pay attention to commit messages, so we had the following problems.

  - **Can't see what they've done to each other at a glance.**
  - **Must read the code for what the other person has worked on.**

Each person doesn't have to match the message perfectly, but <br>
It is important to write it in a uniform way so that you can see what you've done with just a message.

## 1. Importance of Commit Message Rules

The following are the reasons why rules are required when creating commit messages.

- Communication with team members
- Convenient historical tracking
- Issue Management

## 2. Formats for Commit Messages

Let's organize the contents one by one when writing a commit message. <br>
The overall format is as follo


<p align="center">
  <img src="https://blog.kakaocdn.net/dn/xteMz/btskha3GV9d/jJOTTbW8lzcKExUDpri7EK/img.png" height="250">
</p>


## 2.1. Type

The commit shows what the action is for through the keyword.

<p align="center">
  <img src="https://github.com/DoyoungDev/git-commit/assets/110442250/17c4f08e-6879-44f0-b4a2-ba5d594bdeea" height="390">
<p>

  
## 2.2 Subject
Title of the commit message.

- The title does not exceed 50 characters and does not have a period.
- Create a commit type in the title together.
- Write in command tone without using the past tense.
- The title and body are separated by a single line.
- The first letter of the title must be capitalized.
- If it is related to an issue, add the issue number.

### Example of Subject

```
Feat: Added new RFID recognition capabilities
```

## 2.3. Body
The body of the commit message.

- It is optional and does not need to be written to all commitments.
- You must not exceed 72 characters per line.
- Focus on what and why rather than how to write the content.
- In addition to the description, you also create a reason for the commit.

### Example of Subject
```
Added new RFID feature recognition functionality
- RFID Reader.java: Added RFID recognition due to user requirements
```
## 2.4. Footer
The conclusion of the commit message. <s>If there's no issue..</s>

- It is optional and does not need to be written to all commitments.
- Use to add an ID to track an issue.
- Resolved - Resolved Issue ID
- Related - Issue ID associated with the commit
- Note - Issue ID for reference

### Example of Footer
```
Resolution: #123
Related: #321
Note: #222
```

### Exmample of Full Commmit Message

```
Feat: Added new RFID recognition (#123)

Added new RFID feature recognition functionality
- RFID Reader.java: Added RFID recognition due to user requirements

Resolution: #123
```

## Conclusion 
  
Writing commit messages well is a basic habit in collaboration.

If you know I can't see other people's work at a glance<br>
Others should also be aware that it is difficult to grasp the contents of the commit I have written.

If I can work with the above convention in the team, I think I can figure out the history and solve the code review in a short time.
  
## Ref

- [English dictionary for good git commit messages](https://blog.ull.im/engineering/2019/03/10/logs-on-git.html)
- [Commit message Wrap up line](https://guuumi.tistory.com/128)
  
  
## Example 

<p align="center">
  <img src="https://blog.kakaocdn.net/dn/dtCL21/btsklmCgFie/QDPW3LejAG0htEsJ3N628k/img.png" height="600">
</p>
