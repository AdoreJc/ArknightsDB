# MedalDB

**Namespace:** `Torappu`


## Methods

- `MedalPerData GetMedalDataById(String)`

- `MedalGroupData GetMedalGroupById(String)`

- `Boolean CheckIfAdvancedMedal(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class MedalDB : ConstTable`2
{
	private Dictionary`2 m_medalDataMap; // 0x60
	private Dictionary`2 m_medalGroupMap; // 0x68
	private Dictionary`2 m_advMedalToNormal; // 0x70
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_GetMedalDataById; // 0x8
	private static DelegateBridge __Hotfix0_GetMedalGroupById; // 0x10
	private static DelegateBridge __Hotfix0_CheckIfAdvancedMedal; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x31f3240 VA: 0x759580b240
	protected override Void OnInit() { }
	// RVA: 0x31f3578 VA: 0x759580b578
	public MedalPerData GetMedalDataById(String id) { }
	// RVA: 0x31f3638 VA: 0x759580b638
	public MedalGroupData GetMedalGroupById(String id) { }
	// RVA: 0x31f36f8 VA: 0x759580b6f8
	public Boolean CheckIfAdvancedMedal(String medalId) { }
	// RVA: 0x31f37b0 VA: 0x759580b7b0
	public Void .ctor() { }
}
```