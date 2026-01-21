# Python基礎

## 目次
- [Python基礎](#python基礎)
  - [目次](#目次)
  - [変数とデータ型](#変数とデータ型)
    - [ポイント](#ポイント)
  - [文字列操作](#文字列操作)
  - [演習問題1](#演習問題1)

## 変数とデータ型

Pythonは動的型付け言語です。
```python
# 変数の宣言
name = "John"
age = 30
print(f"My name is {name}, I'm {age} years old.")
```

### ポイント
- 明示的な型宣言は不要
- 実行時に型が決定される

## 文字列操作

文字列連結には`+`演算子を使用します。
```python
greeting = "Hello" + " " + "World"
print(greeting)  # Hello World
```

> **注意**: 文字列と数値を直接連結することはできません。

## 演習問題1

変数 `name` に "John" を代入し、"My name is John." と表示するプログラムを記述せよ。

<details>
<summary>解答を表示</summary>
```python

---

次章: [制御構造](02_control_structures.md)