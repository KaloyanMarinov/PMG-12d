# CSS Селектори

## 1 Прости селектори

Селектират елементи въз основа на таг име, id или class.

```css
p { /* Tag selector */
  property: value;
}

.myClass { /* Class selector */
  property: value;
}

.myClass2 {
  property: value;
}

#myClass { /* ID selector */
  property: value;
}
```

## 2 Кобинаторни селектори

Селектират елементи прости селектори възнова на връзки между тях

Видове връзки: 

- descendant selector (space)
- child selector (>)
- adjacent sibling selector (+)
- general sibling selector (~)

## 3 Псевдо селектори

Избират елементи въз основа на определено състояние

```css
selector:pseudo-class {
  property: value;
}

a:hover {
  color: red;
}
```

## 4 Псевдо-елементни селектори

Селектират част от стила на даден елемент

```css
selector:pseudo-element {
  property: value;
}

p:first-line {
  color: red;
}
```

## 5 Атрибутни селектори

Селектират елементи въз основа на атрибут или стойност на атрибут

```css
[attribute="value"] {
  property: value;
}

a[target] {
  background-color: yellow;
}

a[target="_blank"] {
  background-color: yellow;
}
```