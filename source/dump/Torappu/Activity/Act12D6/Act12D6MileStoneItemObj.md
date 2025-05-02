# Act12D6MileStoneItemObj

**Namespace:** `Torappu.Activity.Act12D6`


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

- `Void RenderItemPart(Act12D6MileStoneViewModel)`

- `Void InitData(Act12D6MileStoneViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12D6
public class Act12D6MileStoneItemObj : MonoBehaviour, IHotfixable
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
	private Image _countSymbol; // 0xa0
	private Image _charHead; // 0xa8
	private GameObject _storyObj; // 0xb0
	private GameObject _itemObj; // 0xb8
	private GameObject _ableToGetObj; // 0xc0
	private Button _ableToGetButton; // 0xc8
	private Button _ableToGetButtonChar; // 0xd0
	private Text _getText; // 0xd8
	private GameObject _focusLight; // 0xe0
	private Color _storyTextColor; // 0xe8
	private Color _itemTextColor; // 0xf8
	private Color _notFinishTextColor; // 0x108
	private Color _notFinishedCountColor; // 0x118
	public UIStringEvent clickEvent; // 0x128
	private Boolean m_isInited; // 0x130
	private UIItemCard m_itemCard; // 0x138
	private String m_cacheId; // 0x140
	private static DelegateBridge __Hotfix0__Inited; // 0x0
	private static DelegateBridge __Hotfix0_OnClick; // 0x8
	private static DelegateBridge __Hotfix0_OnFocus; // 0x10
	private static DelegateBridge __Hotfix0_RenderItemPart; // 0x18
	private static DelegateBridge __Hotfix0_InitData; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x347c7f8 VA: 0x7595a947f8
	private Void _Inited() { }
	// RVA: 0x347c9b8 VA: 0x7595a949b8
	public Void OnClick() { }
	// RVA: 0x347ca4c VA: 0x7595a94a4c
	public Void OnFocus() { }
	// RVA: 0x347cacc VA: 0x7595a94acc
	public Void RenderItemPart(Act12D6MileStoneViewModel viewModel) { }
	// RVA: 0x34766e0 VA: 0x7595a8e6e0
	public Void InitData(Act12D6MileStoneViewModel viewModel) { }
	// RVA: 0x347cddc VA: 0x7595a94ddc
	public Void .ctor() { }
}
```