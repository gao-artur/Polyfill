### Extension methods

#### Boolean

 * `Boolean TryFormat(Span<Char>, Int32&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.boolean.tryformat)


#### Byte

 * `Boolean TryFormat(Span<Char>, Int32&, ReadOnlySpan<Char>, IFormatProvider)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.byte.tryformat)


#### Collections.Concurrent.ConcurrentDictionary<TKey,TValue>

 * `TValue GetOrAdd<TKey, TValue, TArg>(TKey, Func<TKey,TArg,TValue>, TArg)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.collections.concurrent.concurrentdictionary-2.getoradd#system-collections-concurrent-concurrentdictionary-2-getoradd-1(-0-system-func((-0-0-1))-0))


#### Dictionary<TKey,TValue>

 * `Boolean Remove<TKey, TValue>(TKey, TValue&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.collections.generic.dictionary-2.remove)


#### HashSet<T>

 * `Boolean TryGetValue<T>(T, T&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.collections.generic.hashset-1.trygetvalue)


#### IDictionary<TKey,TValue>

 * `Collections.ObjectModel.ReadOnlyDictionary<TKey,TValue> AsReadOnly<TKey, TValue>()` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.collections.generic.collectionextensions.asreadonly#system-collections-generic-collectionextensions-asreadonly-2(system-collections-generic-idictionary((-0-1))))


#### IEnumerable<TFirst>

 * `IEnumerable<ValueTuple<TFirst,TSecond,TThird>> Zip<TFirst, TSecond, TThird>(IEnumerable<TSecond>, IEnumerable<TThird>)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.linq.enumerable.zip#system-linq-enumerable-zip-3(system-collections-generic-ienumerable((-0))-system-collections-generic-ienumerable((-1))-system-collections-generic-ienumerable((-2))))
 * `IEnumerable<ValueTuple<TFirst,TSecond>> Zip<TFirst, TSecond>(IEnumerable<TSecond>)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.linq.enumerable.zip#system-linq-enumerable-zip-2(system-collections-generic-ienumerable((-0))-system-collections-generic-ienumerable((-1))))


#### IEnumerable<TSource>

 * `IEnumerable<KeyValuePair<TKey,TAccumulate>> AggregateBy<TSource, TKey, TAccumulate>(Func<TSource,TKey>, TAccumulate, Func<TAccumulate,TSource,TAccumulate>, IEqualityComparer<TKey>)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.linq.enumerable.aggregateby#system-linq-enumerable-aggregateby-3(system-collections-generic-ienumerable((-0))-system-func((-0-1))-system-func((-1-2))-system-func((-2-0-2))-system-collections-generic-iequalitycomparer((-1))))
 * `IEnumerable<KeyValuePair<TKey,TAccumulate>> AggregateBy<TSource, TKey, TAccumulate>(Func<TSource,TKey>, Func<TKey,TAccumulate>, Func<TAccumulate,TSource,TAccumulate>, IEqualityComparer<TKey>)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.linq.enumerable.aggregateby?view=net-9.0#system-linq-enumerable-aggregateby-3(system-collections-generic-ienumerable((-0))-system-func((-0-1))-2-system-func((-2-0-2))-system-collections-generic-iequalitycomparer((-1))))
 * `IEnumerable<TSource> Append<TSource>(TSource)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.linq.enumerable.append)
 * `IEnumerable<TSource[]> Chunk<TSource>(Int32)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.linq.enumerable.chunk)
 * `IEnumerable<KeyValuePair<TKey,Int32>> CountBy<TSource, TKey>(Func<TSource,TKey>, IEqualityComparer<TKey>)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.linq.enumerable.countby)
 * `IEnumerable<TSource> DistinctBy<TSource, TKey>(Func<TSource,TKey>)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.linq.enumerable.distinctby#system-linq-enumerable-distinctby-2(system-collections-generic-ienumerable((-0))-system-func((-0-1))))
 * `IEnumerable<TSource> DistinctBy<TSource, TKey>(Func<TSource,TKey>, IEqualityComparer<TKey>)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.linq.enumerable.distinctby#system-linq-enumerable-distinctby-2(system-collections-generic-ienumerable((-0))-system-func((-0-1))-system-collections-generic-iequalitycomparer((-1))))
 * `TSource ElementAt<TSource>(Index)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.linq.enumerable.elementat#system-linq-enumerable-elementat-1(system-collections-generic-ienumerable((-0))-system-index))
 * `TSource ElementAtOrDefault<TSource>(Index)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.linq.enumerable.elementatordefault#system-linq-enumerable-elementatordefault-1(system-collections-generic-ienumerable((-0))-system-index))
 * `IEnumerable<TSource> Except<TSource>(TSource)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.linq.enumerable.except?view=net-8.0#system-linq-enumerable-except-1(system-collections-generic-ienumerable((-0))-system-collections-generic-ienumerable((-0))))
 * `IEnumerable<TSource> Except<TSource>(TSource[])` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.linq.enumerable.except?view=net-8.0#system-linq-enumerable-except-1(system-collections-generic-ienumerable((-0))-system-collections-generic-ienumerable((-0))))
 * `IEnumerable<TSource> Except<TSource>(TSource, IEqualityComparer<TSource>)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.linq.enumerable.except#system-linq-enumerable-except-1(system-collections-generic-ienumerable((-0))-system-collections-generic-ienumerable((-0))-system-collections-generic-iequalitycomparer((-0))))
 * `IEnumerable<TSource> Except<TSource>(IEqualityComparer<TSource>, TSource[])` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.linq.enumerable.except#system-linq-enumerable-except-1(system-collections-generic-ienumerable((-0))-system-collections-generic-ienumerable((-0))-system-collections-generic-iequalitycomparer((-0))))
 * `IEnumerable<TSource> ExceptBy<TSource, TKey>(IEnumerable<TKey>, Func<TSource,TKey>)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.linq.enumerable.exceptby#system-linq-enumerable-exceptby-2(system-collections-generic-ienumerable((-0))-system-collections-generic-ienumerable((-1))-system-func((-0-1))))
 * `IEnumerable<TSource> ExceptBy<TSource, TKey>(IEnumerable<TKey>, Func<TSource,TKey>, IEqualityComparer<TKey>)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.linq.enumerable.exceptby#system-linq-enumerable-exceptby-2(system-collections-generic-ienumerable((-0))-system-collections-generic-ienumerable((-1))-system-func((-0-1))-system-collections-generic-iequalitycomparer((-1))))
 * `TSource FirstOrDefault<TSource>(Func<TSource,Boolean>, TSource)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.linq.enumerable.firstordefault#system-linq-enumerable-firstordefault-1(system-collections-generic-ienumerable((-0))-system-func((-0-system-boolean))-0))
 * `TSource FirstOrDefault<TSource>(TSource)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.linq.enumerable.firstordefault#system-linq-enumerable-firstordefault-1(system-collections-generic-ienumerable((-0))-0))
 * `IEnumerable<ValueTuple<Int32,TSource>> Index<TSource>()` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.linq.enumerable.index#system-linq-enumerable-index-1(system-collections-generic-ienumerable((-0))))
 * `TSource LastOrDefault<TSource>(TSource)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.linq.enumerable.lastordefault#system-linq-enumerable-lastordefault-1(system-collections-generic-ienumerable((-0))-0))
 * `TSource LastOrDefault<TSource>(Func<TSource,Boolean>, TSource)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.linq.enumerable.lastordefault#system-linq-enumerable-lastordefault-1(system-collections-generic-ienumerable((-0))-system-func((-0-system-boolean))-0))
 * `TSource MaxBy<TSource, TKey>(Func<TSource,TKey>)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.linq.enumerable.maxby#system-linq-enumerable-maxby-2(system-collections-generic-ienumerable((-0))-system-func((-0-1))))
 * `TSource MaxBy<TSource, TKey>(Func<TSource,TKey>, IComparer<TKey>)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.linq.enumerable.maxby?view=net-8.0#system-linq-enumerable-maxby-2(system-collections-generic-ienumerable((-0))-system-func((-0-1))-system-collections-generic-icomparer((-1))))
 * `TSource MinBy<TSource, TKey>(Func<TSource,TKey>)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.linq.enumerable.minby#system-linq-enumerable-minby-2(system-collections-generic-ienumerable((-0))-system-func((-0-1))))
 * `TSource MinBy<TSource, TKey>(Func<TSource,TKey>, IComparer<TKey>)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.linq.enumerable.minby?view=net-8.0#system-linq-enumerable-minby-2(system-collections-generic-ienumerable((-0))-system-func((-0-1))-system-collections-generic-icomparer((-1))))
 * `TSource SingleOrDefault<TSource>(Func<TSource,Boolean>, TSource)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.linq.enumerable.singleordefault#system-linq-enumerable-singleordefault-1(system-collections-generic-ienumerable((-0))-system-func((-0-system-boolean))-0))
 * `TSource SingleOrDefault<TSource>(TSource)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.linq.enumerable.singleordefault#system-linq-enumerable-singleordefault-1(system-collections-generic-ienumerable((-0))-0))
 * `IEnumerable<TSource> SkipLast<TSource>(Int32)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.linq.enumerable.skiplast)
 * `HashSet<TSource> ToHashSet<TSource>(IEqualityComparer<TSource>)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.linq.enumerable.tohashset#system-linq-enumerable-tohashset-1(system-collections-generic-ienumerable((-0))-system-collections-generic-iequalitycomparer((-0))))
 * `Boolean TryGetNonEnumeratedCount<TSource>(Int32&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.linq.enumerable.trygetnonenumeratedcount)


#### IList<T>

 * `Collections.ObjectModel.ReadOnlyCollection<T> AsReadOnly<T>()` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.collections.generic.collectionextensions.asreadonly#system-collections-generic-collectionextensions-asreadonly-1(system-collections-generic-ilist((-0))))


#### IReadOnlyDictionary<TKey,TValue>

 * `TValue GetValueOrDefault<TKey, TValue>(TKey)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.collections.generic.collectionextensions.getvalueordefault)
 * `TValue GetValueOrDefault<TKey, TValue>(TKey, TValue)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.collections.generic.collectionextensions.getvalueordefault#system-collections-generic-collectionextensions-getvalueordefault-2(system-collections-generic-ireadonlydictionary((-0-1))-0-1))


#### KeyValuePair<TKey,TValue>

 * `Void Deconstruct<TKey, TValue>(TKey&, TValue&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.collections.generic.keyvaluepair-2.deconstruct)


