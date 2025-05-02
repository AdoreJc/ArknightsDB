# Act6FunZoneMapBgPluginViewModel

**Namespace:** `Torappu.Activity.Act6fun`


## Fields

- `Boolean <isNormalBg>k__BackingField`

- `Boolean <isBonusBg>k__BackingField`

- `Int32 m_achieveTotalCount`

- `Int32 m_curAchieveCount`


## Properties

- `Boolean isNormalBg`

- `Boolean isBonusBg`


## Methods

- `Boolean get_isNormalBg()`

- `Void set_isNormalBg(Boolean)`

- `Boolean get_isBonusBg()`

- `Void set_isBonusBg(Boolean)`

- `Void LoadData(Act6FunData)`

- `Void RefreshByPlayerData(PlayerActFun6)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act6fun
public class Act6FunZoneMapBgPluginViewModel : IHotfixable
{
	private Boolean <isNormalBg>k__BackingField; // 0x10
	private Boolean <isBonusBg>k__BackingField; // 0x11
	private Int32 m_achieveTotalCount; // 0x14
	private Int32 m_curAchieveCount; // 0x18
	private static DelegateBridge __Hotfix0_get_isNormalBg; // 0x0
	private static DelegateBridge __Hotfix0_set_isNormalBg; // 0x8
	private static DelegateBridge __Hotfix0_get_isBonusBg; // 0x10
	private static DelegateBridge __Hotfix0_set_isBonusBg; // 0x18
	private static DelegateBridge __Hotfix0_LoadData; // 0x20
	private static DelegateBridge __Hotfix0_RefreshByPlayerData; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public Boolean isNormalBg { get; set; }
	public Boolean isBonusBg { get; set; }

	// RVA: 0x31b12f8 VA: 0x75957c92f8
	public Boolean get_isNormalBg() { }
	// RVA: 0x31b1360 VA: 0x75957c9360
	private Void set_isNormalBg(Boolean value) { }
	// RVA: 0x31b13e0 VA: 0x75957c93e0
	public Boolean get_isBonusBg() { }
	// RVA: 0x31b1448 VA: 0x75957c9448
	private Void set_isBonusBg(Boolean value) { }
	// RVA: 0x31b14c8 VA: 0x75957c94c8
	public Void LoadData(Act6FunData act6FunData) { }
	// RVA: 0x31b1554 VA: 0x75957c9554
	public Void RefreshByPlayerData(PlayerActFun6 playerActFun6Data) { }
	// RVA: 0x31b173c VA: 0x75957c973c
	public Void .ctor() { }
}
```