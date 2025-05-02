# SixStarRuneSelectRuneItemView

**Namespace:** `Torappu.UI.Stage`


## Fields

- `GameObject _panelSplit`

- `Text _textDesc`

- `UIAnimationLocation _itemSelectSwitchAnim`

- `UIAnimationLocation _groupSelectSwitchAnim`

- `Int32 m_cachedLevel`

- `String m_cachedRuneId`

- `UICompDialogFinder m_dialogFinder`

- `UISwitchTween m_itemSwitchTween`

- `UISwitchTween m_groupSwitchTween`

- `Boolean m_hasInited`


## Methods

- `Void Render(SixStarRuneSelectItemViewModel, SixStarRuneSelectGroupStatus, Boolean)`

- `Void EventOnItemClicked()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class SixStarRuneSelectRuneItemView : MonoBehaviour, IHotfixable
{
	private GameObject _panelSplit; // 0x18
	private Text _textDesc; // 0x20
	private UIAnimationLocation _itemSelectSwitchAnim; // 0x28
	private UIAnimationLocation _groupSelectSwitchAnim; // 0x38
	private Int32 m_cachedLevel; // 0x48
	private String m_cachedRuneId; // 0x50
	private UICompDialogFinder m_dialogFinder; // 0x58
	private UISwitchTween m_itemSwitchTween; // 0x68
	private UISwitchTween m_groupSwitchTween; // 0x70
	private Boolean m_hasInited; // 0x78
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_EventOnItemClicked; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2f4fbf8 VA: 0x7595567bf8
	public Void Render(SixStarRuneSelectItemViewModel model, SixStarRuneSelectGroupStatus status, Boolean isLastItem) { }
	// RVA: 0x2f4fe74 VA: 0x7595567e74
	public Void EventOnItemClicked() { }
	// RVA: 0x2f4fd24 VA: 0x7595567d24
	private Void _InitIfNot() { }
	// RVA: 0x2f4ff50 VA: 0x7595567f50
	public Void .ctor() { }
}
```