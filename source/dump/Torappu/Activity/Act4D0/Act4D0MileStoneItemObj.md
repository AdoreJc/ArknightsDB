# Act4D0MileStoneItemObj

**Namespace:** `Torappu.Activity.Act4D0`


## Fields

- `Image _finishImg`

- `Image _ableToGetImg`

- `GameObject _ableToGetPart`

- `GameObject _finishPart`

- `GameObject _cannotGetPart`

- `GameObject _finishBackgroundPart`

- `Single _scaleInfo`

- `Transform _itemViewContainer`

- `GameObject _charGetPart`

- `GameObject _itemGetPart`

- `Text _detailText`

- `Text _detailText_2`

- `Text _countText`

- `Text _countText_2`

- `Text _countTextActive`

- `Text _countTextNoActive`

- `Text _itemName`

- `Image _storyImg`

- `Image _countSymbol`

- `Image _charHead`

- `GameObject _storyObj`

- `GameObject _itemObj`

- `GameObject _ableToGetObj`

- `Button _ableToGetButton`

- `Button _ableToGetButtonChar`

- `Text _getText`

- `GameObject _focusLight`

- `Color _storyTextColor`

- `Color _itemTextColor`

- `Color _notFinishTextColor`

- `Color _notFinishedCountColor`

- `UIStringEvent clickEvent`

- `Boolean m_isInited`

- `UIItemCard m_itemCard`

- `String m_cacheId`


## Methods

- `Void _Inited()`

- `Void OnClick()`

- `Void OnFocus()`

- `Void RenderStoryPart(Act4D0MileStoneViewModel)`

- `Void RenderItemPart(Act4D0MileStoneViewModel)`

- `Void InitData(Act4D0MileStoneViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act4D0
public class Act4D0MileStoneItemObj : MonoBehaviour, IHotfixable
{
	private Image _finishImg; // 0x18
	private Image _ableToGetImg; // 0x20
	private GameObject _ableToGetPart; // 0x28
	private GameObject _finishPart; // 0x30
	private GameObject _cannotGetPart; // 0x38
	private GameObject _finishBackgroundPart; // 0x40
	private Single _scaleInfo; // 0x48
	private Transform _itemViewContainer; // 0x50
	private GameObject _charGetPart; // 0x58
	private GameObject _itemGetPart; // 0x60
	private Text _detailText; // 0x68
	private Text _detailText_2; // 0x70
	private Text _countText; // 0x78
	private Text _countText_2; // 0x80
	private Text _countTextActive; // 0x88
	private Text _countTextNoActive; // 0x90
	private Text _itemName; // 0x98
	private Image _storyImg; // 0xa0
	private Image _countSymbol; // 0xa8
	private Image _charHead; // 0xb0
	private GameObject _storyObj; // 0xb8
	private GameObject _itemObj; // 0xc0
	private GameObject _ableToGetObj; // 0xc8
	private Button _ableToGetButton; // 0xd0
	private Button _ableToGetButtonChar; // 0xd8
	private Text _getText; // 0xe0
	private GameObject _focusLight; // 0xe8
	private Color _storyTextColor; // 0xf0
	private Color _itemTextColor; // 0x100
	private Color _notFinishTextColor; // 0x110
	private Color _notFinishedCountColor; // 0x120
	public UIStringEvent clickEvent; // 0x130
	private Boolean m_isInited; // 0x138
	private UIItemCard m_itemCard; // 0x140
	private String m_cacheId; // 0x148
	private static DelegateBridge __Hotfix0__Inited; // 0x0
	private static DelegateBridge __Hotfix0_OnClick; // 0x8
	private static DelegateBridge __Hotfix0_OnFocus; // 0x10
	private static DelegateBridge __Hotfix0_RenderStoryPart; // 0x18
	private static DelegateBridge __Hotfix0_RenderItemPart; // 0x20
	private static DelegateBridge __Hotfix0_InitData; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x31e106c VA: 0x75957f906c
	private Void _Inited() { }
	// RVA: 0x31e1230 VA: 0x75957f9230
	public Void OnClick() { }
	// RVA: 0x31e0f5c VA: 0x75957f8f5c
	public Void OnFocus() { }
	// RVA: 0x31e12c4 VA: 0x75957f92c4
	public Void RenderStoryPart(Act4D0MileStoneViewModel viewModel) { }
	// RVA: 0x31e163c VA: 0x75957f963c
	public Void RenderItemPart(Act4D0MileStoneViewModel viewModel) { }
	// RVA: 0x31e0bdc VA: 0x75957f8bdc
	public Void InitData(Act4D0MileStoneViewModel viewModel) { }
	// RVA: 0x31e1914 VA: 0x75957f9914
	public Void .ctor() { }
}
```