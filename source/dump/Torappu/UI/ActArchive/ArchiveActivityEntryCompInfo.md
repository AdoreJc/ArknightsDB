# ArchiveActivityEntryCompInfo

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `ArchiveActivityEntryProperty property`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveActivityEntryCompInfo : ActArchiveCompInfo
{
	public ArchiveActivityEntryProperty property; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0_ApplyDataBundle; // 0x10
	private static DelegateBridge __Hotfix0_IsValid; // 0x18
	private static DelegateBridge __Hotfix0_NotifyUpdate; // 0x20


	// RVA: 0x3032cc4 VA: 0x759564acc4
	public Void .ctor(ActArchiveInfo archiveInfo) { }
	// RVA: 0x3032d4c VA: 0x759564ad4c
	public override Void LoadData(String archiveId) { }
	// RVA: 0x3032e44 VA: 0x759564ae44
	public override Void ApplyDataBundle(DataBundle data) { }
	// RVA: 0x3032ebc VA: 0x759564aebc
	public override Boolean IsValid() { }
	// RVA: 0x3032f2c VA: 0x759564af2c
	public override Void NotifyUpdate() { }
}
```