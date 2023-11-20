---
title: 6. Taking the Exam
---


So, you have studied, ordered an exam and now the exam itself has started. Here is what you can expect.

**The tests themselves are divided into multiple sections - General questions, Case Studies and Labs**. You can't skip between them. Once you complete a section, you are unable to return to it.

Before you get to the actual exam questions, Microsoft will first ask you about your experience. This is not graded and it doesn't matter what you answer there.

After that you will be shown information about the exam itself. Be sure to read the total number of questions because sometimes you don't get a lab or case study at the beginning which means that you need to save time at the end for them.

<img src="/welcomeexamscreen.webp" alt="Welcome Exam screen">

Other useful information to know: On the bottom of page there are various tools that can help you

<img src="/examtools.webp" alt="Exam Tools">

Specifically, the **Calculator** and **Take a Break options**.

**Calculator** is useful when you need to count SLAs or other stuff that would take too long to do in your head.

**Take a Break** allows you to exit the room to go refresh or other stuff you forgot to do before an exam. After taking the break: **Timer will continue and you won't be able to return to any of the previous questions.** So, cheating won't help you.

**Microsoft Learn** button (launched in September 2023, not shown in the above image) will appear next to **Take Break** only for role-based exams.  The Open Book exam is <a href="https://techcommunity.microsoft.com/t5/microsoft-learn-blog/introducing-a-new-resource-for-all-role-based-microsoft/ba-p/3500870" target="_blank">introduced</a> to refer the product documentation from Microsoft Learn during the Exam. 

**On the top side:**

<img src="/examtools2.webp" alt="Exam tools again">

First You can see the question count. This counts the questions for the **current section** so if it shows 30 questions, this means that there is a very high propability there will be more questions after that.

Under the question count is the **Review** button. You can use it to navigate between the questions easily.

Then there is **Review later** box. If you aren't sure about your answer, you can toggle this and return to it from the Review screen if you have extra time.

**Leave Feedback** is not that important. If you toggle this on questions, you can then tell Microsoft after you finish the exam how bad the question was. Not relevant to the exam.

And lastly on the right, is the timer. This timer and question total is for the whole exam. So if on the left you see 30 questions and on the right there are 40 questions that means when you finish the current section, there will be 10 more questions. If there is lab or case study it is  mentioned on the **Welcome to the exam page** at the start. So don't be surprised when you finish and there is still a case study or lab waiting for you.

