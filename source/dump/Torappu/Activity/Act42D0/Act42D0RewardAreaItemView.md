# Act42D0RewardAreaItemView

**Namespace:** `Torappu.Activity.Act42D0`


## Fields

- `Text _code`

- `Text _codeSelect`

- `CanvasGroup _selectCanvasGroup`

- `Boolean m_isInited`

- `FadeSwitchTween m_fadeSwitchTween`

- `String m_selectedId`

- `Act42D0RewardAreaViewModel m_cachedViewModel`

- `UIStateFinder m_stateFinder`


## Methods

- `Void Render(String, Act42D0RewardAreaViewModel)`

- `Void _InitIfNot()`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act42D0
public class Act42D0RewardAreaItemView : MonoBehaviour, IHotfixable
{
	private Text _code; // 0x18
	private Text _codeSelect; // 0x20
	private CanvasGroup _selectCanvasGroup; // 0x28
	private Boolean m_isInited; // 0x30
	private FadeSwitchTween m_fadeSwitchTween; // 0x38
	private String m_selectedId; // 0x40
	private Act42D0RewardAreaViewModel m_cachedViewModel; // 0x48
	private UIStateFinder m_stateFinder; // 0x50
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnClick; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x321e4cc VA: 0x75958364cc
	public Void Render(String selectedAreaId, Act42D0RewardAreaViewModel viewModel) { }
	// RVA: 0x321e608 VA: 0x7595836608
	private Void _InitIfNot() { }
	// RVA: 0x321e70c VA: 0x759583670c
	public Void OnClick() { }
	// RVA: 0x321e814 VA: 0x7595836814
	public Void .ctor() { }
}
```