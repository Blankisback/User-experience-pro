# Designing for the User Experience-UNI

Created by:
- Tom
- Brandon
- Mikolaj


This project covers differences between netflix and amazon prime video streaming services


## **Buisness neeeds and Website Development**
(10 Marks)


Both of these companies use their websites as streaming services, these sites where developed to effectivly share content with subscribers and to try and keep them engaged for as much as possible. They acchieved this by showing a variety of options catagroised into different sections; top ten lists, thrillers, action movies, easy watching etc and using captivating screenshots to try to sell each show of film to the user.

Starting with Amazon Prime video
Amazon does a lot of their design fairly well nothing is overly clutterd, there is decent spacing between all the titles. The worst part of it is they are reliant on the thumbnails of each of the show or film for the name, this could cause issues for people with visual impairment as some have low contrast or are overly stialised. One solution for this could be a mode where the title of the program is displayed bellow it. While doing this we could also accomidate certain lerning disabilitys such as dyslexia with a more friendly font and or a higher contrast background.

<img width="1737" height="1014" alt="slice1" src="https://github.com/user-attachments/assets/4471e1fa-fc5f-417c-ba32-23cc32a167a7" />

<img width="1867" height="991" alt="slice2" src="https://github.com/user-attachments/assets/cf6f8843-42fa-4597-8d63-9df270661c6c" />

Netflix also suffers from this issue where all film and tv titles are reliant on the product thumbnail even on its click through menu where it has enough space to cleanly layout the title of the show they instead just go for a darkend preview with the ttitle on top creating some contrast but certain senarios that could still be hard to read.

<img width="3133" height="972" alt="slice3" src="https://github.com/user-attachments/assets/c6f2182f-c776-49fd-b19b-ece9c9e890f4" />

<img width="1253" height="1047" alt="slice4" src="https://github.com/user-attachments/assets/b988c895-e002-4d8a-afd8-64e2a7a6381b" />

This could all be fixed with a simple setting in the menu or just by having the click through show the title as normal text in the menu along with the larger styalised version.  Using these insights and guidence from (Lys Forstner, 2023) aswell as (W3C, 2025) we can make a more accessible and user friendly interface for our users.

With regards to how the website will be used (Falkowski-Gilski and Uhl, 2020) gives a in depth survery of 16-25 year olds how they consume content covering, what services do they pay for, what devices do they watch on, even down to their internet speed and prefered audio quailities. We will be taking into account most of this paper for our framework.


## **User Analysis**
(25 Marks)

### Profile One:

Eighteen Years Old, First Time User.

Traits; Budget Conscious, Visual Imparement, Prefers Darker Backgrounds.

Accessibility/Requirments: High Contrast easy to Read titles.

User Story: As a young individual, I am very concerned over budget. I want clear pricing easy term lengths and a straight forward cancelation process.

Testing Criterea: Given this user is visualy impared, forming a focus group to test what is more visible to a range of different people and selecting the three best options to implement for users to select what works best for them.


### Profile Two:

Fifty Six Years Old, Returning User.

Traits: Hearing Difficulties, Only watches an episode or two/month of a long series/show.

Accessibility/Requirements: Subtitles on Media potentially add an equalizer so they can adjust audio balance. Long term memory of what shows they have watched, maybe an ai recap blurb.

User Story: With my hearing difficulties I want subtitles to be easily accessible, customisable, and persistant between shows. They should also be word for word to what is said in the media.

Testing Critera: With the hearing difficulties from this user having subtitles that can be either manually selected to always be in the same place or automaticaly adjusted based on the contents of the media. The user should also be able to adjust the text and a background colour with opacity slider to fine tune them to their liking.


### Profile Three:

Thirty Years Old, Frequent User.

Traits: Reguarly binges entire shows, main complaint is falling asleep and missing content. 

Accesibility/Requirements: A sleep timer/Auto pause after inactivity for X, Ability to quickly and effortless reset progress on watched shows at will.  - will double check this but i think this is a function on netflix already (the are you still watching after inactivity between episodes)

User Story: As a late night viewer, I tend to fall asleep during shows as such a feature which detects in-activity would be nice to help minimise the loss. This feature should be able to be dissabled though for when I am purposfully binging a show. An auto play feature would also be nice continuing on a movie with the next in the order if it is part of a larger serise or with something similiar if it is standalone.

Testing Critera: As this user tends to sleep through media a simple popup menu that automaticaly pauses the media in the background, asking if they want to continue, continue uninterupted or exit. - could be done thorugh a simple are you there yes/no and if no response within 5 minutes the device goes into rest mode

## Demo Framework
(40 Marks)

<img width="1366" height="719" alt="image" src="https://github.com/user-attachments/assets/79ec5609-3d92-455b-b9c1-7150d3eac115" />

This framework is a mix of ideas from Netflix and Amazon Prime, it makes use of the Z pattern which the human eye follows which is why I have placed the title for the site in the top left, this site also follows the rule of thirds as i have seperated the site into parts for, reccomendations, continue watchimg and genres.

<img width="1366" height="719" alt="image" src="https://github.com/user-attachments/assets/0adc9c42-922a-4597-9890-19b4497b18ae" />

For users who already know what movie they want to watch, there is an implemented search button which allows you to filter movies by name:

<img width="1366" height="719" alt="image" src="https://github.com/user-attachments/assets/97ed25f1-b79b-410c-9498-32ad16994b5a" />

### Refferences 

Falkowski-Gilski, P. and Uhl, T. (2020). Current trends in consumption of multimedia content using online streaming platforms: A user-centric survey. [online] Science Direct. Available at: https://www.sciencedirect.com/science/article/abs/pii/S1574013719302473?via%3Dihub [Accessed 30 Jan. 2026].

Lys Forstner, S. (2023). Designing a Dyslexia-Friendly Interaction with News Articles. [online] Sikt.no. Available at: https://nva.sikt.no/registration/0198f2238335-0613e77c-285b-4fa1-bf80-18cee64fa1ca [Accessed 23 Jan. 2026].

W3C (2025). Web Content Accessibility Guidelines (WCAG) 2.1. W3.org. Available at: https://www.w3.org/TR/WCAG21/ [Accessed 23 Jan. 2026].
