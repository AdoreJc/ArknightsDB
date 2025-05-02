# AnimationData

**Namespace:** ` `


## Fields

- `String animKey`

- `String animName`

- `Boolean loop`

- `Single speed`

- `Boolean ignoreMissing`

- `Single time`

- `Boolean valid`


## Methods

- `String GetAnimName()`

- `String GetAnimNameWithPrefix(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AnimationData
{
	public String animKey; // 0x10
	public String animName; // 0x18
	public Boolean loop; // 0x20
	public Single speed; // 0x24
	public Boolean ignoreMissing; // 0x28
	public Single time; // 0x2c
	public Boolean valid; // 0x30


	// RVA: 0x3f5c734 VA: 0x7596574734
	public String GetAnimName() { }
	// RVA: 0x3f5c6ec VA: 0x75965746ec
	public String GetAnimNameWithPrefix(String prefix) { }
	// RVA: 0x3f5d16c VA: 0x759657516c
	public override String ToString() { }
	// RVA: 0x3f5d42c VA: 0x759657542c
	public Void .ctor() { }
}
```