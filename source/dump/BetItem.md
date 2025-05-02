# BetItem

**Namespace:** ` `


## Fields

- `String id`

- `EnemyDuelChoiceSide side`

- `Boolean allin`

- `Int32 streak`

- `Int64 updateTs`


## Methods

- `Void Read(IStreamReader)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class BetItem : IStreamDeserialize
{
	public String id; // 0x10
	public EnemyDuelChoiceSide side; // 0x18
	public Boolean allin; // 0x1c
	public Int32 streak; // 0x20
	public Int64 updateTs; // 0x28


	// RVA: 0x29aa828 VA: 0x7594fc2828
	public Void Read(IStreamReader from) { }
	// RVA: 0x29aaa68 VA: 0x7594fc2a68
	public Void .ctor() { }
}
```