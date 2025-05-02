# SandboxV2RacerTempItemViewModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Methods

- `Void LoadData(String, SandboxV2RacingData, String, TempRacerInfo)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2RacerTempItemViewModel : SandboxV2RacerModel, IHotfixable
{
	private static DelegateBridge __Hotfix0_get_isTemp; // 0x0
	private static DelegateBridge __Hotfix0_get_isMarked; // 0x8
	private static DelegateBridge __Hotfix0_set_isMarked; // 0x10
	private static DelegateBridge __Hotfix0_get_name; // 0x18
	private static DelegateBridge __Hotfix0_get_medalList; // 0x20
	private static DelegateBridge __Hotfix0_LoadData; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public override Boolean isTemp { get; }
	public override Boolean isMarked { get; set; }
	public override String name { get; }
	public override List`1 medalList { get; }

	// RVA: 0x25f678c VA: 0x7594c0e78c
	public override Boolean get_isTemp() { }
	// RVA: 0x25f67f4 VA: 0x7594c0e7f4
	public override Boolean get_isMarked() { }
	// RVA: 0x25f6858 VA: 0x7594c0e858
	public override Void set_isMarked(Boolean value) { }
	// RVA: 0x25f68d0 VA: 0x7594c0e8d0
	public override String get_name() { }
	// RVA: 0x25f695c VA: 0x7594c0e95c
	public override List`1 get_medalList() { }
	// RVA: 0x25f69c0 VA: 0x7594c0e9c0
	public Void LoadData(String topicId, SandboxV2RacingData gameData, String instId, TempRacerInfo playerRacer) { }
	// RVA: 0x25f6a74 VA: 0x7594c0ea74
	public Void .ctor() { }
}
```