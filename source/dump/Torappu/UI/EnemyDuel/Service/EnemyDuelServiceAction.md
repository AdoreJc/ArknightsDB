# EnemyDuelServiceAction

**Namespace:** `Torappu.UI.EnemyDuel.Service`


## Fields

- `EnemyDuelServiceOperate operate`

- `EnemyDuelCharacterAction action`

- `Signiture sig`


## Methods

- `Void Read(IStreamReader)`

- `Void Write(IStreamWriter)`

- `Void OnAllocate()`

- `Void OnRecycle()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel.Service
public class EnemyDuelServiceAction : IStreamSerialize, IStreamDeserialize, IReusable
{
	private const Int32 CHARATCER_INT_PARAM_CNT; // 0x0
	private const Int32 CHARATCER_STRING_PARAM_CNT; // 0x0
	public EnemyDuelServiceOperate operate; // 0x10
	public EnemyDuelCharacterAction action; // 0x14
	public Signiture sig; // 0x18


	// RVA: 0x29a995c VA: 0x7594fc195c
	public Void Read(IStreamReader from) { }
	// RVA: 0x29a9c00 VA: 0x7594fc1c00
	public Void Write(IStreamWriter to) { }
	// RVA: 0x29a9eb8 VA: 0x7594fc1eb8
	public Void OnAllocate() { }
	// RVA: 0x29a9ebc VA: 0x7594fc1ebc
	public Void OnRecycle() { }
	// RVA: 0x29a7328 VA: 0x7594fbf328
	public Void .ctor() { }
}
```