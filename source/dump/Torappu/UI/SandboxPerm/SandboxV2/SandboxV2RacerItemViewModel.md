# SandboxV2RacerItemViewModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Boolean m_isMarked`

- `String m_name`


## Methods

- `Void LoadData(String, SandboxV2RacingData, String, RacerInfo)`

- `Int32 <>xLuaBaseProxy_CompareTo(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2RacerItemViewModel : SandboxV2RacerModel
{
	private Boolean m_isMarked; // 0x58
	private String m_name; // 0x60
	private List`1 m_medalList; // 0x68
	private static DelegateBridge __Hotfix0_get_isTemp; // 0x0
	private static DelegateBridge __Hotfix0_get_isMarked; // 0x8
	private static DelegateBridge __Hotfix0_set_isMarked; // 0x10
	private static DelegateBridge __Hotfix0_get_name; // 0x18
	private static DelegateBridge __Hotfix0_get_medalList; // 0x20
	private static DelegateBridge __Hotfix0_LoadData; // 0x28
	private static DelegateBridge __Hotfix0_CompareTo; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public override Boolean isTemp { get; }
	public override Boolean isMarked { get; set; }
	public override String name { get; }
	public override List`1 medalList { get; }

	// RVA: 0x25e6d9c VA: 0x7594bfed9c
	public override Boolean get_isTemp() { }
	// RVA: 0x25e6e00 VA: 0x7594bfee00
	public override Boolean get_isMarked() { }
	// RVA: 0x25e6e68 VA: 0x7594bfee68
	public override Void set_isMarked(Boolean value) { }
	// RVA: 0x25e6ee8 VA: 0x7594bfeee8
	public override String get_name() { }
	// RVA: 0x25e6f50 VA: 0x7594bfef50
	public override List`1 get_medalList() { }
	// RVA: 0x25e6fb8 VA: 0x7594bfefb8
	public Void LoadData(String topicId, SandboxV2RacingData gameData, String instId, RacerInfo playerRacer) { }
	// RVA: 0x25e73e0 VA: 0x7594bff3e0
	public override Int32 CompareTo(Object obj) { }
	// RVA: 0x25e7504 VA: 0x7594bff504
	public Void .ctor() { }
	// RVA: 0x25e75c4 VA: 0x7594bff5c4
	private Int32 <>xLuaBaseProxy_CompareTo(Object P0) { }
}
```