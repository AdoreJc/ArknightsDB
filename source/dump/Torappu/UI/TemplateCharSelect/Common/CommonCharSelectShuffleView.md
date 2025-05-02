# CommonCharSelectShuffleView

**Namespace:** `Torappu.UI.TemplateCharSelect.Common`


## Fields

- `GameObject _filterProfHideGo`

- `GameObject _filterProfShowGo`

- `GameObject _filterProfDetailPartGo`

- `GameObject _filterProfNonePartGo`

- `Text _textFilterProfDetail`

- `CanvasGroup _professionFilterAlphaHandler`

- `Single _professionFilterSwitchDuration`

- `SimpleLayoutContent _professionFilterList`

- `Text _textProfessionAll`

- `Color _colorFilterAllUnselect`

- `Color _colorFilterAllSelect`

- `FadeSwitchTween m_professionFilterSwitchTween`

- `TemplateCharSelectShuffleProfessionListAdapter m_charSelectShuffleProfessionListAdapter`

- `Boolean m_hasInited`


## Methods

- `Void _InitIfNot()`

- `Void OnChangeProfShuffleView(ProfessionCategory)`

- `Void EventOnFilterAll()`

- `Void EventOnOpenFilter()`

- `Void EventOnCloseFilter()`

- `Void EventOnSort(CharacterSortType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateCharSelect.Common
public class CommonCharSelectShuffleView : TemplateCharSelectShuffleViewBase`1
{
	private GameObject _filterProfHideGo; // 0x30
	private GameObject _filterProfShowGo; // 0x38
	private GameObject _filterProfDetailPartGo; // 0x40
	private GameObject _filterProfNonePartGo; // 0x48
	private Text _textFilterProfDetail; // 0x50
	private CanvasGroup _professionFilterAlphaHandler; // 0x58
	private Single _professionFilterSwitchDuration; // 0x60
	private SimpleLayoutContent _professionFilterList; // 0x68
	private Text _textProfessionAll; // 0x70
	private Color _colorFilterAllUnselect; // 0x78
	private Color _colorFilterAllSelect; // 0x88
	private FadeSwitchTween m_professionFilterSwitchTween; // 0x98
	private TemplateCharSelectShuffleProfessionListAdapter m_charSelectShuffleProfessionListAdapter; // 0xa0
	private Boolean m_hasInited; // 0xa8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnRenderViewModel; // 0x8
	private static DelegateBridge __Hotfix0_OnChangeProfShuffleView; // 0x10
	private static DelegateBridge __Hotfix0_EventOnFilterAll; // 0x18
	private static DelegateBridge __Hotfix0_EventOnOpenFilter; // 0x20
	private static DelegateBridge __Hotfix0_EventOnCloseFilter; // 0x28
	private static DelegateBridge __Hotfix0_EventOnSort; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x2c5b1c4 VA: 0x75952731c4
	private Void _InitIfNot() { }
	// RVA: 0x2c5b3d8 VA: 0x75952733d8
	protected override Void OnRenderViewModel() { }
	// RVA: 0x2c5b624 VA: 0x7595273624
	public Void OnChangeProfShuffleView(ProfessionCategory prof) { }
	// RVA: 0x2c5b7f0 VA: 0x75952737f0
	public Void EventOnFilterAll() { }
	// RVA: 0x2c5b85c VA: 0x759527385c
	public Void EventOnOpenFilter() { }
	// RVA: 0x2c5ba18 VA: 0x7595273a18
	public Void EventOnCloseFilter() { }
	// RVA: 0x2c5bb38 VA: 0x7595273b38
	public Void EventOnSort(CharacterSortType sortType) { }
	// RVA: 0x2c5bd04 VA: 0x7595273d04
	public Void .ctor() { }
}
```