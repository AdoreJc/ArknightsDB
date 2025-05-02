# ChaosCompInfo

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `ChaosProperty chaos`


## Methods

- `Void SetSelectedChaosId(String)`

- `Boolean <>xLuaBaseProxy_HasNewItem()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ChaosCompInfo : ActArchiveCompInfo
{
	public ChaosProperty chaos; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_SetSelectedChaosId; // 0x8
	private static DelegateBridge __Hotfix0_LoadData; // 0x10
	private static DelegateBridge __Hotfix0_ApplyDataBundle; // 0x18
	private static DelegateBridge __Hotfix0_NotifyUpdate; // 0x20
	private static DelegateBridge __Hotfix0_IsValid; // 0x28
	private static DelegateBridge __Hotfix0_HasNewItem; // 0x30


	// RVA: 0x30427c4 VA: 0x759565a7c4
	public Void .ctor(ActArchiveInfo archiveInfo) { }
	// RVA: 0x304284c VA: 0x759565a84c
	public Void SetSelectedChaosId(String chaosId) { }
	// RVA: 0x3042930 VA: 0x759565a930
	public override Void LoadData(String archiveId) { }
	// RVA: 0x3042a6c VA: 0x759565aa6c
	public override Void ApplyDataBundle(DataBundle data) { }
	// RVA: 0x3042b1c VA: 0x759565ab1c
	public override Void NotifyUpdate() { }
	// RVA: 0x3042bc4 VA: 0x759565abc4
	public override Boolean IsValid() { }
	// RVA: 0x3042c50 VA: 0x759565ac50
	public override Boolean HasNewItem() { }
	// RVA: 0x3042d08 VA: 0x759565ad08
	private Boolean <>xLuaBaseProxy_HasNewItem() { }
}
```