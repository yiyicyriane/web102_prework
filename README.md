# WEB102 Prework - _Sea Monster Crowdfunding_

Submitted by: **Yiyi Wang**

**Sea Monster Crowdfunding** is a website for the company Sea Monster Crowdfunding that displays information about the games they have funded.

Time spent: **5** hours spent in total

## Required Features

The following **required** functionality is completed:

- [x] The introduction section explains the background of the company and how many games remain unfunded.
- [x] The Stats section includes information about the total contributions and dollars raised as well as the top two most funded games.
- [x] The Our Games section initially displays all games funded by Sea Monster Crowdfunding
- [x] The Our Games section has three buttons that allow the user to display only unfunded games, only funded games, or all games.

## Video Walkthrough

Here's a walkthrough of implemented features:

![Walkthrough](assets/walkthrough.mp4)

## Notes

While building this app, I encountered and solved several practical issues:

- Variable redeclaration:
  I fixed errors caused by declaring the same const variable multiple times in the same scope.

- Plural/singular grammar:
  I used ternary operators in template literals to display correct grammar based on the number of games.

- Array methods for filtering and sorting:
  I practiced using filter, reduce, sort, and destructuring to process and display the correct data.

- DOM updates:
  I made sure to clear previous content before rendering new lists to prevent duplicate entries.

These challenges improved my JavaScript, debugging, and web development skills.

## License

    Copyright [2025] [YIYI WANG]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