#### List<T>

 * `Void AddRange<T>(ReadOnlySpan<T>)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.collections.generic.collectionextensions.addrange)
 * `Void CopyTo<T>(Span<T>)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.collections.generic.collectionextensions.copyto?view=net-8.0)
 * `Void InsertRange<T>(Int32, ReadOnlySpan<T>)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.collections.generic.collectionextensions.insertrange)


#### SortedList<TKey,TValue>

 * `TKey GetKeyAtIndex<TKey, TValue>(Int32)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.collections.generic.sortedlist-2.getkeyatindex?view=net-8.0)
 * `TValue GetValueAtIndex<TKey, TValue>(Int32)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.collections.generic.sortedlist-2.getvalueatindex?view=net-8.0)


#### DateOnly

 * `Boolean TryFormat(Span<Char>, Int32&, ReadOnlySpan<Char>, IFormatProvider)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.dateonly.tryformat)


#### DateTime

 * `DateTime AddMicroseconds(Double)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.datetime.addmicroseconds)
 * `Int32 Microsecond()` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.datetime.microsecond)
 * `Int32 Nanosecond()` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.datetime.nanosecond)
 * `Boolean TryFormat(Span<Char>, Int32&, ReadOnlySpan<Char>, IFormatProvider)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.datetime.tryformat)


#### DateTimeOffset

 * `DateTimeOffset AddMicroseconds(Double)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.datetimeoffset.addmicroseconds)
 * `Int32 Microsecond()` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.datetimeoffset.microsecond)
 * `Int32 Nanosecond()` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.datetimeoffset.nanosecond)
 * `Boolean TryFormat(Span<Char>, Int32&, ReadOnlySpan<Char>, IFormatProvider)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.datetimeoffset.tryformat)


