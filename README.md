# Bulls and Cows

:rocket: Technology：Blazor WebAssembly

:fire: 2022/9/21 瀏覽網站時看到的經典小遊戲，查了一下發現 1A2B 猜數字遊戲的英文名為 Bulls and Cows，而 Bull 等同於 A、Cow 等同於 B 的意思

## About
[Bulls and Cows](https://en.wikipedia.org/wiki/Bulls_and_Cows) (also known as Cows and Bulls or Pigs and Bulls) is a code-breaking mind or paper and pencil game for two or more players, predating the commercially marketed board game Mastermind and the hit word game Wordle.

The game is played in turns by two opponents who aim to decipher the other's secret code by trial and error.

## How to play
原遊戲方法：
由兩人各自寫下一組四位數字，且每個數字不重複，輪流猜對方的數字是多少，若對方猜測的數字內，有數字相同且位置也相同的稱為 bull，若有猜到數字但位置不對的稱為 cow
假設寫下 2803，對方猜 1834，寫的人必須說 one bull one cow，因為 8 的數字對，位置也對，這樣就是一個 bull，而 3 數字對了，位置不對，則為一個 cow

原遊戲目標：找到四個 bull

1A2B 遊戲方法：
1A2B 遊戲方法與上述說明的幾乎一模一樣，只差在 bull 為 A，cow 為 B，符合小時候玩的記憶

1A2B 遊戲目標：找到 4 個 A
