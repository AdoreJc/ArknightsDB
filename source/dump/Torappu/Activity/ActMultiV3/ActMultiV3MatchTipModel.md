# ActMultiV3MatchTipModel

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `Single m_weight`

- `String m_text`


## Properties

- `String text`

- `Single weightValue`


## Methods

- `String get_text()`

- `Single get_weightValue()`

- `Void LoadData(ActMultiV3TipsData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3MatchTipModel : IHotfixable, IItemWithWeight
{
	private Single m_weight; // 0x10
	private String m_text; // 0x18
	private static DelegateBridge __Hotfix0_get_text; // 0x0
	private static DelegateBridge __Hotfix0_get_weightValue; // 0x8
	private static DelegateBridge __Hotfix0_LoadData; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public String text { get; }
	public Single weightValue { get; }

	// RVA: 0x3130c24 VA: 0x7595748c24
	public String get_text() { }
	// RVA: 0x31328bc VA: 0x759574a8bc
	public Single get_weightValue() { }
	// RVA: 0x3130a74 VA: 0x7595748a74
	public Void LoadData(ActMultiV3TipsData tipData) { }
	// RVA: 0x3130a04 VA: 0x7595748a04
	public Void .ctor() { }
}
```