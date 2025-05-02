# CapsuleCompInfo

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `CapsuleProperty capsule`


## Methods

- `Void SetSelectedCapsuleItem(String)`

- `Boolean <>xLuaBaseProxy_HasNewItem()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class CapsuleCompInfo : ActArchiveCompInfo
{
	public CapsuleProperty capsule; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0_SetSelectedCapsuleItem; // 0x10
	private static DelegateBridge __Hotfix0_ApplyDataBundle; // 0x18
	private static DelegateBridge __Hotfix0_IsValid; // 0x20
	private static DelegateBridge __Hotfix0_NotifyUpdate; // 0x28
	private static DelegateBridge __Hotfix0_HasNewItem; // 0x30


	// RVA: 0x303c8b4 VA: 0x75956548b4
	public Void .ctor(ActArchiveInfo archiveInfo) { }
	// RVA: 0x303c93c VA: 0x759565493c
	public override Void LoadData(String archiveId) { }
	// RVA: 0x303ca78 VA: 0x7595654a78
	public Void SetSelectedCapsuleItem(String capsuleId) { }
	// RVA: 0x303cc14 VA: 0x7595654c14
	public override Void ApplyDataBundle(DataBundle data) { }
	// RVA: 0x303ccc4 VA: 0x7595654cc4
	public override Boolean IsValid() { }
	// RVA: 0x303cd50 VA: 0x7595654d50
	public override Void NotifyUpdate() { }
	// RVA: 0x303cdf8 VA: 0x7595654df8
	public override Boolean HasNewItem() { }
	// RVA: 0x303cf3c VA: 0x7595654f3c
	private Boolean <>xLuaBaseProxy_HasNewItem() { }
}
```