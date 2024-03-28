# LinQ


```sh
sbt clean coverage test
```

```scala
dtWhitelistData.Select().Where(Function(x) x.Item("DomainName").ToString.ToLower.Equals(emailSenderHost.ToLower)).ToArray
```

```scala
(from item in arrStrSplit where Not item.Contains("Page")).ToArray
```

```scala
dtData.AsEnumerable.Where(Function (x) x("CCode").toString.Trim.ToUpper.Equals(strCCFilter.ToUpper)).ToList
```

```scala
(from item in arrStrSplit where Not String.IsNullOrWhiteSpace(item.Trim)).ToArray
```

```scala
String.Join(" ", regexMatch.Cast(Of match).Select(function(d) d.ToString).ToArray)
```

```scala
(from item in lstNewData where item.Contains("3059 Subtotal") or item.Contains("8155 Subtotal")).ToList
```





You can read more ([https://github.com/rpa92/uipath/blob/main/README.md](https://github.com/rpa92/uipath/blob/main/README.md))

# Conclusion<a id="sec-3" name="sec-3"></a>

While you may want to structure your projects different. This set up works and is the one that I will continue to update. If you want to contribute please feel free to submit a pull request!
