# React.js 小書
[![License: CC BY-ND 4.0](https://img.shields.io/badge/License-CC%20BY--ND%204.0-blue.svg)](https://creativecommons.org/licenses/by-nd/4.0/legalcode)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

線上閱讀：[http://huziketang.com/books/react/](http://huziketang.com/books/react/)

## 簡介
這是一本關於 React.js 的小書。

因為工作中一直在使用 React.js，也一直以來想總結一下自己關於 React.js 的一些知識、經驗。於是把一些想法慢慢整理書寫下來，做成一本開源、免費、專業、簡單的入門級別的小書，提供給社羣。希望能夠幫助到更多 React.js 剛入門朋友。

由於水平有限，編寫的過程難免會有諸多錯誤，也希望大家在看的過程中發現了問題，可以在 Github 上給該項目發 Pull Request。衷心希望可以有更多的人蔘與到本書的編寫當中。

（本書的後續可能會做成視訊版本，敬請期待。）

## 本書介紹

本書為有一點前端基礎的並且是 React.js 零基礎的同學而作，幫助他們掌握 React.js 並且靈活地把 React.js 應用到實際項目當中。如果你有一定的 HTML、CSS、JavaScript 基礎並且希望學習 React.js，而又覺得 React.js 當中有些概念比難以接受和理解，希望能夠從零開始學習，那麼本書很適合你。但如果你已經對前端已經非常熟悉並且用過不少的前端框架和相關的元件化技術，建議你直接看官網文件。

本書並不會文件式地包含所有知識點，只會提煉實戰經驗中基礎的、重要的、頻繁的知識進行重點講解，讓你能用最少的精力深入瞭解實戰中最需要的 React.js 知識和套路，輕裝上路。如果需要更多更全面的知識點，可以參看更多的官方文件或者其他豐富的資料。

**另外，本書全書採用 ECMAScript 2015，閱讀之前請確保自己已經掌握了 ECMAScript 2015 的基本語法，否則閱讀起來會非常困難。**

本書初定分為三個階段，每個階段最後會有實戰分析，把該階段的知識點應用起來。

**第一個階段**：希望能讓讀者掌握 React.js 的基本概念和基礎知識。包括問題的根源：前端元件的複用性問題、資料和檢視的同步問題。瞭解清楚問題以後再瞭解 React.js 的基礎知識，包括 JSX、事件監聽、state、props、列表渲染等。看看 React.js 是怎麼解決這些問題的。這個階段結束以後，讀者就可以可以運用 React.js 構建簡單的頁面功能。

**第二個階段**：讓讀者更進一步瞭解 React.js，包括元件生命週期及其含義、state 和 props 的進階概念、props 驗證及其意義、元件組合進階、如何和 DOM 打交道、並且開始引入前端應用狀態管理所存在的問題。

**第三個階段**：讓讀者掌握 React.js 較為高階的概念，包括高階元件、context。並且嘗試引入 React-redux 來協助我們構建較為完整的前端應用，還會開始深入討論前端應用狀態管理的問題；關於 React-router 也會有所提及。

## 目錄

**第一個階段**

![](https://img.shields.io/badge/已完成-100%25-brightgreen.svg)

* Lesson 1 - [React.js 簡介](http://huziketang.com/books/react/lesson1)
* Lesson 2 - [前端元件化（一）：從一個簡單的例子講起](http://huziketang.com/books/react/lesson2)
* Lesson 3 - [前端元件化（二）：優化 DOM 操作](http://huziketang.com/books/react/lesson3)
* Lesson 4 - [前端元件化（三）：抽象出公共元件類](http://huziketang.com/books/react/lesson4)
* Lesson 5 - [React.js 基本環境安裝](http://huziketang.com/books/react/lesson5)
* Lesson 6 - [使用 JSX 描述 UI 資訊](http://huziketang.com/books/react/lesson6)
* Lesson 7 - [元件的 render 方法](http://huziketang.com/books/react/lesson7)
* Lesson 8 - [元件的組合、巢狀和元件樹](http://huziketang.com/books/react/lesson8)
* Lesson 9 - [事件監聽](http://huziketang.com/books/react/lesson9)
* Lesson 10 - [元件的 state 和 setState](http://huziketang.com/books/react/lesson10)
* Lesson 11 - [配置元件的 props](http://huziketang.com/books/react/lesson11)
* Lesson 12 - [state vs props](http://huziketang.com/books/react/lesson12)
* Lesson 13 - [渲染列表資料](http://huziketang.com/books/react/lesson13)
* Lesson 14 - [實戰分析：評論功能（一）](http://huziketang.com/books/react/lesson14)
* Lesson 15 - [實戰分析：評論功能（二）](http://huziketang.com/books/react/lesson15)
* Lesson 16 - [實戰分析：評論功能（三）](http://huziketang.com/books/react/lesson16)

**第二個階段**

![](https://img.shields.io/badge/已完成-100%25-brightgreen.svg)

* Lesson 17 - [前端應用狀態管理 —— 狀態提升](http://huziketang.com/books/react/lesson17)
* Lesson 18 - [掛載階段的元件生命週期（一）](http://huziketang.com/books/react/lesson18)
* Lesson 19 - [掛載階段的元件生命週期（二）](http://huziketang.com/books/react/lesson19)
* Lesson 20 - [更新階段的元件生命週期](http://huziketang.com/books/react/lesson20)
* Lesson 21 - [ref 和 React.js 中的 DOM 操作](http://huziketang.com/books/react/lesson21)
* Lesson 22 - [props.children 和容器類元件](http://huziketang.com/books/react/lesson22)
* Lesson 23 - [dangerouslySetHTML 和 style 屬性](http://huziketang.com/books/react/lesson23)
* Lesson 24 - [PropTypes 和元件參數驗證](http://huziketang.com/books/react/lesson24)
* Lesson 25 - [實戰分析：評論功能（四）](http://huziketang.com/books/react/lesson25)
* Lesson 26 - [實戰分析：評論功能（五）](http://huziketang.com/books/react/lesson26)
* Lesson 27 - [實戰分析：評論功能（六）](http://huziketang.com/books/react/lesson27)

**第三個階段**

![](https://img.shields.io/badge/已完成-90%25-brightgreen.svg)

* Lesson 28 - [高階元件（Higher-Order Components）](http://huziketang.com/books/react/lesson28)
* Lesson 29 - [React.js 的 context](http://huziketang.com/books/react/lesson29)
* Lesson 30 - [動手實現 Redux（一）：優雅地修改共享狀態](http://huziketang.com/books/react/lesson30)
* Lesson 31 - [動手實現 Redux（二）：抽離 store 和監控資料變化](http://huziketang.com/books/react/lesson31)
* Lesson 32 - [動手實現 Redux（三）：純函數（Pure Function）簡介](http://huziketang.com/books/react/lesson32)
* Lesson 33 - [動手實現 Redux（四）：共享結構的物件提高效能](http://huziketang.com/books/react/lesson33)
* Lesson 34 - [動手實現 Redux（五）：不要問為什麼的 reducer](http://huziketang.com/books/react/lesson34)
* Lesson 35 - [動手實現 Redux（六）：Redux 總結](http://huziketang.com/books/react/lesson35)
* Lesson 36 - [動手實現 React-redux（一）：初始化工程](http://huziketang.com/books/react/lesson36)
* Lesson 37 - [動手實現 React-redux（二）：結合 context 和 store](http://huziketang.com/books/react/lesson37)
* Lesson 38 - [動手實現 React-redux（三）：connect 和 mapStateToProps](http://huziketang.com/books/react/lesson38)
* Lesson 39 - [動手實現 React-redux（四）：mapDispatchToProps](http://huziketang.com/books/react/lesson39)
* Lesson 40 - [動手實現 React-redux（五）：Provider](http://huziketang.com/books/react/lesson40)
* Lesson 41 - [動手實現 React-redux（六）：React-redux 總結](http://huziketang.com/books/react/lesson41)
* Lesson 42 - [使用真正的 Redux 和 React-redux](http://huziketang.com/books/react/lesson42)
* Lesson 43 - [Smart 元件 vs Dumb 元件](http://huziketang.com/books/react/lesson43)
* Lesson 44 - [實戰分析：評論功能（七）](http://huziketang.com/books/react/lesson44)
* Lesson 45 - [實戰分析：評論功能（八）](http://huziketang.com/books/react/lesson45)
* Lesson 46 - [實戰分析：評論功能（九）](http://huziketang.com/books/react/lesson46)
* ...

## 特別鳴謝

特別感謝以下朋友對本書所做的審校工作，給本書提出了很多寶貴的改進意見：

* [鄺偉科](https://github.com/kuangwk/) - 騰訊 Web 前端工程師
* [楊海波](https://github.com/hipoyang/) - 百度 Web 高階前端工程師
* [謝軍令](https://github.com/brucexiejunling/) - 天貓 Web 前端工程師
* [戴嘉華](https://github.com/livoras/) - 前微信 Web 前端工程師

## 聯絡作者

* 郵箱：huzidaha@126.com
* 知乎：[@鬍子大哈](https://www.zhihu.com/people/hu-zi-da-ha)
* 專欄：[@前端大哈](https://zhuanlan.zhihu.com/qianduandaha)
* 加入《React.js 小書》讀者交流群，一起討論、交流、學習前端技術。

<img width='256px' src='http://huzidaha.github.io/static/assets/img/wechat-user.jpeg' />


## License

本作品採用 [署名-禁止演繹 4.0 國際許可協議](https://creativecommons.org/licenses/by-nd/4.0/legalcode) 進行許可
