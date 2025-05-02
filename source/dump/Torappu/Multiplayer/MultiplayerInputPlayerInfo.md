# MultiplayerInputPlayerInfo

**Namespace:** `Torappu.Multiplayer`


## Fields

- `Boolean isMentor`

- `String nickName`

- `String uid`

- `Int32 level`

- `AvatarInfo avatarInfo`

- `String secretary`

- `String secretarySkinId`

- `String nameCardSkinId`

- `Int32 nameCardSkinTmpl`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Multiplayer
public class MultiplayerInputPlayerInfo : IHotfixable
{
	public Boolean isMentor; // 0x10
	public List`1 titleList; // 0x18
	public String nickName; // 0x20
	public String uid; // 0x28
	public Int32 level; // 0x30
	public AvatarInfo avatarInfo; // 0x38
	public String secretary; // 0x40
	public String secretarySkinId; // 0x48
	public String nameCardSkinId; // 0x50
	public Int32 nameCardSkinTmpl; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0


	// RVA: 0x358dfbc VA: 0x7595ba5fbc
	public Void .ctor() { }
}
```