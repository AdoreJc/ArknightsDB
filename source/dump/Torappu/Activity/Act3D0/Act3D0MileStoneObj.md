# Act3D0MileStoneObj

**Namespace:** `Torappu.Activity.Act3D0`


## Fields

- `Image _finishImg`

- `Image _ableToGetImg`

- `GameObject _ableToGetPart`

- `GameObject _finishPart`

- `GameObject _cannotGetPart`

- `Single _scaleInfo`

- `Transform _itemViewContainer`

- `Text _detailText`

- `Text _countText`

- `Text _countText_2`

- `Text _countTextActive`

- `Text _countTextNoActive`

- `Text _itemName`

- `Image _countSymbol`

- `Image _backShiningImg`

- `GameObject _maskB`

- `GameObject _maskW`

- `CanvasGroup _canvasGroup`

- `GameObject _replicateFlag1`

- `GameObject _replicateFlag2`

- `UIStringEvent clickEvent`

- `Boolean m_isInited`

- `UIItemCard m_itemCard`

- `String m_cacheId`

- `Tween m_cacheTween`


## Methods

- `Void _Inited()`

- `Void RenderAgain(Act3D0MileStoneViewModel)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act3D0
public class Act3D0MileStoneObj : MonoBehaviour, IHotfixable
{
	private Image _finishImg; // 0x18
	private Image _ableToGetImg; // 0x20
	private GameObject _ableToGetPart; // 0x28
	private GameObject _finishPart; // 0x30
	private GameObject _cannotGetPart; // 0x38
	private Single _scaleInfo; // 0x40
	private Transform _itemViewContainer; // 0x48
	private Text _detailText; // 0x50
	private Text _countText; // 0x58
	private Text _countText_2; // 0x60
	private Text _countTextActive; // 0x68
	private Text _countTextNoActive; // 0x70
	private Text _itemName; // 0x78
	private Image _countSymbol; // 0x80
	private Image _backShiningImg; // 0x88
	private GameObject _maskB; // 0x90
	private GameObject _maskW; // 0x98
	private CanvasGroup _canvasGroup; // 0xa0
	private GameObject _replicateFlag1; // 0xa8
	private GameObject _replicateFlag2; // 0xb0
	public UIStringEvent clickEvent; // 0xb8
	private Boolean m_isInited; // 0xc0
	private UIItemCard m_itemCard; // 0xc8
	private String m_cacheId; // 0xd0
	private Tween m_cacheTween; // 0xd8
	private const Single ANIMATION_ALPHA_SPEED; // 0x0
	private const Single ANIMATION_ANIM_SPEED; // 0x0
	private static DelegateBridge __Hotfix0__Inited; // 0x0
	private static DelegateBridge __Hotfix0_RenderAgain; // 0x8
	private static DelegateBridge __Hotfix0_OnClick; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3235f2c VA: 0x759584df2c
	private Void _Inited() { }
	// RVA: 0x3235404 VA: 0x759584d404
	public Void RenderAgain(Act3D0MileStoneViewModel viewModel) { }
	// RVA: 0x3236134 VA: 0x759584e134
	public Void OnClick() { }
	// RVA: 0x32361c8 VA: 0x759584e1c8
	public Void .ctor() { }
}
```