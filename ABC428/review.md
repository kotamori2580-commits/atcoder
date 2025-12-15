# [ABCX428] 振り返り

## 💡 全体的な感想・反省
* Bは何度も間違った。骨のある問題だった。

---

## 📝 問題別振り返り

### A問題: [Grandma's Footsteps](https://atcoder.jp/contests/abc428/tasks/abc428_a)
* **結果**: CE
* **かかった時間**: 10分
* **思考プロセス**:
    * ダイヤグラムを書いて考えた
* **学び・気づき**:
* 
    * ### B問題: [Most Frequent Substrings](https://atcoder.jp/contests/abc428/tasks/abc428_b)
* **結果**: CE
* **かかった時間**: 60分
* **詰まったポイント**:
    * ループの回数が多くて複雑化してしまった。
* **解説を読んで**:
    * 自分の解法(全探索)でも合っていたが、もっと簡単な書き方(map関数)があった。
    * // 2. 出現回数の最大値を探すうまいやり方
  int max_count = 0;
  for(auto p : count_map){
    // p.first が文字列、p.second が回数
    max_count = max(max_count, p.second);
  }

  //max_countに最大値を格納しておき、それとp.secondの大小を比べるようにする

---

## 🛠 新しく学んだ文法・アルゴリズム
* substr(i, K) で文字列をしていする
* setにはpush_backではなくinsertを使う
* setは順番がないので、取り出せない

## 🚀 次へのアクション
* (例: B問題の典型パターンをAtCoder Problemsで5問解く。)
* (例: 配列のサイズ確保の書き方を指に覚えさせる。)
'''
