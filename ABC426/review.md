# [ABC426] 振り返り

## 💡 全体的な感想・反省
*ロジックはできているが、簡潔に書けない

---

## 📝 問題別振り返り

### A問題: [OS Versions](https://atcoder.jp/contests/abc426/tasks/abc426_a)
* **結果**: AC
* **かかった時間**: 10分
* **思考プロセス**:
    * (例: 単純な四則演算だったので、int型で受け取って出力した。)
* **学び・気づき**:
  *これもmapを使えばもっと簡単に表せた
  
### B問題: [The Odd One Out](https://atcoder.jp/contests/abc426/tasks/abc426_b)
* **結果**:  CE 
* **かかった時間**: 15分
* **詰まったポイント**:
    * setからの値の取り出し方が分からなかった
* **解説を読んで**:
    * mapを上手く使えるともっと良い

---

## 🛠 新しく学んだ文法・アルゴリズム
* setから取り出すときは*set.begin()や*next(set.begin())を使う
*// ★ここがポイント！
  // set の中身を全部 vector にコピーしちゃう
  vector<char> vec;
  for(char c : st){
    vec.push_back(c);
  }
としてしまうのが吉


## 🚀 次へのアクション
* (例: B問題の典型パターンをAtCoder Problemsで5問解く。)
* (例: 配列のサイズ確保の書き方を指に覚えさせる。)
'''
