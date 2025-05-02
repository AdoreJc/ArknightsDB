# ActMultiV3StageListItem

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `Text _stageCodeText`

- `Image _stageImage`

- `Image _cornerImage`

- `GameObject _pnlCorner`

- `GameObject _pnlLocked`

- `RectTransform _imgLock`

- `Vector2 _imgLockPosWithText`

- `Vector2 _imgLockPosWithoutText`

- `Text _textOpenTime`

- `GameObject _randomPanel`

- `GameObject _notRandomPanel`

- `GameObject _pnlSelected`

- `GameObject _pnlTrackpoint`

- `UIStateFinder m_stateFinder`

- `String m_cachedStageId`


## Methods

- `Void Render(ActMultiV3StageItemViewModel, ActMultiV3StageListViewModel)`

- `Void _RenderStageInfo(ActMultiV3StageItemViewModel)`

- `Void OnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3StageListItem : MonoBehaviour, IHotfixable
{
	private Text _stageCodeText; // 0x18
	private Image _stageImage; // 0x20
	private Image _cornerImage; // 0x28
	private GameObject _pnlCorner; // 0x30
	private GameObject _pnlLocked; // 0x38
	private RectTransform _imgLock; // 0x40
	private Vector2 _imgLockPosWithText; // 0x48
	private Vector2 _imgLockPosWithoutText; // 0x50
	private Text _textOpenTime; // 0x58
	private GameObject _randomPanel; // 0x60
	private GameObject _notRandomPanel; // 0x68
	private ActMultiV3StageListItemModeView[] _modeViews; // 0x70
	private GameObject _pnlSelected; // 0x78
	private GameObject _pnlTrackpoint; // 0x80
	private UIStateFinder m_stateFinder; // 0x88
	private String m_cachedStageId; // 0x98
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__RenderStageInfo; // 0x8
	private static DelegateBridge __Hotfix0_OnClicked; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x314b06c VA: 0x759576306c
	public Void Render(ActMultiV3StageItemViewModel viewModel, ActMultiV3StageListViewModel stageListViewModel) { }
	// RVA: 0x314b2a4 VA: 0x75957632a4
	private Void _RenderStageInfo(ActMultiV3StageItemViewModel viewModel) { }
	// RVA: 0x314b4a8 VA: 0x75957634a8
	public Void OnClicked() { }
	// RVA: 0x314b5b0 VA: 0x75957635b0
	public Void .ctor() { }
}
```