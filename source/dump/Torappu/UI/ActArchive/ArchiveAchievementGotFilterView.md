# ArchiveAchievementGotFilterView

**Namespace:** `Torappu.UI.ActArchive`


## Methods

- `Void set_onGotTypeChanged(Action`1)`

- `Void Render(ArchiveAchievementModel)`

- `Void EventOnClickAll()`

- `Void EventOnClickGot()`

- `Void EventOnClickNotGot()`

- `Void _OnChangeSelection(GotType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveAchievementGotFilterView : MonoBehaviour, IHotfixable
{
	private ArchiveAchievementGotFilterBtnView[] _btnViews; // 0x18
	private Action`1 <onGotTypeChanged>k__BackingField; // 0x20
	private static DelegateBridge __Hotfix0_get_onGotTypeChanged; // 0x0
	private static DelegateBridge __Hotfix0_set_onGotTypeChanged; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_EventOnClickAll; // 0x18
	private static DelegateBridge __Hotfix0_EventOnClickGot; // 0x20
	private static DelegateBridge __Hotfix0_EventOnClickNotGot; // 0x28
	private static DelegateBridge __Hotfix0__OnChangeSelection; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public Action`1 onGotTypeChanged { get; set; }

	// RVA: 0x3017a08 VA: 0x759562fa08
	public Action`1 get_onGotTypeChanged() { }
	// RVA: 0x30154cc VA: 0x759562d4cc
	public Void set_onGotTypeChanged(Action`1 value) { }
	// RVA: 0x30151dc VA: 0x759562d1dc
	public Void Render(ArchiveAchievementModel viewModel) { }
	// RVA: 0x3017a70 VA: 0x759562fa70
	public Void EventOnClickAll() { }
	// RVA: 0x3017b94 VA: 0x759562fb94
	public Void EventOnClickGot() { }
	// RVA: 0x3017c00 VA: 0x759562fc00
	public Void EventOnClickNotGot() { }
	// RVA: 0x3017adc VA: 0x759562fadc
	private Void _OnChangeSelection(GotType type) { }
	// RVA: 0x3017c6c VA: 0x759562fc6c
	public Void .ctor() { }
}
```