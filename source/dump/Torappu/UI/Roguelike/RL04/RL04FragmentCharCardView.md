# RL04FragmentCharCardView

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `GameObject _panelEmpty`

- `GameObject _panelChar`

- `Image _imgAvatar`

- `GameObject _panelEvolvePhase2`

- `Text _textWeight`

- `GameObject _panelCanUse`

- `GameObject _panelSelected`

- `Int32 m_cachedIndex`


## Methods

- `Void set_onCardClicked(Action`1)`

- `Void Render(RL04FragmentCharCardViewModel, Param)`

- `Void EventOnCardClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04FragmentCharCardView : MonoBehaviour, IHotfixable
{
	private GameObject _panelEmpty; // 0x18
	private GameObject _panelChar; // 0x20
	private Image _imgAvatar; // 0x28
	private GameObject _panelEvolvePhase2; // 0x30
	private Text _textWeight; // 0x38
	private GameObject _panelCanUse; // 0x40
	private GameObject _panelSelected; // 0x48
	private Action`1 <onCardClicked>k__BackingField; // 0x50
	private Int32 m_cachedIndex; // 0x58
	private static DelegateBridge __Hotfix0_get_onCardClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onCardClicked; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_EventOnCardClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Action`1 onCardClicked { get; set; }

	// RVA: 0x2b1c334 VA: 0x7595134334
	private Action`1 get_onCardClicked() { }
	// RVA: 0x2b1c39c VA: 0x759513439c
	public Void set_onCardClicked(Action`1 value) { }
	// RVA: 0x2b1c420 VA: 0x7595134420
	public Void Render(RL04FragmentCharCardViewModel viewModel, Param param) { }
	// RVA: 0x2b1c5d8 VA: 0x75951345d8
	public Void EventOnCardClicked() { }
	// RVA: 0x2b1c678 VA: 0x7595134678
	public Void .ctor() { }
}
```