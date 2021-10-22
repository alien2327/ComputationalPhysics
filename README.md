# Computational Physics

## 物理学の研究分野

物理学の研究はその研究方法から、理論物理学・実験物理学・数理物理学・計算物理学と大きく4つの分野に分けられる。理論物理学では、物質の持つ特徴を抽出してモデル化し、結論を演繹的に導き出す。実験物理学では、物質そのものを対象として、観測データを集め、それを理論と照合する。数理物理学では、物理学と数学の境界で、宇宙で起こる現象をより厳密で体系的な数学の理論を用いて考える。

計算物理学は理論物理学と実験物理学の境界にある分野とも言える。物質をモデル化する点は理論物理学と同じであり、計算データを集めそれを理論と照合する点は実験物理学に似ている。計算物理学の役割としては、次のことが考えられる。通常の実験では、試料の不均一性や測定誤差などの影響で、完璧に正しい結果を得ることは不可能であるが、計算物理学は理想的な実験環境を計算機上に作り上げることができる。また、実験室では超高圧や超低温などの環境を作ることには限界があるが、計算機上では極限環境を仮想的に作ることができる。また、理論的推論を進めるときには、必ず計算機で数値的に答えを出すことにより、解析的な答えに対して「当たりをつける」ことができる。

このように、それぞれの分野の定義から、純粋な物理学に属する分野は理論物理学と実験物理学であり、応用物理学に属する分野は推理物理学（物理＋数学）と計算物理学（物理＋情報学）である。アナログ的な実験が種類になっていて、コンピューターの普及ができていなかった昔は、それぞれの研究分野の区分が厳密になっていたが、計算方法が徐々に高度化され、高性能のPCが普及されることにつれて、ディジタル的な考え方が増える近年は、それぞれの分野の区別がはっきりしなくなり、理論物理学でも実験物理学の性質を持つ実験を行ったり、実験物理学で計算物理学の手法を用いたりする。

## 使用する言語

物理の解析やシミュレーションを行うときは、C/C++やFortranを使うのが一般的であるが、ここではPythonをメインに使う。Pythonを使う理由としては、簡潔で学びやすい点、視覚化が容易にできる点（Matplotlib）、Numpy等の行列演算が簡単に出来るライブラリが豊富な点（Numpy, Pandas, Scipyなどなど）がある。また、コンパイル言語を使うほど、大量で厳密な計算は行わない点、プログラミング言語は一つマスターしておけば、例えPythonより難しいといわれるC言語を学習することになってもスムーズに学習できる点等もPythonを使う理由である。また、Numpy等のライブラリを上手く駆使すれば、C言語並みの速さ、厳密さを持つ計算ができる（そもそもNumpy自体がCで書かれている）。

## 目次

1. 微分方程式の数値的解放
2. モンテカルロシミュレーション
3. 統計的処理
