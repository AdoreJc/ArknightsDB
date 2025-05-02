# STDuelPlayerStatus

**Namespace:** `Torappu.UI.EnemyDuel.Service`


## Fields

- `String uid`

- `String nickName`

- `PlayerAvatarType avatarType`

- `String avatarId`

- `State state`

- `Boolean connLeave`

- `Int64 joinTs`


## Methods

- `Void Read(IStreamReader)`

- `Void Copy(STDuelPlayerStatus)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel.Service
public class STDuelPlayerStatus : IStreamDeserialize
{
	public String uid; // 0x10
	public String nickName; // 0x18
	public PlayerAvatarType avatarType; // 0x20
	public String avatarId; // 0x28
	public State state; // 0x30
	public Boolean connLeave; // 0x34
	public Int64 joinTs; // 0x38


	// RVA: 0x29a8eec VA: 0x7594fc0eec
	public Void Read(IStreamReader from) { }
	// RVA: 0x29a91d4 VA: 0x7594fc11d4
	public Void Copy(STDuelPlayerStatus from) { }
	// RVA: 0x29a9244 VA: 0x7594fc1244
	public Void .ctor() { }
}
```