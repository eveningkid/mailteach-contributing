# Contribute To MailTeach
So, you want to add your course to mailteach and wonder how to proceed? Awesome!

> If you need a sample repository, here's [one for the ES6 course](https://github.com/eveningkid/mailteach-learn-es6).

## First, create a Github repository
I'd recommend you to call it as the following `mailteach-course-name`, e.g. `mailteach-learn-es6`.  
Initiate it with a **simple MIT licence file**.

## Second, add your lessons
- Every lesson should have its own file, e.g. `lesson-1.md`, `lesson-2.md`, ...and so on.
- All your files must use both the [markdown syntax](https://guides.github.com/features/mastering-markdown/) and `.md` extension. 

## Third, create your course description file
You'll now need to create a `mailteach.json` file at the root of your repository.  
The syntax should look like the following:
```JSON
{
  "lessons": {
    "1": {
      "title": "Arrow functions",
      "path": "lesson-1.md"
    },
    "2": {
      "title": "Classes",
      "path": "lesson-2.md"
    },
    "3": {
      "title": "Enhanced Object Literals",
      "path": "lesson-3.md"
    }
  }
}
```
Your file **must** have a `lessons` key with a **set** of child lessons.  
Each lesson needs to be given a **title** and a **path** attributes.

## Finally, open an issue on this repo
Here you are, your course is finally ready. You now want to submit it to me so I can add it to the mailteach courses' list.  
Now [create an issue on this repository](https://github.com/eveningkid/mailteach-contributing/issues/new) and try to explain the goal of the course, followed by its repository github URL.  

The suggested issue format is the following:
```Markdown
Hi,

**Motivation:** I want to suggest my course which is about...  

**Repository:** [https://github.com/user/repo](https://github.com/user/repo)  
**Number of lessons**: 11  

Thank you!
```

## Thank You!
This project aims to help people to finally learn things they've been procrastinating about for a long time.  
I believe that small content, put into a simple and pretty way would be the answer to this.  
I don't know if anyone will ever contribute to this project, but I do want to thank you if you take some of your time to take part to this.  

Actually, I guess that every future learner will want to thank you as well!  

Have a nice day, and happy coding! :)

— Arnaud
