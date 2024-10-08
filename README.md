# nandgame-translate-ja
https://nandgame.com/translate/ja

## Some notes

- Some words are intentionally altered from the original text. Some notable examples are:
  - I translate "level" as "ステージ" (stage) because "レベル" (level) is more commonly used for "difficulty level" in Japanese.
    - 『日本ではゲームにおける「ステージ」の意味では馴染みがないが、海外では「レベル」(level) という表現も広く使われており』 https://ja.wikipedia.org/wiki/%E3%82%B9%E3%83%86%E3%83%BC%E3%82%B8_(%E3%82%B3%E3%83%B3%E3%83%94%E3%83%A5%E3%83%BC%E3%82%BF%E3%82%B2%E3%83%BC%E3%83%A0)
    - 『NandGameではステージをレベル（Level）と表現しています。』 https://akademeia.info/?page_id=33404
  - "create a connection" is translated as 配線を繋げる (lit. "connect the wire") because "接続を作成" (lit. "create a connection") sounds too awkward.
  - The explanation of "counter" is augmented with a link to Wikipedia, since its translation 「カウンター」 is ambiguous in Japanese and might be misinterpreted as a "counter table" in a store or a "counterattack" in games.

- Some explanations are completely rephrased for better understanding.
  - For instance, `<p>The two bit-flags <b>op0</b> and <b>op1</b> select which out of four operations are performed on the two 16-bit inputs <b>X</b> and <b>Y</b>.</p>` is rephrased as `<p>以下の4つの操作のうちのどれを適用するかを、2つのビットフラグ<b>op0</b>と<b>op1</b>で選択します。操作を行う対象として、16ビット入力<b>X</b>と<b>Y</b>も受け取ります。</p>`

- I replaced all the `<i>`s with `<u>`s because some Japanese fonts don't have italics at all and render it indistinguishable from regular texts.
