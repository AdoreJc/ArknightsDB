# StatisticToolConfig

**Namespace:** `Torappu`


## Fields

- `Boolean _recordDataAtStart`

- `Single _disableLogToFileTime`

- `String _filePath`


## Properties

- `String filePath`

- `Boolean recordDataAtStart`

- `Single disableLogToFileTime`


## Methods

- `String get_filePath()`

- `Void CleanFilesInFolder()`

- `Boolean get_recordDataAtStart()`

- `Single get_disableLogToFileTime()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class StatisticToolConfig : ScriptableObject
{
	private Boolean _recordDataAtStart; // 0x18
	private Single _disableLogToFileTime; // 0x1c
	private String _filePath; // 0x20
	public PathAndPrefix[] pathAndPrefixs; // 0x28

	public String filePath { get; }
	public Boolean recordDataAtStart { get; }
	public Single disableLogToFileTime { get; }

	// RVA: 0x2d0471c VA: 0x759531c71c
	public String get_filePath() { }
	// RVA: 0x2d04724 VA: 0x759531c724
	private Void CleanFilesInFolder() { }
	// RVA: 0x2d04728 VA: 0x759531c728
	public Boolean get_recordDataAtStart() { }
	// RVA: 0x2d04730 VA: 0x759531c730
	public Single get_disableLogToFileTime() { }
	// RVA: 0x2d04738 VA: 0x759531c738
	public Void .ctor() { }
}
```