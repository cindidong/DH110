# DH110 Assignment 7: High Fidelity Prototype by Cindi Dong

## Description

### Tasks
- Navigate to 3 lessons and "complete" 2 lessons.
- Login and "purchase" the rest of the content.

## Prototype
### Iteration 1
![Iteration1](./Iteration1.png)

[Figma File](https://www.figma.com/file/r0msWDlELGlAJWSloyPOQg/Cognitive-Walkthrough?node-id=117%3A2652)

[Figma Prototype](https://www.figma.com/proto/r0msWDlELGlAJWSloyPOQg/Cognitive-Walkthrough?node-id=117%3A2653&scaling=scale-down&page-id=117%3A2652&starting-point-node-id=117%3A2653)

### Cognitive Walkthrough

### Iteration 2
![Iteration2](./Iteration2.png)

[Figma File](https://www.figma.com/file/Hg4KMbU53R7l7LcXRgAiyJ/Cognitive-Walkthrough-2nd-Draft?node-id=117%3A2652)

[Figma Prototype](https://www.figma.com/proto/Hg4KMbU53R7l7LcXRgAiyJ/Cognitive-Walkthrough-2nd-Draft?node-id=117%3A2653&scaling=scale-down&page-id=117%3A2652&starting-point-node-id=117%3A2653)

#### Changes
- Added ability to store user progress when signed in (the user's completed lessons have a checkmark next to it in the Table of Contents page).
- Must finish quiz to "complete" a lesson.
- Added ability to retake quiz.
- Changed links to lessons to standard blue color when not visited, and standard purple color when visited (matching HTML link behavior).

### UT Testing
[Participant link to survey](https://forms.gle/4chXd5oDrXBnaATR6)

[Collaborator Link to survey](https://docs.google.com/forms/d/14V49gmvPEK9X0c57B8RyRUY48ZumZoOWZBBt6ghBLmk/edit?usp=sharing)

[Link to UT testing YouTube video with screen recording](https://youtu.be/eqiJ-iYZjSw)

#### Summary

### Iteration 3 (Final)
#### Combined
![Iteration3](./Iteration3.png)

[Figma File](https://www.figma.com/file/ydwJChLGVRTIUWu33gTjJt/Final-Assignment-7?node-id=117%3A2652)

[Figma Prototype](https://www.figma.com/proto/ydwJChLGVRTIUWu33gTjJt/Final-Assignment-7?node-id=117%3A2653&scaling=scale-down&page-id=117%3A2652&starting-point-node-id=117%3A2653)

#### Changes

#### Progress
![Iteration3Progress](./Iteration3Progress.png)

[Figma File](https://www.figma.com/file/ydwJChLGVRTIUWu33gTjJt/Final-Assignment-7?node-id=313%3A3)

[Figma Prototype](https://www.figma.com/proto/ydwJChLGVRTIUWu33gTjJt/Final-Assignment-7?node-id=313%3A4&scaling=scale-down&page-id=313%3A3&starting-point-node-id=313%3A4)

Since Figma does not save state, it's difficult to include the completed lessons within my main flow. This is because I have included 3 lessons in my prototype, and the user can access these lessons in any order. Therefore, I've included a separate linear flow for just the displaying completed lessons (the lessons are in order so I don't have to do so much connections between prototypes to account for the many permutations of visiting the 3 lessons in whatever order).

Likewise, I am unable to include both "mouse enter" (for the mini table of contents overlay) and "on tap" (redirect back to the Table of Contents page) interactions on a single component on Figma, so it just defaults as "mouse enter" and displays the overlay table of contents. In practice, the user would be greeted with a mini table of contents overlay (as seen in the prototype) when the mouse enters the table of contents button in the NavBar. At the same time, the user would be able to click the table of contents button in the NavBar to be taken to the Table of Contents page. On mobile, the table of contents button would just take the user to the Table of Contents page upon clicking/tapping on it. There would be no overlay option for mobile.

#### Changes
- Added sign in/sign up popup to "Sign up to unlock more content" in the Table of Contents page.
- Spilt prototype into 2 flows/tasks - one for normal navigation through the website, and one to display how the website deals with user progress.