#### Decimal

 * `Boolean TryFormat(Span<Char>, Int32&, ReadOnlySpan<Char>, IFormatProvider)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.decimal.tryformat)


#### Process

 * `Task WaitForExitAsync(CancellationToken)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.diagnostics.process.waitforexitasync)


#### Double

 * `Boolean TryFormat(Span<Char>, Int32&, ReadOnlySpan<Char>, IFormatProvider)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.double.tryformat)


#### Guid

 * `Boolean TryFormat(Span<Char>, Int32&, ReadOnlySpan<Char>)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.guid.tryformat#system-guid-tryformat(system-span((system-char))-system-int32@-system-readonlyspan((system-char))))


#### Int16

 * `Boolean TryFormat(Span<Char>, Int32&, ReadOnlySpan<Char>, IFormatProvider)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.int16.tryformat)


#### Int32

 * `Boolean TryFormat(Span<Char>, Int32&, ReadOnlySpan<Char>, IFormatProvider)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.int32.tryformat)


#### Int64

 * `Boolean TryFormat(Span<Char>, Int32&, ReadOnlySpan<Char>, IFormatProvider)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.int64.tryformat)


#### Stream

 * `Task CopyToAsync(Stream, CancellationToken)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.io.stream.copytoasync#system-io-stream-copytoasync(system-io-stream-system-threading-cancellationtoken))
 * `ValueTask<Int32> ReadAsync(Memory<Byte>, CancellationToken)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.io.stream.readasync#system-io-stream-readasync(system-memory((system-byte))-system-threading-cancellationtoken))
 * `ValueTask WriteAsync(ReadOnlyMemory<Byte>, CancellationToken)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.io.stream.writeasync#system-io-stream-writeasync(system-readonlymemory((system-byte))-system-threading-cancellationtoken))


#### TextReader

 * `ValueTask<Int32> ReadAsync(Memory<Char>, CancellationToken)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.io.textreader.readasync#system-io-textreader-readasync(system-memory((system-char))-system-threading-cancellationtoken))
 * `Task<String> ReadLineAsync(CancellationToken)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.io.textreader.readtoendasync#system-io-textreader-readlineasync(system-threading-cancellationtoken))
 * `Task<String> ReadToEndAsync(CancellationToken)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.io.textreader.readtoendasync#system-io-textreader-readtoendasync(system-threading-cancellationtoken))


#### TextWriter

 * `Void Write(ReadOnlySpan<Char>)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.io.textwriter.write#system-io-textwriter-write(system-readonlyspan((system-char))))
 * `ValueTask WriteAsync(ReadOnlyMemory<Char>, CancellationToken)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.io.textwriter.writeasync#system-io-textwriter-writeasync(system-readonlymemory((system-char))-system-threading-cancellationtoken))
 * `Void WriteLine(ReadOnlySpan<Char>)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.io.textwriter.writeline#system-io-textwriter-writeline(system-readonlyspan((system-char))))
 * `ValueTask WriteLineAsync(ReadOnlyMemory<Char>, CancellationToken)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.io.textwriter.writelineasync#system-io-textwriter-writelineasync(system-readonlymemory((system-char))-system-threading-cancellationtoken))


#### HttpClient

 * `Task<Byte[]> GetByteArrayAsync(String, CancellationToken)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.net.http.httpclient.getbytearrayasync#system-net-http-httpclient-getbytearrayasync(system-string-system-threading-cancellationtoken))
 * `Task<Byte[]> GetByteArrayAsync(Uri, CancellationToken)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.net.http.httpclient.getbytearrayasync#system-net-http-httpclient-getbytearrayasync(system-uri-system-threading-cancellationtoken))
 * `Task<Stream> GetStreamAsync(String, CancellationToken)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.net.http.httpclient.getstreamasync#system-net-http-httpclient-getstreamasync(system-string-system-threading-cancellationtoken))
 * `Task<Stream> GetStreamAsync(Uri, CancellationToken)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.net.http.httpclient.getstreamasync#system-net-http-httpclient-getstreamasync(system-uri-system-threading-cancellationtoken))
 * `Task<String> GetStringAsync(String, CancellationToken)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.net.http.httpclient.getstringasync#system-net-http-httpclient-getstringasync(system-string-system-threading-cancellationtoken))
 * `Task<String> GetStringAsync(Uri, CancellationToken)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.net.http.httpclient.getstringasync#system-net-http-httpclient-getstringasync(system-uri-system-threading-cancellationtoken))


#### HttpContent

 * `Task<Byte[]> ReadAsByteArrayAsync(CancellationToken)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.net.http.httpcontent.readasbytearrayasync#system-net-http-httpcontent-readasbytearrayasync(system-threading-cancellationtoken))
 * `Task<Stream> ReadAsStreamAsync(CancellationToken)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.net.http.httpcontent.readasstreamasync#system-net-http-httpcontent-readasstreamasync(system-threading-cancellationtoken))
 * `Task<String> ReadAsStringAsync(CancellationToken)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.net.http.httpcontent.readasstringasync#system-net-http-httpcontent-readasstringasync(system-threading-cancellationtoken))


#### ReadOnlySpan<Char>

 * `Boolean EndsWith(String, StringComparison)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.memoryextensions.endswith#system-memoryextensions-endswith-1(system-readonlyspan((-0))-system-readonlyspan((-0))))
 * `SpanLineEnumerator EnumerateLines()` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.memoryextensions.enumeratelines#system-memoryextensions-enumeratelines(system-readonlyspan((system-char))))
 * `Boolean SequenceEqual(String)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.memoryextensions.sequenceequal#system-memoryextensions-sequenceequal-1(system-readonlyspan((-0))-system-readonlyspan((-0))))
 * `Boolean StartsWith(String, StringComparison)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.memoryextensions.startswith#system-memoryextensions-startswith-1(system-readonlyspan((-0))-system-readonlyspan((-0))))


#### ReadOnlySpan<T>

 * `Boolean Contains<T>(T)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.memoryextensions.contains#system-memoryextensions-contains-1(system-readonlyspan((-0))-0))


