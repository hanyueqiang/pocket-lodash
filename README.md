# pocket-lodash

> 能做事的做事，能发声的发声。有一分热，发一分光，就令萤火一般，也可以在黑暗里发一点光，不必等候炬火。
>
> ​																					——鲁迅

很喜欢鲁迅的这段话，在很多社区也会引用作为签名。鲁迅这段话有反抗的意味，用于单纯的技术分享似乎不太合适，可是管它呢。

前一段时间，从 `Zepto` 开始，初尝了阅读源码，以前觉得很难，现在有点上了瘾，这次阅读的是 `lodash` ，平时也会用到这个库，希望可以借此对它有更深入的了解。

这系列的每篇文章应该不会很长，依 `lodash` 的组织，每个文件都会有一篇对应的文章，因此命名为 `pocket-lodash`。

## 源码版本

[lodash v4.17.4](https://github.com/lodash/lodash)

## GitBook

《[pocket-lodash](https://www.gitbook.com/book/yeyuqiudeng/pocket-lodash/details)》

## 目录

* [internal]()
  * [Hash](internal/Hash.md)
  * [assocIndexOf](internal/assocIndexOf.md)
  * [ListCache](internal/ListCache.md)
  * [MapCache](internal/MapCache.md)
  * [SetCache](internal/SetCache.md)
  * [baseFindIndex](internal/baseFindIndex.md)
  * [baseIsNaN](eq.md)
  * [strictIndexOf](internal/strictIndexOf.md)
  * [baseIndexOf](internal/baseIndexOf.md)
  * [arrayIncludes](internal/arrayIncludes.md)
  * [arrayIncludesWith](internal/arrayIncludesWith.md)
  * [cacheHas](internal/cacheHas.md)
  * [baseDifference](internal/baseDifference.md)
  * [baseGetTag](internal/baseGetTag.md)
  * [getTag](internal/getTag.md)
  * [isFlattenable](internal/isFlattenable.md)
  * [baseFlatten](internal/baseFlatten.md)
  * [baseWhile](internal/baseWhile.md)
  * [baseIntersection](internal/baseIntersection.md)
  * [castArrayLikeObject](internal/castArrayLikeObject.md)
  * [strictLastIndexOf](internal/strictLastIndexOf.md)
  * [isIndex](internal/isIndex.md)
  * [baseIndexOfWith](internal/baseIndexOfWith.md)
  * [copyArray](internal/copyArray.md)
  * [basePullAll](internal/basePullAll.md)
  * [isKey](internal/isKey.md)
  * [memoizeCapped](internal/memoizeCapped.md)
  * [stringToPath](internal/stringToPath.md)
  * [castPath](internal/castPath.md)
  * [toKey](internal/toKey.md)
  * [baseGet](internal/baseGet.md)
  * [baseAt](internal/baseAt.md)
  * [parent](internal/parent.md)
  * [baseUnset](internal/baseUnset.md)
  * [basePullAt](internal/basePullAt.md)
  * [compareAscending](internal/compareAscending.md)
  * [baseSortedIndexBy](internal/baseSortedIndexBy.md)
  * [baseSortedIndex](internal/baseSortedIndex.md)
  * [baseSortedUniq](internal/baseSortedUniq.md)
  * [setToArray](internal/setToArray.md)
  * [createSet](internal/createSet.md)
  * [baseUniq](internal/baseUniq.md)
  * [baseProperty](internal/baseProperty.md)


* [slice](slice.md)
* [chunk](chunk.md)
* [compact](compact.md)
* [eq](eq.md)
* [map](map.md)
* [isObjectLike](isObjectLike.md)
* [isArguments](isArguments.md)
* [isLength](isLength.md)
* [isArrayLike](isArrayLike.md)
* [isArrayLikeObject](isArrayLikeObject.md)
* [difference](difference.md)
* [last](last.md)
* [differenceBy](differenceBy.md)
* [differenceWith](differenceWith.md)
* [drop](drop.md)
* [dropRight](dropRight.md)
* [dropRightWhile](dropRightWhile.md)
* [dropWhile](dropWhile.md)
* [findLastIndex](findLastIndex.md)
* [head](head.md)
* [flatten](flatten.md)
* [flattenDeep](flattenDeep.md)
* [flattenDepth](flattenDepth.md)
* [fromPairs](fromPairs.md)
* [indexOf](indexOf.md)
* [initial](initial.md)
* [intersection](intersection.md)
* [intersectionBy](intersectionBy.md)
* [intersectionWith](intersectionWith.md)
* [isObject](isObject.md)
* [isSymbol](isSymbol.md)
* [toNumber](toNumber.md)
* [toFinite](toFinite.md)
* [toInteger](toInteger.md)
* [lastIndexOf](lastIndexOf.md)
* [nth](nth.md)
* [pullAll](pullAll.md)
* [pull](pull.md)
* [pullAllBy](pullAllBy.md)
* [pullAllWith](pullAllWith.md)
* [memoize](memoize.md)
* [get](get.md)
* [pullAt](pullAt.md)
* [remove](remove.md)
* [sortedIndex](sortedIndex.md)
* [sortedIndexBy](sortedIndexBy.md)
* [sortedIndexOf](sortedIndexOf.md)
* [sortedLastIndex](sortedLastIndex.md)
* [sortedLastIndexBy](sortedLastIndexBy.md)
* [sortedLastIndexOf](sortedLastIndexOf.md)
* [sortedUniq](sortedUniq.md)
* [sortedUniqBy](sortedUniqBy.md)
* [tail](tail.md)
* [take](take.md)
* [takeRight](takeRight.md)
* [takeRightWhile](takeRightWhile.md)
* [takeWhile](takeWhile.md)
* [union](union.md)
* [unionBy](unionBy.md)
* [unionWith](unionWith.md)
* [uniq](uniq.md)
* [uniqBy](uniqBy.md)
* [uniqWith](uniqWith.md)
* [filter](filter.md)
* [zip](zip.md)
* [unzipWith](unzipWith.md)

## License

[署名-非商业性使用-禁止演绎 4.0 国际 (CC BY-NC-ND 4.0)](http://creativecommons.org/licenses/by-nc-nd/4.0/)

所有文章都会同步发送到微信公众号上，欢迎关注,欢迎提意见：

  ![](https://raw.githubusercontent.com/yeyuqiudeng/resource/master/images/qrcode_front-end-article.jpg) 