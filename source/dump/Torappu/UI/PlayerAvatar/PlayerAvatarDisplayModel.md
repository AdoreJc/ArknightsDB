# PlayerAvatarDisplayModel

**Namespace:** `Torappu.UI.PlayerAvatar`


## Fields

- `AvatarInfo avatarInfo`

- `Int32 level`

- `String avatarName`

- `String avatarUsage`


## Methods

- `Void FillDataByItem(UIItemViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.PlayerAvatar
public class PlayerAvatarDisplayModel : IHotfixable
{
	public AvatarInfo avatarInfo; // 0x10
	public Int32 level; // 0x18
	public String avatarName; // 0x20
	public String avatarUsage; // 0x28
	private static DelegateBridge __Hotfix0_FillDataByItem; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2724db4 VA: 0x7594d3cdb4
	public Void FillDataByItem(UIItemViewModel model) { }
	// RVA: 0x2724ecc VA: 0x7594d3cecc
	public Void .ctor() { }
}
```