#### Reflection.EventInfo

 * `Reflection.NullabilityState GetNullability()`
 * `Reflection.NullabilityInfo GetNullabilityInfo()`
 * `Boolean IsNullable()`


#### Reflection.FieldInfo

 * `Reflection.NullabilityState GetNullability()`
 * `Reflection.NullabilityInfo GetNullabilityInfo()`
 * `Boolean IsNullable()`


#### Reflection.MemberInfo

 * `Reflection.NullabilityState GetNullability()`
 * `Reflection.NullabilityInfo GetNullabilityInfo()`
 * `Boolean HasSameMetadataDefinitionAs(Reflection.MemberInfo)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.reflection.memberinfo.hassamemetadatadefinitionas)
 * `Boolean IsNullable()`


#### Reflection.ParameterInfo

 * `Reflection.NullabilityState GetNullability()`
 * `Reflection.NullabilityInfo GetNullabilityInfo()`
 * `Boolean IsNullable()`


#### Reflection.PropertyInfo

 * `Reflection.NullabilityState GetNullability()`
 * `Reflection.NullabilityInfo GetNullabilityInfo()`
 * `Boolean IsNullable()`


#### SByte

 * `Boolean TryFormat(Span<Char>, Int32&, ReadOnlySpan<Char>, IFormatProvider)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.sbyte.tryformat)


#### Single

 * `Boolean TryFormat(Span<Char>, Int32&, ReadOnlySpan<Char>, IFormatProvider)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.single.tryformat)


#### Span<Char>

 * `Boolean EndsWith(String)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.memoryextensions.endswith#system-memoryextensions-endswith-1(system-span((-0))-system-readonlyspan((-0))))
 * `SpanLineEnumerator EnumerateLines()` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.memoryextensions.enumeratelines#system-memoryextensions-enumeratelines(system-span((system-char))))
 * `Boolean SequenceEqual(String)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.memoryextensions.sequenceequal#system-memoryextensions-sequenceequal-1(system-span((-0))-system-readonlyspan((-0))))
 * `Boolean StartsWith(String)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.memoryextensions.startswith#system-memoryextensions-startswith-1(system-span((-0))-system-readonlyspan((-0))))
 * `Span<Char> TrimEnd()` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.memoryextensions.trimend#system-memoryextensions-trimend(system-span((system-char))))
 * `Span<Char> TrimStart()` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.memoryextensions.trimstart#system-memoryextensions-trimstart(system-span((system-char))))


#### Span<T>

 * `Boolean Contains<T>(T)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.memoryextensions.contains#system-memoryextensions-contains-1(system-span((-0))-0))


#### String

 * `Boolean Contains(String, StringComparison)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.string.contains#system-string-contains(system-string-system-stringcomparison))
 * `Boolean Contains(Char)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.string.contains#system-string-contains(system-char))
 * `Void CopyTo(Span<Char>)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.string.copyto)
 * `Boolean EndsWith(Char)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.string.contains#system-string-contains(system-char))
 * `Int32 GetHashCode(StringComparison)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.string.gethashcode#system-string-gethashcode(system-stringcomparison))
 * `String[] Split(Char, StringSplitOptions)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.string.split#system-string-split(system-char-system-stringsplitoptions))
 * `String[] Split(Char, Int32, StringSplitOptions)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.string.split#system-string-split(system-char-system-int32-system-stringsplitoptions))
 * `Boolean StartsWith(Char)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.string.contains#system-string-contains(system-char))
 * `Boolean TryCopyTo(Span<Char>)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.string.trycopyto)


#### Regex

 * `ValueMatchEnumerator EnumerateMatches(ReadOnlySpan<Char>)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.text.regularexpressions.regex.enumeratematches#system-text-regularexpressions-regex-enumeratematches(system-readonlyspan((system-char))))
 * `ValueMatchEnumerator EnumerateMatches(ReadOnlySpan<Char>, Int32)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.text.regularexpressions.regex.enumeratematches#system-text-regularexpressions-regex-enumeratematches(system-readonlyspan((system-char))-system-int32))
 * `Boolean IsMatch(ReadOnlySpan<Char>, Int32)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.text.regularexpressions.regex.ismatch#system-text-regularexpressions-regex-ismatch(system-readonlyspan((system-char))-system-int32))
 * `Boolean IsMatch(ReadOnlySpan<Char>)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.text.regularexpressions.regex.ismatch#system-text-regularexpressions-regex-ismatch(system-readonlyspan((system-char))))


