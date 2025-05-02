# EnemyDuelServiceStepData

**Namespace:** `Torappu.UI.EnemyDuel.Service`


## Fields

- `Int32 index`

- `Int32 duration`

- `Int32 checkSeq`

- `Int32 round`


## Methods

- `Void Read(IStreamReader)`

- `Void OnAllocate()`

- `Void OnRecycle()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel.Service
public class EnemyDuelServiceStepData : IStreamDeserialize, IReusable
{
	public Int32 index; // 0x10
	public Int32 duration; // 0x14
	public List`1 actions; // 0x18
	public Int32 checkSeq; // 0x20
	public Int32 round; // 0x24


	// RVA: 0x29a7294 VA: 0x7594fbf294
	public Void .ctor() { }
	// RVA: 0x29a9f18 VA: 0x7594fc1f18
	public Void Read(IStreamReader from) { }
	// RVA: 0x29aa180 VA: 0x7594fc2180
	public Void OnAllocate() { }
	// RVA: 0x29aa184 VA: 0x7594fc2184
	public Void OnRecycle() { }
}
```