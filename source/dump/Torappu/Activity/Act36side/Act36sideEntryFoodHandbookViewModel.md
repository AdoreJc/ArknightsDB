# Act36sideEntryFoodHandbookViewModel

**Namespace:** `Torappu.Activity.Act36side`


## Fields

- `DateTime m_actRewardEndTs`

- `Status currStatus`


## Methods

- `Void RefreshPlayerData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act36side
public class Act36sideEntryFoodHandbookViewModel : TemplateActivityViewModel, IHotfixable
{
	private DateTime m_actRewardEndTs; // 0x20
	public Status currStatus; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_RefreshPlayerData; // 0x8


	// RVA: 0x3243424 VA: 0x759585b424
	public Void .ctor(Object param) { }
	// RVA: 0x3242a5c VA: 0x759585aa5c
	public Void RefreshPlayerData() { }
}
```