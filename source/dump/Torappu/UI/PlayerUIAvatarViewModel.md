# PlayerUIAvatarViewModel

**Namespace:** `Torappu.UI`


## Fields

- `AvatarInfo avatarInfo`

- `String dynAvatarId`


## Methods

- `Void LoadData(AvatarInfo)`

- `Void LoadData(PlayerAvatarItemViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class PlayerUIAvatarViewModel : IHotfixable
{
	public AvatarInfo avatarInfo; // 0x10
	public String dynAvatarId; // 0x18
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix1_LoadData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2278e80 VA: 0x7594890e80
	public Void LoadData(AvatarInfo avatarInfo) { }
	// RVA: 0x2278f84 VA: 0x7594890f84
	public Void LoadData(PlayerAvatarItemViewModel model) { }
	// RVA: 0x22790d8 VA: 0x75948910d8
	public Void .ctor() { }
}
```