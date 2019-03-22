@snap[north-west text-gray span-100]
@size[1.5em](This is Header)
@snapend

```scala
trait Adder[T] {
  val add: (T, T) => T
}
```

Traits declare module specs, therefore they also can be documents.
 
@snap[south-west template-note text-gray]
Trait の定義はモジュールの仕様を宣言しているので、ドキュメントとみなすこともできるはずです。
@snapend
