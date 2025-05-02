# PlayerAvatarGroupViewModel

**Namespace:** `Torappu.UI.PlayerAvatar`


## Fields

- `PlayerAvatarGroupData data`


## Properties

- `PlayerAvatarGroupType groupType`


## Methods

- `PlayerAvatarGroupType get_groupType()`

- `Void AddAvatar(PlayerAvatarItemViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.PlayerAvatar
public class PlayerAvatarGroupViewModel : IHotfixable
{
	public PlayerAvatarGroupData data; // 0x10
	public List`1 avatarItemList; // 0x18
	private static DelegateBridge __Hotfix0_get_groupType; // 0x0
	private static DelegateBridge __Hotfix0_AddAvatar; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public PlayerAvatarGroupType groupType { get; }

	// RVA: 0x2725384 VA: 0x7594d3d384
	public PlayerAvatarGroupType get_groupType() { }
	// RVA: 0x27253fc VA: 0x7594d3d3fc
	public Void AddAvatar(PlayerAvatarItemViewModel viewModel) { }
	// RVA: 0x27254f8 VA: 0x7594d3d4f8
	public Void .ctor() { }
}
```