# RecruitBuildConfigTagView

**Namespace:** `Torappu.UI.Recruit`


## Fields

- `Text _textContent`

- `TwoStateToggle _toggle`

- `TwoStateToggle _toggleSpecial`

- `GameObject _panelContent`

- `GameObject _panelSpecial`

- `Int32 m_tagIndex`


## Methods

- `Void set_onClick(Action`1)`

- `Void Render(BuildConfigTagViewModel)`

- `Void EventOnTagClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Recruit
public class RecruitBuildConfigTagView : MonoBehaviour, IHotfixable
{
	private Text _textContent; // 0x18
	private TwoStateToggle _toggle; // 0x20
	private TwoStateToggle _toggleSpecial; // 0x28
	private GameObject _panelContent; // 0x30
	private GameObject _panelSpecial; // 0x38
	private Action`1 <onClick>k__BackingField; // 0x40
	private Int32 m_tagIndex; // 0x48
	private static DelegateBridge __Hotfix0_get_onClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onClick; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_EventOnTagClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Action`1 onClick { get; set; }

	// RVA: 0x270e878 VA: 0x7594d26878
	private Action`1 get_onClick() { }
	// RVA: 0x270e190 VA: 0x7594d26190
	public Void set_onClick(Action`1 value) { }
	// RVA: 0x270e580 VA: 0x7594d26580
	public Void Render(BuildConfigTagViewModel viewModel) { }
	// RVA: 0x270e8e0 VA: 0x7594d268e0
	public Void EventOnTagClick() { }
	// RVA: 0x270e980 VA: 0x7594d26980
	public Void .ctor() { }
}
```