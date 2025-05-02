# CarvingTopInfoViewModel

**Namespace:** `Torappu.UI.Carving`


## Fields

- `Int32 <curRound>k__BackingField`

- `Int32 <targetScore>k__BackingField`

- `Boolean <inUnlimitedMode>k__BackingField`


## Properties

- `Int32 curRound`

- `Int32 targetScore`

- `Boolean inUnlimitedMode`


## Methods

- `Int32 get_curRound()`

- `Void set_curRound(Int32)`

- `Int32 get_targetScore()`

- `Void set_targetScore(Int32)`

- `Boolean get_inUnlimitedMode()`

- `Void set_inUnlimitedMode(Boolean)`

- `Void LoadData(PlayerAct35SideCarving, Act35SideData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingTopInfoViewModel : IHotfixable
{
	private Int32 <curRound>k__BackingField; // 0x10
	private Int32 <targetScore>k__BackingField; // 0x14
	private Boolean <inUnlimitedMode>k__BackingField; // 0x18
	private static DelegateBridge __Hotfix0_get_curRound; // 0x0
	private static DelegateBridge __Hotfix0_set_curRound; // 0x8
	private static DelegateBridge __Hotfix0_get_targetScore; // 0x10
	private static DelegateBridge __Hotfix0_set_targetScore; // 0x18
	private static DelegateBridge __Hotfix0_get_inUnlimitedMode; // 0x20
	private static DelegateBridge __Hotfix0_set_inUnlimitedMode; // 0x28
	private static DelegateBridge __Hotfix0_LoadData; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public Int32 curRound { get; set; }
	public Int32 targetScore { get; set; }
	public Boolean inUnlimitedMode { get; set; }

	// RVA: 0x2da06ec VA: 0x75953b86ec
	public Int32 get_curRound() { }
	// RVA: 0x2da0894 VA: 0x75953b8894
	private Void set_curRound(Int32 value) { }
	// RVA: 0x2da07bc VA: 0x75953b87bc
	public Int32 get_targetScore() { }
	// RVA: 0x2da0910 VA: 0x75953b8910
	private Void set_targetScore(Int32 value) { }
	// RVA: 0x2da0754 VA: 0x75953b8754
	public Boolean get_inUnlimitedMode() { }
	// RVA: 0x2da098c VA: 0x75953b898c
	private Void set_inUnlimitedMode(Boolean value) { }
	// RVA: 0x2d97c1c VA: 0x75953afc1c
	public Void LoadData(PlayerAct35SideCarving carving, Act35SideData actData) { }
	// RVA: 0x2d97bac VA: 0x75953afbac
	public Void .ctor() { }
}
```