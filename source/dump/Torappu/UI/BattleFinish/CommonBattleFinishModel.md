# CommonBattleFinishModel

**Namespace:** `Torappu.UI.BattleFinish`


## Fields

- `BattleInfoViewModel battleInfoModel`

- `DropInfoGroupViewModel dropInfoModel`

- `ControlModel expBarControlModel`

- `Boolean <isInited>k__BackingField`


## Properties

- `Boolean isInited`


## Methods

- `Boolean get_isInited()`

- `Void set_isInited(Boolean)`

- `Void LoadData(CommonFinishBattleResponse)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BattleFinish
public class CommonBattleFinishModel : IHotfixable
{
	public BattleInfoViewModel battleInfoModel; // 0x10
	public DropInfoGroupViewModel dropInfoModel; // 0x18
	public List`1 pryDropInfoModels; // 0x20
	public ControlModel expBarControlModel; // 0x28
	private Boolean <isInited>k__BackingField; // 0x30
	private static DelegateBridge __Hotfix0_get_isInited; // 0x0
	private static DelegateBridge __Hotfix0_set_isInited; // 0x8
	private static DelegateBridge __Hotfix0_LoadData; // 0x10
	private static DelegateBridge __Hotfix0_FindCharsInDropItems; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Boolean isInited { get; set; }

	// RVA: 0x2e8a680 VA: 0x75954a2680
	public Boolean get_isInited() { }
	// RVA: 0x2e8a6e8 VA: 0x75954a26e8
	private Void set_isInited(Boolean value) { }
	// RVA: 0x2e8a768 VA: 0x75954a2768
	public Void LoadData(CommonFinishBattleResponse response) { }
	// RVA: 0x2e8b238 VA: 0x75954a3238
	public List`1 FindCharsInDropItems() { }
	// RVA: 0x2e8b590 VA: 0x75954a3590
	public Void .ctor() { }
}
```