#### StringBuilder

 * `StringBuilder Append(ReadOnlySpan<Char>)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.text.stringbuilder.append#system-text-stringbuilder-append(system-readonlyspan((system-char))))
 * `StringBuilder Append(StringBuilder, AppendInterpolatedStringHandler&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.text.stringbuilder.append#system-text-stringbuilder-append(system-text-stringbuilder-appendinterpolatedstringhandler@))
 * `StringBuilder Append(StringBuilder, IFormatProvider, AppendInterpolatedStringHandler&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.text.stringbuilder.append#system-text-stringbuilder-append(system-iformatprovider-system-text-stringbuilder-appendinterpolatedstringhandler@))
 * `StringBuilder Append(StringBuilder, StringBuilder/AppendInterpolatedStringHandler&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.text.stringbuilder.append#system-text-stringbuilder-append(system-text-stringbuilder-appendinterpolatedstringhandler@))
 * `StringBuilder Append(StringBuilder, IFormatProvider, StringBuilder/AppendInterpolatedStringHandler&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.text.stringbuilder.append#system-text-stringbuilder-append(system-iformatprovider-system-text-stringbuilder-appendinterpolatedstringhandler@))
 * `StringBuilder AppendJoin(String, String[])` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.text.stringbuilder.appendjoin?view=netcore-2.0#system-text-stringbuilder-appendjoin(system-string-system-string()))
 * `StringBuilder AppendJoin(String, Object[])` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.text.stringbuilder.appendjoin?view=netcore-2.0#system-text-stringbuilder-appendjoin(system-string-system-object()))
 * `StringBuilder AppendJoin(Char, String[])` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.text.stringbuilder.appendjoin?view=netcore-2.0#system-text-stringbuilder-appendjoin(system-char-system-string()))
 * `StringBuilder AppendJoin(Char, Object[])` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.text.stringbuilder.appendjoin?view=netcore-2.0#system-text-stringbuilder-appendjoin(system-char-system-object()))
 * `StringBuilder AppendJoin<T>(Char, T[])` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.text.stringbuilder.appendjoin?view=netcore-2.0#system-text-stringbuilder-appendjoin-1(system-char-system-collections-generic-ienumerable((-0))))
 * `StringBuilder AppendJoin<T>(String, T[])` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.text.stringbuilder.appendjoin?view=netcore-2.0#system-text-stringbuilder-appendjoin-1(system-string-system-collections-generic-ienumerable((-0))))
 * `StringBuilder AppendLine(StringBuilder, AppendInterpolatedStringHandler&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.text.stringbuilder.appendline#system-text-stringbuilder-appendline(system-text-stringbuilder-appendinterpolatedstringhandler@))
 * `StringBuilder AppendLine(StringBuilder, IFormatProvider, AppendInterpolatedStringHandler&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.text.stringbuilder.appendline#system-text-stringbuilder-appendline(system-iformatprovider-system-text-stringbuilder-appendinterpolatedstringhandler@))
 * `StringBuilder AppendLine(StringBuilder, StringBuilder/AppendInterpolatedStringHandler&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.text.stringbuilder.appendline#system-text-stringbuilder-appendline(system-text-stringbuilder-appendinterpolatedstringhandler@))
 * `StringBuilder AppendLine(StringBuilder, IFormatProvider, StringBuilder/AppendInterpolatedStringHandler&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.text.stringbuilder.appendline#system-text-stringbuilder-appendline(system-iformatprovider-system-text-stringbuilder-appendinterpolatedstringhandler@))
 * `Void CopyTo(Int32, Span<Char>, Int32)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.text.stringbuilder.copyto#system-text-stringbuilder-copyto(system-int32-system-span((system-char))-system-int32))
 * `Boolean Equals(ReadOnlySpan<Char>)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.text.stringbuilder.equals#system-text-stringbuilder-equals(system-readonlyspan((system-char))))
 * `Polyfill/ChunkEnumerator GetChunks()` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.text.stringbuilder.getchunks)
 * `StringBuilder Replace(ReadOnlySpan<Char>, ReadOnlySpan<Char>)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.text.stringbuilder.replace#system-text-stringbuilder-replace(system-readonlyspan((system-char))-system-readonlyspan((system-char))))
 * `StringBuilder Replace(ReadOnlySpan<Char>, ReadOnlySpan<Char>, Int32, Int32)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.text.stringbuilder.replace#system-text-stringbuilder-replace(system-readonlyspan((system-char))-system-readonlyspan((system-char))-system-int32-system-int32)


#### CancellationToken

 * `CancellationTokenRegistration Register(Action<Object,CancellationToken>, Object)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.threading.cancellationtoken.register#system-threading-cancellationtoken-register(system-action((system-object-system-threading-cancellationtoken))-system-object))
 * `CancellationTokenRegistration UnsafeRegister(Action<Object>, Object)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.threading.cancellationtoken.unsaferegister#system-threading-cancellationtoken-unsaferegister(system-action((system-object))-system-object))
 * `CancellationTokenRegistration UnsafeRegister(Action<Object,CancellationToken>, Object)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.threading.cancellationtoken.unsaferegister#system-threading-cancellationtoken-unsaferegister(system-action((system-object-system-threading-cancellationtoken))-system-object))


#### CancellationTokenSource

 * `Task CancelAsync()` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.threading.cancellationtokensource.cancelasync)


#### Task

 * `Task WaitAsync(CancellationToken)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.threading.tasks.task.waitasync#system-threading-tasks-task-waitasync(system-threading-cancellationtoken))
 * `Task WaitAsync(TimeSpan)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.threading.tasks.task.waitasync#system-threading-tasks-task-waitasync(system-timespan))
 * `Task WaitAsync(TimeSpan, CancellationToken)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.threading.tasks.task.waitasync#system-threading-tasks-task-waitasync(system-timespan-system-threading-cancellationtoken))


#### Task<TResult>

 * `Task<TResult> WaitAsync<TResult>(CancellationToken)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.threading.tasks.task.waitasync#system-threading-tasks-task-waitasync(system-threading-cancellationtoken))
 * `Task<TResult> WaitAsync<TResult>(TimeSpan)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.threading.tasks.task-1.waitasync#system-threading-tasks-task-1-waitasync(system-timespan))
 * `Task<TResult> WaitAsync<TResult>(TimeSpan, CancellationToken)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.threading.tasks.task-1.waitasync#system-threading-tasks-task-1-waitasync(system-timespan-system-threading-cancellationtoken))


#### TimeOnly

 * `Boolean TryFormat(Span<Char>, Int32&, ReadOnlySpan<Char>, IFormatProvider)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.timeonly.tryformat)


#### TimeSpan

 * `Int32 Microseconds()` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.timespan.microseconds)
 * `Int32 Nanoseconds()` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.timespan.nanoseconds)
 * `Boolean TryFormat(Span<Char>, Int32&, ReadOnlySpan<Char>, IFormatProvider)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.timespan.tryformat#system-timespan-tryformat(system-span((system-byte))-system-int32@-system-readonlyspan((system-char))-system-iformatprovider))


#### Type

 * `Boolean IsAssignableFrom<T>()`
 * `Boolean IsAssignableTo<T>()`
 * `Boolean IsAssignableTo(Type)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.type.isassignableto)
 * `Boolean IsGenericMethodParameter()` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.type.isgenericmethodparameter)


#### UInt16

 * `Boolean TryFormat(Span<Char>, Int32&, ReadOnlySpan<Char>, IFormatProvider)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.uint16.tryformat)


#### UInt32

 * `Boolean TryFormat(Span<Char>, Int32&, ReadOnlySpan<Char>, IFormatProvider)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.uint32.tryformat)


#### UInt64

 * `Boolean TryFormat(Span<Char>, Int32&, ReadOnlySpan<Char>, IFormatProvider)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.uint64.tryformat)


### Static helpers

#### EnumPolyfill

 * `String[] GetNames<TEnum>()` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.enum.getnames)
 * `TEnum[] GetValues<TEnum>()` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.enum.getvalues)


