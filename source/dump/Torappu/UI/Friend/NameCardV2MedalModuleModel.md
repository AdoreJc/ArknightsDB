# NameCardV2MedalModuleModel

**Namespace:** `Torappu.UI.Friend`


## Fields

- `FriendMedalBoard medalBoard`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class NameCardV2MedalModuleModel : NameCardV2RemovableModuleBaseModel
{
	public FriendMedalBoard medalBoard; // 0x50
	private static DelegateBridge __Hotfix0_get_moduleSubType; // 0x0
	private static DelegateBridge __Hotfix0_OnLoadFriendData; // 0x8
	private static DelegateBridge __Hotfix0_OnLoadSelfData; // 0x10
	private static DelegateBridge __Hotfix0_OnRefreshSelfData; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override NameCardV2ModuleSubType moduleSubType { get; }

	// RVA: 0x28c3b70 VA: 0x7594edbb70
	public override NameCardV2ModuleSubType get_moduleSubType() { }
	// RVA: 0x28c3bd8 VA: 0x7594edbbd8
	protected override Void OnLoadFriendData(FriendDataWithNameCard data) { }
	// RVA: 0x28c3c64 VA: 0x7594edbc64
	protected override Void OnLoadSelfData() { }
	// RVA: 0x28c3cc8 VA: 0x7594edbcc8
	protected override Void OnRefreshSelfData() { }
	// RVA: 0x28c44b4 VA: 0x7594edc4b4
	public Void .ctor() { }
}
```