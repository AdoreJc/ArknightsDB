# PlayerAvatarItemViewModel

**Namespace:** `Torappu.UI.PlayerAvatar`


## Fields

- `String assistantId`

- `PlayerAvatarPerData data`

- `Boolean isSelect`


## Properties

- `String avatarId`

- `Boolean isAssistant`

- `Int32 sortId`

- `PlayerAvatarGroupType avatarType`


## Methods

- `String get_avatarId()`

- `Void set_avatarId(String)`

- `Boolean get_isAssistant()`

- `Int32 get_sortId()`

- `PlayerAvatarGroupType get_avatarType()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.PlayerAvatar
public class PlayerAvatarItemViewModel : IHotfixable
{
	private String assistantId; // 0x10
	public PlayerAvatarPerData data; // 0x18
	public Boolean isSelect; // 0x20
	private static DelegateBridge __Hotfix0_get_avatarId; // 0x0
	private static DelegateBridge __Hotfix0_set_avatarId; // 0x8
	private static DelegateBridge __Hotfix0_get_isAssistant; // 0x10
	private static DelegateBridge __Hotfix0_get_sortId; // 0x18
	private static DelegateBridge __Hotfix0_get_avatarType; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public String avatarId { get; set; }
	public Boolean isAssistant { get; }
	public Int32 sortId { get; }
	public PlayerAvatarGroupType avatarType { get; }

	// RVA: 0x2723f24 VA: 0x7594d3bf24
	public String get_avatarId() { }
	// RVA: 0x27266e4 VA: 0x7594d3e6e4
	public Void set_avatarId(String value) { }
	// RVA: 0x2723fd8 VA: 0x7594d3bfd8
	public Boolean get_isAssistant() { }
	// RVA: 0x2725728 VA: 0x7594d3d728
	public Int32 get_sortId() { }
	// RVA: 0x2723eac VA: 0x7594d3beac
	public PlayerAvatarGroupType get_avatarType() { }
	// RVA: 0x2725090 VA: 0x7594d3d090
	public Void .ctor() { }
}
```