# TuningChatViewModel

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `TuningProductBagViewModel bagViewModel`

- `String selectedInvestId`

- `Int32 tryTimesMax`

- `String m_actId`


## Properties

- `Boolean showBag`


## Methods

- `Boolean get_showBag()`

- `Void set_showBag(Boolean)`

- `Void LoadData(String, String)`

- `Void UpdateHidden(String)`

- `TuningChatItemViewModel GetSelectedViewModel()`

- `TuningChatBagItemViewModel GetSelectedBagItemViewModel()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningChatViewModel : IHotfixable
{
	public ListDict`2 invests; // 0x10
	public TuningProductBagViewModel bagViewModel; // 0x18
	public String selectedInvestId; // 0x20
	public Int32 tryTimesMax; // 0x28
	private String m_actId; // 0x30
	private static DelegateBridge __Hotfix0_get_showBag; // 0x0
	private static DelegateBridge __Hotfix0_set_showBag; // 0x8
	private static DelegateBridge __Hotfix0_LoadData; // 0x10
	private static DelegateBridge __Hotfix0_UpdateHidden; // 0x18
	private static DelegateBridge __Hotfix0_GetSelectedViewModel; // 0x20
	private static DelegateBridge __Hotfix0_GetSelectedBagItemViewModel; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public Boolean showBag { get; set; }

	// RVA: 0x231c9b8 VA: 0x75949349b8
	public Boolean get_showBag() { }
	// RVA: 0x231dddc VA: 0x7594935ddc
	public Void set_showBag(Boolean value) { }
	// RVA: 0x231b7f0 VA: 0x75949337f0
	public Void LoadData(String actId, String investId) { }
	// RVA: 0x231f39c VA: 0x759493739c
	public Void UpdateHidden(String actId) { }
	// RVA: 0x231be98 VA: 0x7594933e98
	public TuningChatItemViewModel GetSelectedViewModel() { }
	// RVA: 0x231d618 VA: 0x7594935618
	public TuningChatBagItemViewModel GetSelectedBagItemViewModel() { }
	// RVA: 0x2321160 VA: 0x7594939160
	public Void .ctor() { }
}
```