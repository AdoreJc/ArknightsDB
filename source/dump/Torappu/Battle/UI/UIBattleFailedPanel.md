# UIBattleFailedPanel

**Namespace:** `Torappu.Battle.UI`


## Fields

- `Single _fadeInTime`

- `Single _switchPageTime`

- `Button _raycastBtn`

- `RectTransform _continueLabel`

- `RectTransform _practiceHintPanel`

- `CanvasGroup _defaultPage`

- `CanvasGroup _apProtectPage`

- `CanvasGroup _powerScoreNotEnoughPage`

- `UnityEvent _onPanelClose`

- `GameObject _apProtectText_firstTry`

- `GameObject _apProtectText_period`

- `Tween m_tween`

- `Options m_options`

- `CanvasGroup m_currentPage`

- `Boolean m_isPageSwitching`

- `CanvasGroup m_rootCanvasGroup`


## Properties

- `CanvasGroup rootCanvasGroup`

- `Boolean isRaycastBlock`


## Methods

- `CanvasGroup get_rootCanvasGroup()`

- `Boolean get_isRaycastBlock()`

- `Void set_isRaycastBlock(Boolean)`

- `Void Show()`

- `Void Hide()`

- `Void OnInit()`

- `Void OnPanelClicked()`

- `Void _LoadData()`

- `Options _LoadOptions()`

- `Void _ResetAll()`

- `Void _SwitchPage(CanvasGroup, Boolean)`

- `IEnumerator _DoSwitchPageCoroutine(CanvasGroup, Single)`

- `Void _ClearTween(Boolean)`

- `Void Awake()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UIBattleFailedPanel : MonoBehaviour
{
	private const Int32 NUM_TIPS; // 0x0
	private Single _fadeInTime; // 0x18
	private Single _switchPageTime; // 0x1c
	private Button _raycastBtn; // 0x20
	private RectTransform _continueLabel; // 0x28
	private RectTransform _practiceHintPanel; // 0x30
	private Text[] _tips; // 0x38
	private CanvasGroup _defaultPage; // 0x40
	private CanvasGroup _apProtectPage; // 0x48
	private CanvasGroup _powerScoreNotEnoughPage; // 0x50
	private UnityEvent _onPanelClose; // 0x58
	private GameObject _apProtectText_firstTry; // 0x60
	private GameObject _apProtectText_period; // 0x68
	private CanvasGroup[] m_pages; // 0x70
	private Tween m_tween; // 0x78
	private Options m_options; // 0x80
	private CanvasGroup m_currentPage; // 0x88
	private Boolean m_isPageSwitching; // 0x90
	private CanvasGroup m_rootCanvasGroup; // 0x98

	private CanvasGroup rootCanvasGroup { get; }
	private Boolean isRaycastBlock { get; set; }

	// RVA: 0x2045bcc VA: 0x759465dbcc
	private CanvasGroup get_rootCanvasGroup() { }
	// RVA: 0x2045c74 VA: 0x759465dc74
	private Boolean get_isRaycastBlock() { }
	// RVA: 0x2045c98 VA: 0x759465dc98
	private Void set_isRaycastBlock(Boolean value) { }
	// RVA: 0x2045ce8 VA: 0x759465dce8
	public Void Show() { }
	// RVA: 0x20461fc VA: 0x759465e1fc
	public Void Hide() { }
	// RVA: 0x2046220 VA: 0x759465e220
	public Void OnInit() { }
	// RVA: 0x2046224 VA: 0x759465e224
	public Void OnPanelClicked() { }
	// RVA: 0x2045dec VA: 0x759465ddec
	private Void _LoadData() { }
	// RVA: 0x20463a0 VA: 0x759465e3a0
	private Options _LoadOptions() { }
	// RVA: 0x204636c VA: 0x759465e36c
	private Void _ResetAll() { }
	// RVA: 0x2046040 VA: 0x759465e040
	private Void _SwitchPage(CanvasGroup nextPage, Boolean useTween) { }
	// RVA: 0x20464cc VA: 0x759465e4cc
	private IEnumerator _DoSwitchPageCoroutine(CanvasGroup nextPage, Single duration) { }
	// RVA: 0x2046480 VA: 0x759465e480
	private Void _ClearTween(Boolean complete) { }
	// RVA: 0x2046594 VA: 0x759465e594
	private Void Awake() { }
	// RVA: 0x20466ac VA: 0x759465e6ac
	public Void .ctor() { }
}
```