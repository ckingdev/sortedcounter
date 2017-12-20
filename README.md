# sortedcounter

A Counter like the collections class but with sorted keys (thanks to
 [sortedcontainers](https://pypi.python.org/pypi/sortedcontainers))

Currently, the only changes to functionality are the replacement of the superclass from dict to sortedcontainer.SortedContainer.
Any other changes are cosmetic. I expect that that will remain the case, but I will be adding type/variable annotations
where relevant and updating the documentation. At the moment, it is the same as the collections.Counter docs.

This should be a drop-in replacement for a Counter where you need a sorted collection, but as always you should test that first.

Since this subclasses SortedDict, there will be other methods defined than on a dict or a Counter. See the documentation for [sortedcontainers](http://www.grantjenks.com/docs/sortedcontainers/) for more.

