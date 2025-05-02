# TrapCompInfo

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `TrapProperty trap`

- `String m_cachedArchiveId`


## Methods

- `Void SetSelectedTrapItem(String)`

- `Boolean <>xLuaBaseProxy_HasNewItem()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class TrapCompInfo : ActArchiveCompInfo
{
	public TrapProperty trap; // 0x18
	private String m_cachedArchiveId; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0_SetSelectedTrapItem; // 0x10
	private static DelegateBridge __Hotfix0_ApplyDataBundle; // 0x18
	private static DelegateBridge __Hotfix0_IsValid; // 0x20
	private static DelegateBridge __Hotfix0_NotifyUpdate; // 0x28
	private static DelegateBridge __Hotfix0_HasNewItem; // 0x30


	// RVA: 0x309066c VA: 0x75956a866c
	public Void .ctor(ActArchiveInfo archiveInfo) { }
	// RVA: 0x30906f4 VA: 0x75956a86f4
	public override Void LoadData(String archiveId) { }
	// RVA: 0x3090830 VA: 0x75956a8830
	public Void SetSelectedTrapItem(String trapId) { }
	// RVA: 0x30909cc VA: 0x75956a89cc
	public override Void ApplyDataBundle(DataBundle data) { }
	// RVA: 0x3090a7c VA: 0x75956a8a7c
	public override Boolean IsValid() { }
	// RVA: 0x3090b08 VA: 0x75956a8b08
	public override Void NotifyUpdate() { }
	// RVA: 0x3090bb0 VA: 0x75956a8bb0
	public override Boolean HasNewItem() { }
	// RVA: 0x3090ca0 VA: 0x75956a8ca0
	private Boolean <>xLuaBaseProxy_HasNewItem() { }
}
```