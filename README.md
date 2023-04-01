# Parrot Number - Flutter Guess Number Game

Parrot Number is a simple guessing game built using Flutter. The game involves guessing a number between 1 and 100, with the help of hints given by a parrot.

## Getting Started

To get started with Parrot Number, clone the repository to your local machine using the following command:

```shell
git clone git@github.com:NEO-TAT/parrot_number_starter.git
```

## Installation

To install the required dependencies, run the following command:

```shell
flutter pub get
```

## Running the App

To run the app on your local machine, run the following command:

```shell
flutter run
```

## Description
這是一個猜數字遊戲的初始模板，你可以在此基礎上開發出自己的猜數字遊戲，但要符合以下限制：
猜數字過程如下：App 會在遊戲開始時先從 n (1 <= n <= 100) 之中隨意選取一個數字當作答案, 然後玩家會透過畫面上的某個輸入框框來數入猜的數字。每當玩家送出一次猜測時，畫面就會告訴玩家你猜的數字是大於還是小於正確答案。如果玩家猜到正確答案，畫面就會跳轉到遊戲結束恭喜過關頁面，並顯示玩家猜的次數與正確答案。

- 頁面1(首頁)：在畫面中央顯示 App Logo, Logo 不限，可自行設計或放一張你喜歡的圖。頁面下半部要有個開始遊戲按鈕。
- 頁面2(猜數字頁面)：要有個輸入匡可以讓玩家輸入數字，和一個送出按鈕。此外，還要有個地方顯示玩家該次猜測的數字是大於還是小於正確答案。在頁面的下半部要有個清單可以列出玩家猜測過的數字歷史紀錄。
- 頁面3(成果頁面)：要顯示恭喜之類的字詞來告訴玩家你終於猜對了。此外，要有個數字顯示正確答案，以及玩家總共的猜測次數。

以上敘述為大方向限制，實際上的實作細節各位可以自行發揮，例如：頁面佈局可以依個人喜好調整，或是增加一些題目沒講到的內容都可以唷～

進階要求：以下幾點為較為進階的題目要求，如果有興趣的話也可以試試看：
1. 線上計分板功能：玩家的遊玩成績(猜了幾次、時間等)資訊可以上傳到 firebase, 並讓所有玩家在 App 中的某處欣賞，尤其是在成果頁面，可以比較自己的排名
2. 遊戲進度儲存：玩到一半的時候關掉 App 再打開，可以從上次猜的位置繼續猜

上述所有項目均不限制使用之技術，僅要求使用 flutter / Dart 進行開發。(狀態管理、依賴注入、動畫、框架、MethodChannel Call、演算法資料結構、ci/cd、AI ML、AR VR ...)

## Some Links
- Dart language tour: https://dart.dev/guides/language/
- Dart codelab: https://dart.dev/codelabs
- Write a better Dart code: https://dart.dev/guides/language/effective-dart
- Flutter starter codelab: https://flutter.dev/docs/get-started/codelab
- Flutter tutorial: https://docs.flutter.dev/reference/tutorials
- Git tutorial: https://gitbook.tw/
- Git tutorial-2: https://github.com/twtrubiks/Git-Tutorials
- Git tutorial-3: https://github.com/eficode-academy/git-katas
- Git branch exercise: https://learngitbranching.js.org/?locale=zh_TW

## License

Parrot Number is open source software licensed under the [MIT license](https://opensource.org/licenses/MIT).
