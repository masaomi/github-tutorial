# GitHub **Super-Quick** Tutorial

---

## 1. What is GitHub?

@ul[list-spaced-bullets text-09]
* Version control tool
* Command line tool (Web GUI is helpful)
@ulend

---

## 2. How to use?

@ul
1. Make an account
2. Make a new **repository**
3. Update the repository
@ulend


---

## 3. What is Repository?

**Repository**
* A unit of project (a sort of directory)
* **Local repository** the files in your computer
* **Remote repository** the files in the GitHub server

---

## 4. How to update?

1. **Add** a new file to the repository
2. **Commit** the file to the local repository
3. **Push**  the file to the remote repository

---

## 5. Additional important 3 operations

1. **Status**: check the file status
2. **Clone**: copy all the files in the remote repository to your computer, and make a local repository
3. **Pull**: update/syncronize the local repository to the remote repository

---

## 6. Summary

![summary](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2016/11/Git-Architechture-Git-Tutorial-Edureka-2.png)

Link
* https://www.edureka.co/blog/git-tutorial/

Waht is xext?
* Learn markdowon format (document)
* Use Git

Note
* demonstration
* git diff --word-diff=color

---

# Demonstration

@snapend

@snap[east span-45]
![IMAGE](assets/img/conference.png)
@snapend

@snap[south span-100 bg-black fragment]
@img[shadow](assets/img/conference.png)
@snapend

---

@snap[north-east span-100 text-pink text-06]
Let your code do the talking!
@snapend

```sql zoom-18
CREATE TABLE "topic" (
    "id" serial NOT NULL PRIMARY KEY,
    "forum_id" integer NOT NULL,
    "subject" varchar(255) NOT NULL
);
ALTER TABLE "topic"
ADD CONSTRAINT forum_id
FOREIGN KEY ("forum_id")
REFERENCES "forum" ("id");
```

@snap[south span-100 text-gray text-08]
@[1-5](You can step-and-ZOOM into fenced-code blocks, source files, and Github GIST.)
@[6,7, zoom-13](Using GitPitch live code presenting with optional annotations.)
@[8-9, zoom-12](This means no more switching between your slide deck and IDE on stage.)
@snapend


---?image=assets/img/code.jpg&opacity=60&position=left&size=45% 100%

@snap[east span-50 text-center]
## Now It's **Your** Turn
@snapend

@snap[south-east span-50 text-center text-06]
[Download GitPitch Desktop @fa[external-link]](https://gitpitch.com/docs/getting-started/tutorial/)
@snapend

