# BattleFinishTargetModel

**Namespace:** `Torappu.Activity.ActMultiV3.BattleFinish`


## Fields

- `Int32 <index>k__BackingField`

- `Single <currentVal>k__BackingField`

- `Single <maxVal>k__BackingField`

- `String <currentStr>k__BackingField`

- `String <maxStr>k__BackingField`

- `Boolean <isComplete>k__BackingField`


## Properties

- `Int32 index`

- `Single currentVal`

- `Single maxVal`

- `String currentStr`

- `String maxStr`

- `Boolean isComplete`

- `Single progress`


## Methods

- `Int32 get_index()`

- `Void set_index(Int32)`

- `Single get_currentVal()`

- `Void set_currentVal(Single)`

- `Single get_maxVal()`

- `Void set_maxVal(Single)`

- `String get_currentStr()`

- `Void set_currentStr(String)`

- `String get_maxStr()`

- `Void set_maxStr(String)`

- `Boolean get_isComplete()`

- `Void set_isComplete(Boolean)`

- `Single get_progress()`

- `Void LoadData(Int32, ProgressRspData)`

- `Void LoadData(Int32, ProgressRspData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3.BattleFinish
public class BattleFinishTargetModel : IHotfixable
{
	private Int32 <index>k__BackingField; // 0x10
	private Single <currentVal>k__BackingField; // 0x14
	private Single <maxVal>k__BackingField; // 0x18
	private String <currentStr>k__BackingField; // 0x20
	private String <maxStr>k__BackingField; // 0x28
	private Boolean <isComplete>k__BackingField; // 0x30
	private static DelegateBridge __Hotfix0_get_index; // 0x0
	private static DelegateBridge __Hotfix0_set_index; // 0x8
	private static DelegateBridge __Hotfix0_get_currentVal; // 0x10
	private static DelegateBridge __Hotfix0_set_currentVal; // 0x18
	private static DelegateBridge __Hotfix0_get_maxVal; // 0x20
	private static DelegateBridge __Hotfix0_set_maxVal; // 0x28
	private static DelegateBridge __Hotfix0_get_currentStr; // 0x30
	private static DelegateBridge __Hotfix0_set_currentStr; // 0x38
	private static DelegateBridge __Hotfix0_get_maxStr; // 0x40
	private static DelegateBridge __Hotfix0_set_maxStr; // 0x48
	private static DelegateBridge __Hotfix0_get_isComplete; // 0x50
	private static DelegateBridge __Hotfix0_set_isComplete; // 0x58
	private static DelegateBridge __Hotfix0_get_progress; // 0x60
	private static DelegateBridge __Hotfix0_LoadData; // 0x68
	private static DelegateBridge __Hotfix1_LoadData; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	public Int32 index { get; set; }
	public Single currentVal { get; set; }
	public Single maxVal { get; set; }
	public String currentStr { get; set; }
	public String maxStr { get; set; }
	public Boolean isComplete { get; set; }
	public Single progress { get; }

	// RVA: 0x3189dc8 VA: 0x75957a1dc8
	public Int32 get_index() { }
	// RVA: 0x3189e30 VA: 0x75957a1e30
	private Void set_index(Int32 value) { }
	// RVA: 0x317e7e4 VA: 0x75957967e4
	public Single get_currentVal() { }
	// RVA: 0x3189eac VA: 0x75957a1eac
	private Void set_currentVal(Single value) { }
	// RVA: 0x317e84c VA: 0x759579684c
	public Single get_maxVal() { }
	// RVA: 0x3189f28 VA: 0x75957a1f28
	private Void set_maxVal(Single value) { }
	// RVA: 0x3189fa4 VA: 0x75957a1fa4
	public String get_currentStr() { }
	// RVA: 0x318a00c VA: 0x75957a200c
	private Void set_currentStr(String value) { }
	// RVA: 0x318a090 VA: 0x75957a2090
	public String get_maxStr() { }
	// RVA: 0x318a0f8 VA: 0x75957a20f8
	private Void set_maxStr(String value) { }
	// RVA: 0x317e77c VA: 0x759579677c
	public Boolean get_isComplete() { }
	// RVA: 0x318a17c VA: 0x75957a217c
	private Void set_isComplete(Boolean value) { }
	// RVA: 0x317e6ac VA: 0x75957966ac
	public Single get_progress() { }
	// RVA: 0x318a1fc VA: 0x75957a21fc
	public Void LoadData(Int32 idx, ProgressRspData targetRspData) { }
	// RVA: 0x318a330 VA: 0x75957a2330
	public Void LoadData(Int32 idx, ProgressRspData targetRspData) { }
	// RVA: 0x318a4b4 VA: 0x75957a24b4
	public Void .ctor() { }
}
```