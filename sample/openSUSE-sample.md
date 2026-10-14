---
marp: true
theme: openSUSE
paginate: true
footer: openSUSE Theme Sample
---

<!-- _class: lead -->

# openSUSE Theme
## サンプルスライド

Have a lot of fun!

---

# 見出しとテキスト

本文には **強調**、*斜体*、~~取り消し~~、<mark>マーカー</mark>、[リンク](https://www.opensuse.org/)、<kbd>Ctrl</kbd> + <kbd>C</kbd> が使えます。

- 箇条書き
  - ネスト
- `zypper refresh` のようなインラインコード

1. 番号付き
2. リスト

---

## コードブロック

```bash
# パッケージの更新
sudo zypper refresh && sudo zypper dup -y
echo "Hello, $USER"
```

```python
def greet(name: str) -> str:
    """Return greeting"""
    return f"Hello, {name}!"  # comment
print(greet("Geeko"), 42, True)
```

---

### 表と引用

| ディストリ | リリース | 備考 |
| --- | --- | --- |
| Tumbleweed | ローリング | 最新 |
| Leap | 固定 | 安定 |
| MicroOS | ローリング | イミュータブル |

> openSUSE は世界中のコミュニティによって支えられています。

---

<!-- _class: section -->

# 第2章
## セクション区切り

---

<!-- _class: invert -->

# ライトバリアント

本文と `inline code`

```js
const distro = "openSUSE";
console.log(`Hello ${distro}`);
```
