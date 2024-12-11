# 卒業研究
## To Do
- [ ] 連結式以外の実装方式の実装
  - ヒープにスタックの継続をコピー保存し、戻すときはアドレスが一致する位置に戻す(プロンプトの位置を覚えておけばできそう？)。呼び出す際はスタックを破壊してしまう可能性があるので、スタックの内容をいったん退避させてから、ヒープからスタックにコピーし、継続の処理がすべて終了したら退避させた処理を戻す。結果マルチショットになるが、それは問題ない。
- [ ] System timeがどのパラメータに依存しているかを調査。
      - テーブルが関係している？
- [ ] ToDo案と目次案を考える