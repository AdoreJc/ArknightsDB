# NameCardV2SignModuleModel

**Namespace:** `Torappu.UI.Friend`


## Fields

- `String resume`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class NameCardV2SignModuleModel : NameCardV2RemovableModuleBaseModel
{
	public String resume; // 0x50
	private static DelegateBridge __Hotfix0_get_moduleSubType; // 0x0
	private static DelegateBridge __Hotfix0_OnLoadFriendData; // 0x8
	private static DelegateBridge __Hotfix0_OnLoadSelfData; // 0x10
	private static DelegateBridge __Hotfix0_OnRefreshSelfData; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override NameCardV2ModuleSubType moduleSubType { get; }

	// RVA: 0x28c3560 VA: 0x7594edb560
	public override NameCardV2ModuleSubType get_moduleSubType() { }
	// RVA: 0x28c35c8 VA: 0x7594edb5c8
	protected override Void OnLoadFriendData(FriendDataWithNameCard data) { }
	// RVA: 0x28c36a4 VA: 0x7594edb6a4
	protected override Void OnLoadSelfData() { }
	// RVA: 0x28c3708 VA: 0x7594edb708
	protected override Void OnRefreshSelfData() { }
	// RVA: 0x28c3800 VA: 0x7594edb800
	public Void .ctor() { }
}
```