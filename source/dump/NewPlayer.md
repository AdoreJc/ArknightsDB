# NewPlayer

**Namespace:** ` `


## Fields

- `String uid`

- `SByte index`

- `String buffId`

- `Int32 fail`


## Methods

- `Void Read(IStreamReader)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class NewPlayer : IStreamDeserialize
{
	public String uid; // 0x10
	public SByte index; // 0x18
	public List`1 squad; // 0x20
	public String buffId; // 0x28
	public Int32 fail; // 0x30


	// RVA: 0x359874c VA: 0x7595bb074c
	public Void Read(IStreamReader from) { }
	// RVA: 0x3598974 VA: 0x7595bb0974
	public Void .ctor() { }
}
```