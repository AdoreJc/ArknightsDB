# FifthAnnivExploreValueViewModel

**Namespace:** `Torappu.UI.FifthAnnivMainline`


## Fields

- `Int32 minValue`

- `Int32 maxValue`

- `Int32 deltaValue`

- `Boolean hasDeltaValue`

- `Boolean showDeltaValue`

- `Int32 <curValue>k__BackingField`


## Properties

- `Int32 curValue`

- `Int32 displayCurValue`

- `Single curNormalizedValue`

- `Single beforeDeltaNormalizedValue`


## Methods

- `Void set_curValue(Int32)`

- `Int32 get_curValue()`

- `Int32 get_displayCurValue()`

- `Single get_curNormalizedValue()`

- `Single get_beforeDeltaNormalizedValue()`

- `Void LoadData(Int32, Boolean, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.FifthAnnivMainline
public class FifthAnnivExploreValueViewModel : IHotfixable
{
	public Int32 minValue; // 0x10
	public Int32 maxValue; // 0x14
	public Int32 deltaValue; // 0x18
	public Boolean hasDeltaValue; // 0x1c
	public Boolean showDeltaValue; // 0x1d
	private Int32 <curValue>k__BackingField; // 0x20
	private static DelegateBridge __Hotfix0_set_curValue; // 0x0
	private static DelegateBridge __Hotfix0_get_curValue; // 0x8
	private static DelegateBridge __Hotfix0_get_displayCurValue; // 0x10
	private static DelegateBridge __Hotfix0_get_curNormalizedValue; // 0x18
	private static DelegateBridge __Hotfix0_get_beforeDeltaNormalizedValue; // 0x20
	private static DelegateBridge __Hotfix0_LoadData; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	private Int32 curValue { get; set; }
	public Int32 displayCurValue { get; }
	public Single curNormalizedValue { get; }
	public Single beforeDeltaNormalizedValue { get; }

	// RVA: 0x291d28c VA: 0x7594f3528c
	public Void set_curValue(Int32 value) { }
	// RVA: 0x291d308 VA: 0x7594f35308
	private Int32 get_curValue() { }
	// RVA: 0x291d1f8 VA: 0x7594f351f8
	public Int32 get_displayCurValue() { }
	// RVA: 0x291d370 VA: 0x7594f35370
	public Single get_curNormalizedValue() { }
	// RVA: 0x291d420 VA: 0x7594f35420
	public Single get_beforeDeltaNormalizedValue() { }
	// RVA: 0x291cddc VA: 0x7594f34ddc
	public Void LoadData(Int32 curValue, Boolean hasDeltaValue, Int32 deltaValue) { }
	// RVA: 0x291cd6c VA: 0x7594f34d6c
	public Void .ctor() { }
}
```