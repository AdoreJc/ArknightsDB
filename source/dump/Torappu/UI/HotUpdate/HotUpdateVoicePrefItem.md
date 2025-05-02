# HotUpdateVoicePrefItem

**Namespace:** `Torappu.UI.HotUpdate`


## Fields

- `TwoStateToggle _toggle`

- `Text _textTitle`

- `HotUpdatePref m_cachedPref`


## Methods

- `Void set_onClicked(Action`1)`

- `Void EventOnClicked()`

- `Void Render(Options)`

- `Void _UpdateContent(HotUpdatePref)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HotUpdate
public class HotUpdateVoicePrefItem : MonoBehaviour, IHotfixable
{
	private TwoStateToggle _toggle; // 0x18
	private Text[] _textDescs; // 0x20
	private Text _textTitle; // 0x28
	private HotUpdatePref m_cachedPref; // 0x30
	private Action`1 <onClicked>k__BackingField; // 0x38
	private static DelegateBridge __Hotfix0_get_onClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onClicked; // 0x8
	private static DelegateBridge __Hotfix0_EventOnClicked; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge __Hotfix0__UpdateContent; // 0x20
	private static DelegateBridge __Hotfix0__GetViewDataFromPref; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	private Action`1 onClicked { get; set; }

	// RVA: 0x27d0ecc VA: 0x7594de8ecc
	private Action`1 get_onClicked() { }
	// RVA: 0x27d0f34 VA: 0x7594de8f34
	public Void set_onClicked(Action`1 value) { }
	// RVA: 0x27d0fb8 VA: 0x7594de8fb8
	public Void EventOnClicked() { }
	// RVA: 0x27d1060 VA: 0x7594de9060
	public Void Render(Options options) { }
	// RVA: 0x27d1100 VA: 0x7594de9100
	private Void _UpdateContent(HotUpdatePref newViewPref) { }
	// RVA: 0x27d1274 VA: 0x7594de9274
	private static ViewData _GetViewDataFromPref(HotUpdatePref pref) { }
	// RVA: 0x27d14a0 VA: 0x7594de94a0
	public Void .ctor() { }
}
```