# ClassicSnakeGame
**Classic Snake Game** is a fun game that allows user to feed their snake food pieces that will appear at random places in the game canvas. This will help the snake grow bigger and bigger in size. If the snake hits itself or the canvas boundary then it will die and then the game will stop.

Time spent: **3** hours spent in total

## Feature of the Game

The following functionality is completed:

- [x] User can press any key on the keyboard to start the game.
- [x]	User will hear background music when the game is running, when the snake eats the food and when it collides with itself or the walls.
 -[x] User score will be updated on scoreboard everytime their snake eats food and grows bigger.
 -[x] User can see the highestscore made by any previous player on the score board.
- [x] Highestscore will be updated if a new record is made by the current player.


## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='https://imgur.com/a/PrGPCrB.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />



## Notes

Describe any challenges encountered while building the game ?

I encountered few challenges while building this game. I divided my game canvas in grid format but after testing my code I realized my snake was not moving properly when the game was running. The snake would not move from one position to another instead it was staying in one place and stretching across the y-axis. I debugged my code and I realized there was an issue in my CSS file. I had forgotten to put the rows divison for my canvas grid. When I added this piece of code "grid-template-rows: repeat(18, 1fr)" then my snake moved perfectly fine. 
Also, I wanted to store the highest score history of the game on my scoreboard and I was not aware how to implement that. It was quite challenging for me but I used online resources to find help and this stack over flow channel helped me a lot(https://stackoverflow.com/questions/26440147/use-local-storage-to-remember-the-high-score-javascript). I got to learn that I have to use local storage to remember the score history. 

## Open-source libraries used

- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android

## License

    Copyright [2022] [Kashaf Mujeeb]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

https://www.youtube.com/watch?v=2ZDnw6ifdSI
