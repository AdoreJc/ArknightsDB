# ArchiveEndbookDetailDataBinder

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `CanvasGroup _detailCanvasGroup`

- `GameObject _panelDetail`

- `UIDynImage _cgImg`

- `GameObject _panelAvg`

- `GameObject _panelUnlock`

- `GameObject _panelLock`

- `SimpleLayoutContent _endItemContent`

- `GameObject _extendingPanel`

- `Text _titleUp`

- `Text _titleDown`

- `Text _textContent`

- `Text _textTitle`

- `Text _unlockDesc`

- `ScrollRect _contentRect`

- `RectTransform _textRect`

- `EndbookDetailShowTween m_showTween`

- `Boolean m_isInited`

- `ActArchiveController m_controller`

- `EndbookDetailItemAdapter m_adapter`

- `String m_cachedEndId`

- `String m_cachedAvgId`


## Properties

- `ActArchiveController controller`


## Methods

- `ActArchiveController get_controller()`

- `Void set_controller(ActArchiveController)`

- `Void _InitIfNot()`

- `String _TryLoadTextAssets(String)`

- `Void _OnStoryClicked(String)`

- `DataBundle _ArchiveEndbookDetailToDataBundle()`

- `Void _ResetScrollPosition()`

- `Void OnAvgClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveEndbookDetailDataBinder : DataBinder`1
{
	private CanvasGroup _detailCanvasGroup; // 0x20
	private GameObject _panelDetail; // 0x28
	private UIDynImage _cgImg; // 0x30
	private GameObject _panelAvg; // 0x38
	private GameObject _panelUnlock; // 0x40
	private GameObject _panelLock; // 0x48
	private SimpleLayoutContent _endItemContent; // 0x50
	private GameObject _extendingPanel; // 0x58
	private Text _titleUp; // 0x60
	private Text _titleDown; // 0x68
	private Text _textContent; // 0x70
	private Text _textTitle; // 0x78
	private Text _unlockDesc; // 0x80
	private ScrollRect _contentRect; // 0x88
	private RectTransform _textRect; // 0x90
	private EndbookDetailShowTween m_showTween; // 0x98
	private Boolean m_isInited; // 0xa0
	private ActArchiveController m_controller; // 0xa8
	private EndbookDetailItemAdapter m_adapter; // 0xb0
	private String m_cachedEndId; // 0xb8
	private String m_cachedAvgId; // 0xc0
	private static DelegateBridge __Hotfix0_get_controller; // 0x0
	private static DelegateBridge __Hotfix0_set_controller; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__TryLoadTextAssets; // 0x20
	private static DelegateBridge __Hotfix0__OnStoryClicked; // 0x28
	private static DelegateBridge __Hotfix0__ArchiveEndbookDetailToDataBundle; // 0x30
	private static DelegateBridge __Hotfix0__ResetScrollPosition; // 0x38
	private static DelegateBridge __Hotfix0_OnAvgClicked; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	private ActArchiveController controller { get; set; }

	// RVA: 0x304c83c VA: 0x759566483c
	private ActArchiveController get_controller() { }
	// RVA: 0x304c544 VA: 0x7595664544
	public Void set_controller(ActArchiveController value) { }
	// RVA: 0x304c9c4 VA: 0x75956649c4
	public override Void OnValueChanged(EndbookProperty property) { }
	// RVA: 0x304c8a4 VA: 0x75956648a4
	private Void _InitIfNot() { }
	// RVA: 0x304ce28 VA: 0x7595664e28
	private String _TryLoadTextAssets(String textId) { }
	// RVA: 0x304d1b8 VA: 0x75956651b8
	private Void _OnStoryClicked(String storyId) { }
	// RVA: 0x304d33c VA: 0x759566533c
	private DataBundle _ArchiveEndbookDetailToDataBundle() { }
	// RVA: 0x304cfcc VA: 0x7595664fcc
	private Void _ResetScrollPosition() { }
	// RVA: 0x304d458 VA: 0x7595665458
	public Void OnAvgClicked() { }
	// RVA: 0x304d4f0 VA: 0x75956654f0
	public Void .ctor() { }
}
```