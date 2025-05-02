# HomeMailArchiveBarItemView

**Namespace:** `Torappu.UI.Home`


## Fields

- `Text _textYear`

- `UIAnimationLocation _switchAnim`

- `UISwitchTween m_switchTween`

- `Boolean m_hasInited`

- `Int32 m_cachedYear`

- `UIStateFinder m_stateFinder`


## Methods

- `Void Render(HomeMailArchiveItemViewModel, Boolean)`

- `Void ResetStatus()`

- `Void EventOnItemClicked()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeMailArchiveBarItemView : MonoBehaviour, IHotfixable
{
	private Text _textYear; // 0x18
	private UIAnimationLocation _switchAnim; // 0x20
	private UISwitchTween m_switchTween; // 0x30
	private Boolean m_hasInited; // 0x38
	private Int32 m_cachedYear; // 0x3c
	private UIStateFinder m_stateFinder; // 0x40
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_ResetStatus; // 0x8
	private static DelegateBridge __Hotfix0_EventOnItemClicked; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2844ea4 VA: 0x7594e5cea4
	public Void Render(HomeMailArchiveItemViewModel model, Boolean isFocus) { }
	// RVA: 0x2845050 VA: 0x7594e5d050
	public Void ResetStatus() { }
	// RVA: 0x28450d8 VA: 0x7594e5d0d8
	public Void EventOnItemClicked() { }
	// RVA: 0x2844f78 VA: 0x7594e5cf78
	private Void _InitIfNot() { }
	// RVA: 0x28451d4 VA: 0x7594e5d1d4
	public Void .ctor() { }
}
```