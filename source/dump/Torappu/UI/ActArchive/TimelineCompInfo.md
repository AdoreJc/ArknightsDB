# TimelineCompInfo

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `TimelineProperty timeline`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class TimelineCompInfo : ActArchiveCompInfo
{
	public TimelineProperty timeline; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0_ApplyDataBundle; // 0x10
	private static DelegateBridge __Hotfix0_IsValid; // 0x18
	private static DelegateBridge __Hotfix0_NotifyUpdate; // 0x20


	// RVA: 0x3089c68 VA: 0x75956a1c68
	public Void .ctor(ActArchiveInfo archiveInfo) { }
	// RVA: 0x3089cf0 VA: 0x75956a1cf0
	public override Void LoadData(String archiveId) { }
	// RVA: 0x3089e28 VA: 0x75956a1e28
	public override Void ApplyDataBundle(DataBundle data) { }
	// RVA: 0x3089ea0 VA: 0x75956a1ea0
	public override Boolean IsValid() { }
	// RVA: 0x3089f10 VA: 0x75956a1f10
	public override Void NotifyUpdate() { }
}
```