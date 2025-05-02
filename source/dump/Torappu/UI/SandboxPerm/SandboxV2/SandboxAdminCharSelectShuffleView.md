# SandboxAdminCharSelectShuffleView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `GameObject _filterProfHideGo`

- `GameObject _filterProfShowGo`

- `GameObject _filterProfDetailPartGo`

- `GameObject _filterProfNonePartGo`

- `Text _textFilterProfDetail`

- `GameObject _filterStatusHideGo`

- `GameObject _filterStatusShowGo`

- `CanvasGroup _professionFilterAlphaHandler`

- `Single _professionFilterSwitchDuration`

- `CanvasGroup _statusFilterAlphaHandler`

- `Single _statusFilterSwitchDuration`

- `SimpleLayoutContent _professionFilterList`

- `SimpleLayoutContent _statusFilterList`

- `Text _textProfessionAll`

- `Color _colorFilterAllUnselect`

- `Color _colorFilterAllSelect`

- `Text _textSelectStatus`

- `GameObject _panelBtnFilterStatus`

- `FadeSwitchTween m_professionFilterSwitchTween`

- `FadeSwitchTween m_statusFilterSwitchTween`

- `SandboxCharShuffleProfessionListAdapter m_sandboxCharShuffleProfessionListAdapter`

- `SandboxShuffleStatusListAdapter m_sandboxShuffleStatusListAdapter`

- `UIStateFinder m_stateFinder`

- `Boolean m_hasInited`


## Methods

- `Void _InitIfNot()`

- `Void _HandleFilterStatusWhenNeeded(SandboxV2ShuffleViewModel)`

- `Void OnOpenStateShuffleView()`

- `Void OnCloseStateShuffleView()`

- `Void OnChangeStateShuffleView(SandboxV2CharFilter)`

- `Void OnOpenProfShuffleView()`

- `Void OnCloseProfShuffleView()`

- `Void OnChangeProfShuffleView(ProfessionCategory)`

- `Void OnSelectProfAllShuffle()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxAdminCharSelectShuffleView : SandboxV2AdminCharAbstractShuffleView
{
	private GameObject _filterProfHideGo; // 0x18
	private GameObject _filterProfShowGo; // 0x20
	private GameObject _filterProfDetailPartGo; // 0x28
	private GameObject _filterProfNonePartGo; // 0x30
	private Text _textFilterProfDetail; // 0x38
	private GameObject _filterStatusHideGo; // 0x40
	private GameObject _filterStatusShowGo; // 0x48
	private CanvasGroup _professionFilterAlphaHandler; // 0x50
	private Single _professionFilterSwitchDuration; // 0x58
	private CanvasGroup _statusFilterAlphaHandler; // 0x60
	private Single _statusFilterSwitchDuration; // 0x68
	private SimpleLayoutContent _professionFilterList; // 0x70
	private SimpleLayoutContent _statusFilterList; // 0x78
	private Text _textProfessionAll; // 0x80
	private Color _colorFilterAllUnselect; // 0x88
	private Color _colorFilterAllSelect; // 0x98
	private Text _textSelectStatus; // 0xa8
	private GameObject _panelBtnFilterStatus; // 0xb0
	private FadeSwitchTween m_professionFilterSwitchTween; // 0xb8
	private FadeSwitchTween m_statusFilterSwitchTween; // 0xc0
	private SandboxCharShuffleProfessionListAdapter m_sandboxCharShuffleProfessionListAdapter; // 0xc8
	private SandboxShuffleStatusListAdapter m_sandboxShuffleStatusListAdapter; // 0xd0
	private UIStateFinder m_stateFinder; // 0xd8
	private Boolean m_hasInited; // 0xe8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnApplyShuffleViewModel; // 0x8
	private static DelegateBridge __Hotfix0__HandleFilterStatusWhenNeeded; // 0x10
	private static DelegateBridge __Hotfix0_OnOpenStateShuffleView; // 0x18
	private static DelegateBridge __Hotfix0_OnCloseStateShuffleView; // 0x20
	private static DelegateBridge __Hotfix0_OnChangeStateShuffleView; // 0x28
	private static DelegateBridge __Hotfix0_OnOpenProfShuffleView; // 0x30
	private static DelegateBridge __Hotfix0_OnCloseProfShuffleView; // 0x38
	private static DelegateBridge __Hotfix0_OnChangeProfShuffleView; // 0x40
	private static DelegateBridge __Hotfix0_OnSelectProfAllShuffle; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x24843fc VA: 0x7594a9c3fc
	private Void _InitIfNot() { }
	// RVA: 0x2484918 VA: 0x7594a9c918
	public override Void OnApplyShuffleViewModel(SandboxV2CharListViewModel viewModel) { }
	// RVA: 0x2484b10 VA: 0x7594a9cb10
	private Void _HandleFilterStatusWhenNeeded(SandboxV2ShuffleViewModel shuffleViewModel) { }
	// RVA: 0x2484c60 VA: 0x7594a9cc60
	public Void OnOpenStateShuffleView() { }
	// RVA: 0x2484d14 VA: 0x7594a9cd14
	public Void OnCloseStateShuffleView() { }
	// RVA: 0x2484dc8 VA: 0x7594a9cdc8
	public Void OnChangeStateShuffleView(SandboxV2CharFilter status) { }
	// RVA: 0x2484ed4 VA: 0x7594a9ced4
	public Void OnOpenProfShuffleView() { }
	// RVA: 0x2484f88 VA: 0x7594a9cf88
	public Void OnCloseProfShuffleView() { }
	// RVA: 0x248503c VA: 0x7594a9d03c
	public Void OnChangeProfShuffleView(ProfessionCategory prof) { }
	// RVA: 0x2485148 VA: 0x7594a9d148
	public Void OnSelectProfAllShuffle() { }
	// RVA: 0x248524c VA: 0x7594a9d24c
	public Void .ctor() { }
}
```