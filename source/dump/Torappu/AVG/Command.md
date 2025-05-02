# Command

**Namespace:** `Torappu.AVG`


## Fields

- `String command`

- `String content`

- `Int32 lineNumber`


## Methods

- `Boolean TryGetParam(String, out)`

- `Boolean TryGetParam(String, out)`

- `Boolean TryGetParam(String, out)`

- `Boolean TryGetParam(String, out)`

- `Boolean TryGetParam(String, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class Command
{
	public String command; // 0x10
	public String content; // 0x18
	public Dictionary`2 param; // 0x20
	public Int32 lineNumber; // 0x28


	// RVA: 0x3e5d600 VA: 0x7596475600
	public Boolean TryGetParam(String key, out Object value) { }
	// RVA: 0x3e5d688 VA: 0x7596475688
	public Boolean TryGetParam(String key, out Single value) { }
	// RVA: 0x3e5d724 VA: 0x7596475724
	public Boolean TryGetParam(String key, out Int32 value) { }
	// RVA: 0x3e5d7c4 VA: 0x75964757c4
	public Boolean TryGetParam(String key, out Boolean value) { }
	// RVA: 0x3e5d864 VA: 0x7596475864
	public Boolean TryGetParam(String key, out String value) { }
	// RVA: 0x VA: 0x0
	public static Boolean TryGetParam(IList`1 keys, out T value, TryGetParamDelegate`1 getter) { }
	// RVA: 0x VA: 0x0
	public static T GetOrDefault(String key, T defaultValue, TryGetParamDelegate`1 getter) { }
	// RVA: 0x VA: 0x0
	public static T GetOrDefault(IList`1 keys, T defaultValue, TryGetParamDelegate`1 getter) { }
	// RVA: 0x3e5d8d0 VA: 0x75964758d0
	public Void .ctor() { }
}
```