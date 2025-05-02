# NameCardV2AssistModuleModel

**Namespace:** `Torappu.UI.Friend`


## Fields

- `Boolean isSelf`

- `Style style`


## Methods

- `Void SwitchStyle()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class NameCardV2AssistModuleModel : NameCardV2RemovableModuleBaseModel
{
	public Boolean isSelf; // 0x49
	public List`1 sharedCharDataSelf; // 0x50
	public List`1 sharedCharDataFriend; // 0x58
	public Style style; // 0x60
	private static DelegateBridge __Hotfix0_get_moduleSubType; // 0x0
	private static DelegateBridge __Hotfix0_OnLoadFriendData; // 0x8
	private static DelegateBridge __Hotfix0_OnLoadSelfData; // 0x10
	private static DelegateBridge __Hotfix0_OnRefreshSelfData; // 0x18
	private static DelegateBridge __Hotfix0_SwitchStyle; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override NameCardV2ModuleSubType moduleSubType { get; }

	// RVA: 0x28c3870 VA: 0x7594edb870
	public override NameCardV2ModuleSubType get_moduleSubType() { }
	// RVA: 0x28c38d8 VA: 0x7594edb8d8
	protected override Void OnLoadFriendData(FriendDataWithNameCard data) { }
	// RVA: 0x28c3968 VA: 0x7594edb968
	protected override Void OnLoadSelfData() { }
	// RVA: 0x28c39cc VA: 0x7594edb9cc
	protected override Void OnRefreshSelfData() { }
	// RVA: 0x28c3a7c VA: 0x7594edba7c
	public Void SwitchStyle() { }
	// RVA: 0x28c3b00 VA: 0x7594edbb00
	public Void .ctor() { }
}
```