#### RegexPolyfill

 * `ValueMatchEnumerator EnumerateMatches(ReadOnlySpan<Char>, String)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.text.regularexpressions.regex.enumeratematches?view=net-8.0#system-text-regularexpressions-regex-enumeratematches(system-readonlyspan((system-char))-system-string))
 * `ValueMatchEnumerator EnumerateMatches(ReadOnlySpan<Char>, String, RegexOptions, TimeSpan)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.text.regularexpressions.regex.enumeratematches#system-text-regularexpressions-regex-enumeratematches(system-readonlyspan((system-char))-system-string-system-text-regularexpressions-regexoptions-system-timespan))
 * `ValueMatchEnumerator EnumerateMatches(ReadOnlySpan<Char>, String, RegexOptions)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.text.regularexpressions.regex.enumeratematches#system-text-regularexpressions-regex-enumeratematches(system-readonlyspan((system-char))-system-string-system-text-regularexpressions-regexoptions))
 * `Regex/ValueMatchEnumerator EnumerateMatches(ReadOnlySpan<Char>, String)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.text.regularexpressions.regex.enumeratematches?view=net-8.0#system-text-regularexpressions-regex-enumeratematches(system-readonlyspan((system-char))-system-string))
 * `Regex/ValueMatchEnumerator EnumerateMatches(ReadOnlySpan<Char>, String, RegexOptions, TimeSpan)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.text.regularexpressions.regex.enumeratematches#system-text-regularexpressions-regex-enumeratematches(system-readonlyspan((system-char))-system-string-system-text-regularexpressions-regexoptions-system-timespan))
 * `Regex/ValueMatchEnumerator EnumerateMatches(ReadOnlySpan<Char>, String, RegexOptions)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.text.regularexpressions.regex.enumeratematches#system-text-regularexpressions-regex-enumeratematches(system-readonlyspan((system-char))-system-string-system-text-regularexpressions-regexoptions))
 * `Boolean IsMatch(ReadOnlySpan<Char>, String, RegexOptions, TimeSpan)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.text.regularexpressions.regex.ismatch#system-text-regularexpressions-regex-ismatch(system-readonlyspan((system-char))-system-string-system-text-regularexpressions-regexoptions-system-timespan))
 * `Boolean IsMatch(ReadOnlySpan<Char>, String, RegexOptions)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.text.regularexpressions.regex.ismatch#system-text-regularexpressions-regex-ismatch(system-readonlyspan((system-char))-system-string-system-text-regularexpressions-regexoptions))
 * `Boolean IsMatch(ReadOnlySpan<Char>, String)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.text.regularexpressions.regex.ismatch#system-text-regularexpressions-regex-ismatch(system-readonlyspan((system-char))-system-string))


#### StringPolyfill

 * `String Join(Char, String[])` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.string.join#system-string-join(system-char-system-string()))
 * `String Join(Char, Object[])` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.string.join#system-string-join(system-char-system-object()))
 * `String Join(Char, String[], Int32, Int32)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.string.join#system-string-join(system-char-system-string()-system-int32-system-int32))
 * `String Join<T>(Char, IEnumerable<T>)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.string.join#system-string-join-1(system-char-system-collections-generic-ienumerable((-0))))


#### BytePolyfill

 * `Boolean TryParse(String, IFormatProvider, Byte&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.byte.tryparse#system-byte-tryparse(system-string-system-iformatprovider-system-byte@))
 * `Boolean TryParse(ReadOnlySpan<Byte>, IFormatProvider, Byte&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.byte.tryparse#system-byte-tryparse(system-readonlyspan((system-byte))-system-iformatprovider-system-byte@))
 * `Boolean TryParse(ReadOnlySpan<Char>, Byte&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.byte.tryparse#system-byte-tryparse(system-readonlyspan((system-char))-system-byte@))
 * `Boolean TryParse(ReadOnlySpan<Char>, IFormatProvider, Byte&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.byte.tryparse#system-byte-tryparse(system-readonlyspan((system-char))-system-iformatprovider-system-byte@))
 * `Boolean TryParse(ReadOnlySpan<Byte>, Globalization.NumberStyles, IFormatProvider, Byte&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.byte.tryparse#system-byte-tryparse(system-readonlyspan((system-byte))-system-globalization-numberstyles-system-iformatprovider-system-byte@))
 * `Boolean TryParse(ReadOnlySpan<Byte>, Byte&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.byte.tryparse#system-byte-tryparse(system-readonlyspan((system-char))-system-globalization-numberstyles-system-iformatprovider-system-byte@))
 * `Boolean TryParse(ReadOnlySpan<Char>, Globalization.NumberStyles, IFormatProvider, Byte&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.byte.tryparse#system-byte-tryparse(system-readonlyspan((system-char))-system-globalization-numberstyles-system-iformatprovider-system-byte@))


#### DoublePolyfill

 * `Boolean TryParse(String, IFormatProvider, Double&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.double.tryparse#system-double-tryparse(system-string-system-iformatprovider-system-double@))
 * `Boolean TryParse(ReadOnlySpan<Byte>, IFormatProvider, Double&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.double.tryparse#system-double-tryparse(system-readonlyspan((system-byte))-system-iformatprovider-system-double@))
 * `Boolean TryParse(ReadOnlySpan<Char>, Double&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.double.tryparse#system-double-tryparse(system-readonlyspan((system-char))-system-double@))
 * `Boolean TryParse(ReadOnlySpan<Char>, IFormatProvider, Double&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.double.tryparse#system-double-tryparse(system-readonlyspan((system-char))-system-iformatprovider-system-double@))
 * `Boolean TryParse(ReadOnlySpan<Byte>, Globalization.NumberStyles, IFormatProvider, Double&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.double.tryparse#system-double-tryparse(system-readonlyspan((system-byte))-system-globalization-numberstyles-system-iformatprovider-system-double@))
 * `Boolean TryParse(ReadOnlySpan<Byte>, Double&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.double.tryparse#system-double-tryparse(system-readonlyspan((system-byte))-system-double@))
 * `Boolean TryParse(ReadOnlySpan<Char>, Globalization.NumberStyles, IFormatProvider, Double&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.double.tryparse#system-double-tryparse(system-readonlyspan((system-char))-system-globalization-numberstyles-system-iformatprovider-system-double@))


#### IntPolyfill

 * `Boolean TryParse(String, IFormatProvider, Int32&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.int32.tryparse#system-int32-tryparse(system-string-system-iformatprovider-system-int32@))
 * `Boolean TryParse(ReadOnlySpan<Byte>, IFormatProvider, Int32&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.int32.tryparse#system-int32-tryparse(system-readonlyspan((system-byte))-system-iformatprovider-system-int32@))
 * `Boolean TryParse(ReadOnlySpan<Char>, Int32&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.int32.tryparse#system-int32-tryparse(system-readonlyspan((system-char))-system-int32@))
 * `Boolean TryParse(ReadOnlySpan<Char>, IFormatProvider, Int32&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.int32.tryparse#system-int32-tryparse(system-readonlyspan((system-char))-system-iformatprovider-system-int32@))
 * `Boolean TryParse(ReadOnlySpan<Byte>, Globalization.NumberStyles, IFormatProvider, Int32&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.int32.tryparse#system-int32-tryparse(system-readonlyspan((system-byte))-system-globalization-numberstyles-system-iformatprovider-system-int32@))
 * `Boolean TryParse(ReadOnlySpan<Byte>, Int32&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.int32.tryparse#system-int32-tryparse(system-readonlyspan((system-char))-system-globalization-numberstyles-system-iformatprovider-system-int32@))
 * `Boolean TryParse(ReadOnlySpan<Char>, Globalization.NumberStyles, IFormatProvider, Int32&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.int32.tryparse#system-int32-tryparse(system-readonlyspan((system-char))-system-globalization-numberstyles-system-iformatprovider-system-int32@))


#### LongPolyfill

 * `Boolean TryParse(String, IFormatProvider, Int32&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.int64.tryparse#system-int64-tryparse(system-string-system-iformatprovider-system-int64@))
 * `Boolean TryParse(ReadOnlySpan<Byte>, IFormatProvider, Int32&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.int64.tryparse#system-int64-tryparse(system-readonlyspan((system-byte))-system-iformatprovider-system-int64@))
 * `Boolean TryParse(ReadOnlySpan<Char>, Int32&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.int64.tryparse#system-int64-tryparse(system-readonlyspan((system-char))-system-int64@))
 * `Boolean TryParse(ReadOnlySpan<Char>, IFormatProvider, Int32&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.int64.tryparse#system-int64-tryparse(system-readonlyspan((system-char))-system-iformatprovider-system-int64@))
 * `Boolean TryParse(ReadOnlySpan<Byte>, Globalization.NumberStyles, IFormatProvider, Int32&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.int64.tryparse#system-int64-tryparse(system-readonlyspan((system-byte))-system-globalization-numberstyles-system-iformatprovider-system-int64@))
 * `Boolean TryParse(ReadOnlySpan<Byte>, Int32&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.int64.tryparse#system-int64-tryparse(system-readonlyspan((system-char))-system-globalization-numberstyles-system-iformatprovider-system-int64@))
 * `Boolean TryParse(ReadOnlySpan<Char>, Globalization.NumberStyles, IFormatProvider, Int32&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.int64.tryparse#system-int64-tryparse(system-readonlyspan((system-char))-system-globalization-numberstyles-system-iformatprovider-system-int64@))


#### SBytePolyfill

 * `Boolean TryParse(String, IFormatProvider, SByte&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.sbyte.tryparse#system-sbyte-tryparse(system-string-system-iformatprovider-system-sbyte@))
 * `Boolean TryParse(ReadOnlySpan<Byte>, IFormatProvider, SByte&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.sbyte.tryparse#system-sbyte-tryparse(system-readonlyspan((system-byte))-system-iformatprovider-system-sbyte@))
 * `Boolean TryParse(ReadOnlySpan<Char>, SByte&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.sbyte.tryparse#system-sbyte-tryparse(system-readonlyspan((system-char))-system-sbyte@))
 * `Boolean TryParse(ReadOnlySpan<Char>, IFormatProvider, SByte&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.sbyte.tryparse#system-sbyte-tryparse(system-readonlyspan((system-char))-system-iformatprovider-system-sbyte@))
 * `Boolean TryParse(ReadOnlySpan<Byte>, Globalization.NumberStyles, IFormatProvider, SByte&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.sbyte.tryparse#system-sbyte-tryparse(system-readonlyspan((system-byte))-system-globalization-numberstyles-system-iformatprovider-system-sbyte@))
 * `Boolean TryParse(ReadOnlySpan<Byte>, SByte&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.sbyte.tryparse#system-sbyte-tryparse(system-readonlyspan((system-char))-system-globalization-numberstyles-system-iformatprovider-system-sbyte@))
 * `Boolean TryParse(ReadOnlySpan<Char>, Globalization.NumberStyles, IFormatProvider, SByte&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.sbyte.tryparse#system-sbyte-tryparse(system-readonlyspan((system-char))-system-globalization-numberstyles-system-iformatprovider-system-sbyte@))


#### ShortPolyfill

 * `Boolean TryParse(String, IFormatProvider, Int16&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.int16.tryparse#system-int16-tryparse(system-string-system-iformatprovider-system-int16@))
 * `Boolean TryParse(ReadOnlySpan<Byte>, IFormatProvider, Int16&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.int16.tryparse#system-int16-tryparse(system-readonlyspan((system-byte))-system-iformatprovider-system-int16@))
 * `Boolean TryParse(ReadOnlySpan<Char>, Int16&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.int16.tryparse#system-int16-tryparse(system-readonlyspan((system-char))-system-int16@))
 * `Boolean TryParse(ReadOnlySpan<Char>, IFormatProvider, Int16&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.int16.tryparse#system-int16-tryparse(system-readonlyspan((system-char))-system-iformatprovider-system-int16@))
 * `Boolean TryParse(ReadOnlySpan<Byte>, Globalization.NumberStyles, IFormatProvider, Int16&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.int16.tryparse#system-int16-tryparse(system-readonlyspan((system-byte))-system-globalization-numberstyles-system-iformatprovider-system-int16@))
 * `Boolean TryParse(ReadOnlySpan<Byte>, Int16&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.int16.tryparse#system-int16-tryparse(system-readonlyspan((system-char))-system-globalization-numberstyles-system-iformatprovider-system-int16@))
 * `Boolean TryParse(ReadOnlySpan<Char>, Globalization.NumberStyles, IFormatProvider, Int16&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.int16.tryparse#system-int16-tryparse(system-readonlyspan((system-char))-system-globalization-numberstyles-system-iformatprovider-system-int16@))


#### UIntPolyfill

 * `Boolean TryParse(String, IFormatProvider, UInt32&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.uint32.tryparse#system-uint32-tryparse(system-string-system-iformatprovider-system-uint32@))
 * `Boolean TryParse(ReadOnlySpan<Byte>, IFormatProvider, UInt32&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.uint32.tryparse#system-uint32-tryparse(system-readonlyspan((system-byte))-system-iformatprovider-system-uint32@))
 * `Boolean TryParse(ReadOnlySpan<Char>, UInt32&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.uint32.tryparse#system-uint32-tryparse(system-readonlyspan((system-char))-system-uint32@))
 * `Boolean TryParse(ReadOnlySpan<Char>, IFormatProvider, UInt32&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.uint32.tryparse#system-uint32-tryparse(system-readonlyspan((system-char))-system-iformatprovider-system-uint32@))
 * `Boolean TryParse(ReadOnlySpan<Byte>, Globalization.NumberStyles, IFormatProvider, UInt32&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.uint32.tryparse#system-uint32-tryparse(system-readonlyspan((system-byte))-system-globalization-numberstyles-system-iformatprovider-system-uint32@))
 * `Boolean TryParse(ReadOnlySpan<Byte>, UInt32&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.uint32.tryparse#system-uint32-tryparse(system-readonlyspan((system-char))-system-globalization-numberstyles-system-iformatprovider-system-uint32@))
 * `Boolean TryParse(ReadOnlySpan<Char>, Globalization.NumberStyles, IFormatProvider, UInt32&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.uint32.tryparse#system-uint32-tryparse(system-readonlyspan((system-char))-system-globalization-numberstyles-system-iformatprovider-system-uint32@))


#### ULongPolyfill

 * `Boolean TryParse(String, IFormatProvider, UInt64&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.uint64.tryparse#system-uint64-tryparse(system-string-system-iformatprovider-system-uint64@))
 * `Boolean TryParse(ReadOnlySpan<Byte>, IFormatProvider, UInt64&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.uint64.tryparse#system-uint64-tryparse(system-readonlyspan((system-byte))-system-iformatprovider-system-uint64@))
 * `Boolean TryParse(ReadOnlySpan<Char>, UInt64&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.uint64.tryparse#system-uint64-tryparse(system-readonlyspan((system-char))-system-uint64@))
 * `Boolean TryParse(ReadOnlySpan<Char>, IFormatProvider, UInt64&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.uint64.tryparse#system-uint64-tryparse(system-readonlyspan((system-char))-system-iformatprovider-system-uint64@))
 * `Boolean TryParse(ReadOnlySpan<Byte>, Globalization.NumberStyles, IFormatProvider, UInt64&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.uint64.tryparse#system-uint64-tryparse(system-readonlyspan((system-byte))-system-globalization-numberstyles-system-iformatprovider-system-uint64@))
 * `Boolean TryParse(ReadOnlySpan<Byte>, UInt64&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.uint64.tryparse#system-uint64-tryparse(system-readonlyspan((system-char))-system-globalization-numberstyles-system-iformatprovider-system-uint64@))
 * `Boolean TryParse(ReadOnlySpan<Char>, Globalization.NumberStyles, IFormatProvider, UInt64&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.uint64.tryparse#system-uint64-tryparse(system-readonlyspan((system-char))-system-globalization-numberstyles-system-iformatprovider-system-uint64@))


#### UShortPolyfill

 * `Boolean TryParse(String, IFormatProvider, UInt16&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.uint16.tryparse#system-uint16-tryparse(system-string-system-iformatprovider-system-uint16@))
 * `Boolean TryParse(ReadOnlySpan<Byte>, IFormatProvider, UInt16&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.uint16.tryparse#system-uint16-tryparse(system-readonlyspan((system-byte))-system-iformatprovider-system-uint16@))
 * `Boolean TryParse(ReadOnlySpan<Char>, UInt16&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.uint16.tryparse#system-uint16-tryparse(system-readonlyspan((system-char))-system-uint16@))
 * `Boolean TryParse(ReadOnlySpan<Char>, IFormatProvider, UInt16&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.uint16.tryparse#system-uint16-tryparse(system-readonlyspan((system-char))-system-iformatprovider-system-uint16@))
 * `Boolean TryParse(ReadOnlySpan<Byte>, Globalization.NumberStyles, IFormatProvider, UInt16&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.uint16.tryparse#system-uint16-tryparse(system-readonlyspan((system-byte))-system-globalization-numberstyles-system-iformatprovider-system-uint16@))
 * `Boolean TryParse(ReadOnlySpan<Byte>, UInt16&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.uint16.tryparse#system-uint16-tryparse(system-readonlyspan((system-char))-system-globalization-numberstyles-system-iformatprovider-system-uint16@))
 * `Boolean TryParse(ReadOnlySpan<Char>, Globalization.NumberStyles, IFormatProvider, UInt16&)` [reference](https://learn.microsoft.com/en-us/dotnet/api/system.uint16.tryparse#system-uint16-tryparse(system-readonlyspan((system-char))-system-globalization-numberstyles-system-iformatprovider-system-uint16@))


