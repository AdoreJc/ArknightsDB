# BuffCompInfo

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `BuffProperty buff`


## Methods

- `Void SetSelectedBuffItem(String)`

- `Boolean <>xLuaBaseProxy_HasNewItem()`

- `Boolean <>xLuaBaseProxy_IsUnlocked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class BuffCompInfo : ActArchiveCompInfo
{
	public BuffProperty buff; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0_SetSelectedBuffItem; // 0x10
	private static DelegateBridge __Hotfix0_ApplyDataBundle; // 0x18
	private static DelegateBridge __Hotfix0_IsValid; // 0x20
	private static DelegateBridge __Hotfix0_NotifyUpdate; // 0x28
	private static DelegateBridge __Hotfix0_HasNewItem; // 0x30
	private static DelegateBridge __Hotfix0_IsUnlocked; // 0x38


	// RVA: 0x3039f40 VA: 0x7595651f40
	public Void .ctor(ActArchiveInfo archiveInfo) { }
	// RVA: 0x3039fc8 VA: 0x7595651fc8
	public override Void LoadData(String archiveId) { }
	// RVA: 0x303a104 VA: 0x7595652104
	public Void SetSelectedBuffItem(String buffId) { }
	// RVA: 0x303a2a0 VA: 0x75956522a0
	public override Void ApplyDataBundle(DataBundle data) { }
	// RVA: 0x303a350 VA: 0x7595652350
	public override Boolean IsValid() { }
	// RVA: 0x303a3dc VA: 0x75956523dc
	public override Void NotifyUpdate() { }
	// RVA: 0x303a484 VA: 0x7595652484
	public override Boolean HasNewItem() { }
	// RVA: 0x303a5c8 VA: 0x75956525c8
	public override Boolean IsUnlocked() { }
	// RVA: 0x303a704 VA: 0x7595652704
	private Boolean <>xLuaBaseProxy_HasNewItem() { }
	// RVA: 0x303a70c VA: 0x759565270c
	private Boolean <>xLuaBaseProxy_IsUnlocked() { }
}
```