[**Using the Open Book - Microsoft Learn feature during your exam**](https://learn.microsoft.com)
:::note
Microsoft Learn is only available for role-based exams, it will be missing for fundamental exams.
:::

As of September 2023, Role-based Microsoft Exams now contain the option to access Microsoft Learn during your exam to look up information and if you haven't used it in the exam yet, I highly recommend reading this so you know how to correctly use it. The most important things to know is that you are still limited by the same time during your exam is it in nearly impossible to lookup all questions you get and it is Microsoft Learn, not Google so you need to know what you are looking for to find it, if you don't you are in for a bad time. 

So how to use it?

- First of all if you feel like you need the documentation to verify/find the answer, mark the question for review and return to it when you finish all the other questions and have time left (unless it is one of the questions asking about roles/cmdlets/powershell modules)
- Learn how to navigate Microsoft Learn. For example I didn't have an issue with it because I use Microsoft Learn daily in my job but that isn't the case for everyone and many people have said that they couldn't find what to look for. What is important here is to know how the page you are looking for is called or what does it contain exactly. So if you don't learn the SKUs for App Service Plans, learn how to find the page inside Microsoft Learn.
- Don't think this is your Get out of Jail free card. While having access to Microsoft Learn makes the exams easier, it isn't a free win. On average you have 2-3 minutes per questions (including lab tasks and case studies) and you won't have the time to look up what is a Virtual Machine and how to turn it on. So while you only need to know the concepts and how the products work now, it doesn't mean you can walk into the center with zero knowledge and pass it.
- On Microsoft Learn you don't get access to Q&A and your profile. It is obvious why this is but just felt like mentioning here.

**There are 3 requirements that are always present in questions and required**:

* **Solution must be as cheap as possible**
* **Administrative role must be of the least privilege**
* **Must be the simplest to implement**
So if you feel like there are 2 possible answers, try to find one that follows also these requirements.

**Here are the question types:**

:::note
 You can find most of these in the exam demo that simulates how the real exam looks like, [https://aka.ms/examdemo](https://aka.ms/examdemo)
:::

[**Active Screen**](https://learn.microsoft.com/en-us/certifications/exam-duration-question-types#active-screen-044)**/**[**Best answer**](https://learn.microsoft.com/en-us/certifications/exam-duration-question-types#best-answer-020)**/**[**Multiple Choice**](https://learn.microsoft.com/en-us/certifications/exam-duration-question-types#multiple-choice-037): I grouped these together because the strategy is the same. Choose the best answer. You can usually discard 2 answers because you either haven't heard of it or you know it is obviously wrong. So, you are left with 50/50 choice. If you feel like both are correct, think of the more elegant solution. Abide by the 3 rules I mentioned in bold earlier.

<img src="/multiplechoice.webp" alt="Multiple Choice">
<br>
<img src="/multiplechoicemultipleselect.webp" alt="Multiple Choice & Multiple Select">

[**Hot Area/Active Screen**](https://learn.microsoft.com/en-us/certifications/exam-duration-question-types#hot-area-017): It can be screenshot of basically any menu or portal that is related to the exam. AAD Connect configuration, azure portal, creating Virtual Machines for example. Your task will be to answer the question by toggling option/s in the screenshot. 

<img src="/hotarea.webp" alt="Hot Area">

It is really useful to know the menu you are interacting with and not going in blind.

[**Drag and Drop**](https://learn.microsoft.com/en-us/certifications/exam-duration-question-types#drag-and-drop-037): As the name says, pretty self-explanatory. Drag an answer from left to right.

Usually there aren't more of the same answers on the right so if you have 3 on the left and 3 on the right and have no idea, there is a good chance that all answers will be used once.  **That isn't the case with some questions** but most I encountered used this pattern.

<img src="/draganddrop.webp" alt="Drag and Drop">

**The question types below will only appear in role-based exams.**

[**Build List**](https://learn.microsoft.com/en-us/certifications/exam-duration-question-types#build-list-045): Similar to the Drag and Drop, but now you are making a list. So, you will also need to order it correctly. **Don't forget about the basics**, like resource providers in PowerShell or create resource button in Azure Portal.

<img src="/buildlist.webp" alt="Build List">

[**Repeated answer choices**](https://learn.microsoft.com/en-us/certifications/exam-duration-question-types#repeated-answer-choices-020): Probably the strangest and most confusing question type you will encounter if you haven't heard about it yet. You will be presented with one scenario. There will be a possible solution and you will be asked if it is a **full** solution to the scenario and problem. There will be multiple questions presenting the same scenario but different solutions. **After answering the question, you may not return to it.** There are usually around 4 questions in a scenario.

The strategy here is simple, if you aren't **100%** sure, pick **false**. There are 3 patterns, there either isn't presented correct answer, there is only one and there are 2. From my own experience the chance there are 2 answers is really low. So statistically it is best to always pick false unless you are sure it is correct.

[**Simulations/Labs**](https://learn.microsoft.com/en-us/certifications/exam-duration-question-types#labs-258): You will enter a virtual environment and will have to complete a series of tasks there. The only thing that matters is to get the task done. So if you are more comfortable using Cloud Shell, go for it. It is only the result that counts. Be aware that you cannot use internet to search stuff up. 

Labs take longer to score so you will not receive your score immediately.

[**Case Studies**](https://learn.microsoft.com/en-us/certifications/exam-duration-question-types#case-studies-113): You will be shown a screen with a lot of tabs and screens with tons of information in them. The important thing here: **Don't read it all!**  The first screen doesn't contain the question, so you will have to go to the next one. Only after reading the question, start going through the relevant materials.

<img src="/casestudies.webp" alt="Case Studies">

After you finish all your questions in the section, you will be presented with the Review screen (also accessible from the top tool bar).

<img src="/reviewscreen.webp" alt="Review Screen">

This doesn't necessarily mean it is the end of the exam as there may be case study or lab after. Here you can see how you and can easily access questions you didn't answer or marked for review. **Always answer all questions, even if you have no clue. You don't get negative points for guessing. If you finish the review screen and there are still unanswered questions, you've done it wrong.**

After finishing the whole exam, it still isn't over. Once you get to this window and don't want to leave feedback to the questions (or are just really anxious about how you did). **Ignore it. In the bottom right there is Exit button.**

<img src="/questionfeedbackscreen.webp" alt="Question Feedback Screen">

This will take you to the result page (if you had a lab, you won't get your result immediately).

<img src="/resultscreen.webp" alt="Result Page">

On the next page you will see your score report (no need to read it now, can access it from PearsonVue later on. And only once you hit the End button there, you finished the exam.

**This is especially important when taking a test from home so you don't get failed for leaving the screen before this.**

<img src="/scorereport.webp" alt="Score Report">

---


**Sources:**

[Prepare for an exam | Microsoft Learn](https://learn.microsoft.com/en-us/certifications/prepare-exam)
[Microsoft Learn for Exams | Techcommunity](https://techcommunity.microsoft.com/t5/microsoft-learn-blog/introducing-a-new-resource-for-all-role-based-microsoft/ba-p/3500870)
[How to use Microsoft Learn during the exam | Microsoft Video](https://www.microsoft.com/videoplayer/embed/RW1a0L5)
