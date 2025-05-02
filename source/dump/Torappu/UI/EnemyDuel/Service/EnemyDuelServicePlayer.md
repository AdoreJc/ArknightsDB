# EnemyDuelServicePlayer

**Namespace:** `Torappu.UI.EnemyDuel.Service`


## Fields

- `String uid`

- `String avatarId`

- `String nickName`

- `PlayerAvatarType avatarType`

- `Boolean haveShield`


## Methods

- `Void Read(IStreamReader)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel.Service
public class EnemyDuelServicePlayer : IStreamDeserialize
{
	public String uid; // 0x10
	public String avatarId; // 0x18
	public String nickName; // 0x20
	public PlayerAvatarType avatarType; // 0x28
	public Boolean haveShield; // 0x2c


	// RVA: 0x29a948c VA: 0x7594fc148c
	public Void Read(IStreamReader from) { }
	// RVA: 0x29a96b0 VA: 0x7594fc16b0
	public Void .ctor() { }
}
```