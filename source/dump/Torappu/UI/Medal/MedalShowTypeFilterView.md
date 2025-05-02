# MedalShowTypeFilterView

**Namespace:** `Torappu.UI.Medal`


## Methods

- `Void add_onShowTypeClicked(Action`1)`

- `Void remove_onShowTypeClicked(Action`1)`

- `Void EventToShowTypeAll()`

- `Void EventToShowTypeAvail()`

- `Void EventToShowTypeNotAvail()`

- `Void Render(MedalBarListShowType)`

- `Void _OnShowTypeClicked(MedalBarListShowType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Medal
public class MedalShowTypeFilterView : MonoBehaviour, IHotfixable
{
	private List`1 _filterBtns; // 0x18
	private Action`1 onShowTypeClicked; // 0x20
	private static DelegateBridge __Hotfix0_add_onShowTypeClicked; // 0x0
	private static DelegateBridge __Hotfix0_remove_onShowTypeClicked; // 0x8
	private static DelegateBridge __Hotfix0_EventToShowTypeAll; // 0x10
	private static DelegateBridge __Hotfix0_EventToShowTypeAvail; // 0x18
	private static DelegateBridge __Hotfix0_EventToShowTypeNotAvail; // 0x20
	private static DelegateBridge __Hotfix0_Render; // 0x28
	private static DelegateBridge __Hotfix0__OnShowTypeClicked; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x27a90a4 VA: 0x7594dc10a4
	public Void add_onShowTypeClicked(Action`1 value) { }
	// RVA: 0x27a9198 VA: 0x7594dc1198
	public Void remove_onShowTypeClicked(Action`1 value) { }
	// RVA: 0x27a928c VA: 0x7594dc128c
	public Void EventToShowTypeAll() { }
	// RVA: 0x27a9398 VA: 0x7594dc1398
	public Void EventToShowTypeAvail() { }
	// RVA: 0x27a9404 VA: 0x7594dc1404
	public Void EventToShowTypeNotAvail() { }
	// RVA: 0x27a9470 VA: 0x7594dc1470
	public Void Render(MedalBarListShowType showType) { }
	// RVA: 0x27a92f8 VA: 0x7594dc12f8
	private Void _OnShowTypeClicked(MedalBarListShowType showType) { }
	// RVA: 0x27a95b0 VA: 0x7594dc15b0
	public Void .ctor() { }
}
```