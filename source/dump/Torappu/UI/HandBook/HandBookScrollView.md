# HandBookScrollView

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `UIWrappedScrollRect _scrollView`

- `Transform _contentPanel`

- `Transform _lineContainer`

- `Transform _cardContainer`

- `Transform _sixLineContainer`

- `Transform _teamContainer`

- `HandBookCommonStateBean _stateBean`

- `HandBookCardView _handbookCommonCard`

- `RectTransform _contentRect`

- `GameObject _openButton`

- `GameObject _backButton`

- `HandbookSixLineView _sixLine`

- `Image _teamImage`

- `UnityEvent _onCheck`

- `HandBookTeamView _teamView`

- `Vector3 m_initPos`

- `Vector2 m_initSize`

- `Single m_cacheScale`


## Methods

- `Void CleanEffect()`

- `Void HideEffect()`

- `Void ReloadCard(HandBookCardViewModel)`

- `Void _ChangePos(HandBookCardView, Boolean)`

- `IEnumerator AnimatorController(HandBookScrollViewProperty, Boolean)`

- `Void _MoveContentAfterSecond(Vector3, Single)`

- `Void OnChildFocus(String)`

- `Void OnChildClick(String, HandBookCardView)`

- `Void CancelClick()`

- `Void ApplyData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookScrollView : DataBinder`1
{
	private UIWrappedScrollRect _scrollView; // 0x20
	private Transform _contentPanel; // 0x28
	protected HandBookCommonLineRender[] _linePrefab; // 0x30
	protected Transform _lineContainer; // 0x38
	protected Transform _cardContainer; // 0x40
	private Transform _sixLineContainer; // 0x48
	private Transform _teamContainer; // 0x50
	private HandBookCommonStateBean _stateBean; // 0x58
	protected HandBookCardView _handbookCommonCard; // 0x60
	private RectTransform _contentRect; // 0x68
	private GameObject _openButton; // 0x70
	private GameObject _backButton; // 0x78
	protected HandbookSixLineView _sixLine; // 0x80
	private Image _teamImage; // 0x88
	private UnityEvent _onCheck; // 0x90
	private List`1 m_teamViews; // 0x98
	protected HandBookTeamView _teamView; // 0xa0
	private List`1 m_handbookCards; // 0xa8
	private List`1 m_sixLineViews; // 0xb0
	private Dictionary`2 m_handbookSixLists; // 0xb8
	private Vector3 m_initPos; // 0xc0
	private Vector2 m_initSize; // 0xcc
	private Dictionary`2 m_lines; // 0xd8
	private Single m_cacheScale; // 0xe0
	private static DelegateBridge __Hotfix0_CleanEffect; // 0x0
	private static DelegateBridge __Hotfix0_HideEffect; // 0x8
	private static DelegateBridge __Hotfix0_ReloadCard; // 0x10
	private static DelegateBridge __Hotfix0__ChangePos; // 0x18
	private static DelegateBridge __Hotfix0_AnimatorController; // 0x20
	private static DelegateBridge __Hotfix0__MoveContentAfterSecond; // 0x28
	private static DelegateBridge __Hotfix0_OnChildFocus; // 0x30
	private static DelegateBridge __Hotfix0_OnChildClick; // 0x38
	private static DelegateBridge __Hotfix0_CancelClick; // 0x40
	private static DelegateBridge __Hotfix0_ApplyData; // 0x48
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x2eb1fc8 VA: 0x75954c9fc8
	public Void CleanEffect() { }
	// RVA: 0x2eb21b0 VA: 0x75954ca1b0
	public Void HideEffect() { }
	// RVA: 0x2eb2350 VA: 0x75954ca350
	public Void ReloadCard(HandBookCardViewModel cardViewModel) { }
	// RVA: 0x2eb250c VA: 0x75954ca50c
	private Void _ChangePos(HandBookCardView view, Boolean lastSelected) { }
	// RVA: 0x2eb271c VA: 0x75954ca71c
	private IEnumerator AnimatorController(HandBookScrollViewProperty property, Boolean lastSelected) { }
	// RVA: 0x2eb2824 VA: 0x75954ca824
	private Void _MoveContentAfterSecond(Vector3 secondPos, Single time) { }
	// RVA: 0x2eb28e0 VA: 0x75954ca8e0
	public Void OnChildFocus(String charID) { }
	// RVA: 0x2eb2b68 VA: 0x75954cab68
	public Void OnChildClick(String charID, HandBookCardView child) { }
	// RVA: 0x2eb2cec VA: 0x75954cacec
	public Void CancelClick() { }
	// RVA: 0x2eb2df0 VA: 0x75954cadf0
	public Void ApplyData() { }
	// RVA: 0x2eb4c08 VA: 0x75954ccc08
	public override Void OnValueChanged(HandBookScrollViewProperty property) { }
	// RVA: 0x2eb1c54 VA: 0x75954c9c54
	public Void .ctor() { }
}
```