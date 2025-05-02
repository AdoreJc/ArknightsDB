# SandboxV2CharRepoView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2CharRepoListAdapter _charListAdapter`

- `SimpleLayoutContent _professionFilterList`

- `SimpleLayoutContent _statusFilterList`

- `CanvasGroup _alphaHandler`

- `Single _fadeDuraton`

- `CanvasGroup _professionFilterAlphaHandler`

- `Single _professionFilterSwitchDuration`

- `CanvasGroup _statusFilterAlphaHandler`

- `Single _statusFilterSwitchDuration`

- `Text _textProfessionAll`

- `Color _colorFilterAllUnselect`

- `Color _colorFilterAllSelect`

- `GameObject _filterProfHideGo`

- `GameObject _filterProfShowGo`

- `GameObject _filterProfDetailPartGo`

- `GameObject _filterProfNonePartGo`

- `Text _textFilterProfDetail`

- `GameObject _filterStatusHideGo`

- `GameObject _filterStatusShowGo`

- `Text _textSelectStatus`

- `GameObject _emptyPanelGo`

- `Boolean m_hasInited`

- `FadeSwitchTween m_switchTween`

- `FadeSwitchTween m_professionFilterSwitchTween`

- `FadeSwitchTween m_statusFilterSwitchTween`

- `SandboxCharShuffleProfessionListAdapter m_sandboxCharShuffleProfessionListAdapter`

- `SandboxShuffleStatusListAdapter m_sandboxShuffleStatusListAdapter`

- `SandboxV2CharRepoModel m_repoModel`


## Methods

- `Void set_onSlotClick(Action`1)`

- `Void set_onCharDineClick(Action`1)`

- `Void set_onProfessionFilterClick(Action`1)`

- `Void set_onStatusFilterClick(Action`1)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2CharRepoView : DataBinder`1
{
	private SandboxV2CharRepoListAdapter _charListAdapter; // 0x20
	private SimpleLayoutContent _professionFilterList; // 0x28
	private SimpleLayoutContent _statusFilterList; // 0x30
	private CanvasGroup _alphaHandler; // 0x38
	private Single _fadeDuraton; // 0x40
	private CanvasGroup _professionFilterAlphaHandler; // 0x48
	private Single _professionFilterSwitchDuration; // 0x50
	private CanvasGroup _statusFilterAlphaHandler; // 0x58
	private Single _statusFilterSwitchDuration; // 0x60
	private Text _textProfessionAll; // 0x68
	private Color _colorFilterAllUnselect; // 0x70
	private Color _colorFilterAllSelect; // 0x80
	private GameObject _filterProfHideGo; // 0x90
	private GameObject _filterProfShowGo; // 0x98
	private GameObject _filterProfDetailPartGo; // 0xa0
	private GameObject _filterProfNonePartGo; // 0xa8
	private Text _textFilterProfDetail; // 0xb0
	private GameObject _filterStatusHideGo; // 0xb8
	private GameObject _filterStatusShowGo; // 0xc0
	private Text _textSelectStatus; // 0xc8
	private GameObject _emptyPanelGo; // 0xd0
	private Boolean m_hasInited; // 0xd8
	private FadeSwitchTween m_switchTween; // 0xe0
	private FadeSwitchTween m_professionFilterSwitchTween; // 0xe8
	private FadeSwitchTween m_statusFilterSwitchTween; // 0xf0
	private SandboxCharShuffleProfessionListAdapter m_sandboxCharShuffleProfessionListAdapter; // 0xf8
	private SandboxShuffleStatusListAdapter m_sandboxShuffleStatusListAdapter; // 0x100
	private SandboxV2CharRepoModel m_repoModel; // 0x108
	private Action`1 <onSlotClick>k__BackingField; // 0x110
	private Action`1 <onCharDineClick>k__BackingField; // 0x118
	private Action`1 <onProfessionFilterClick>k__BackingField; // 0x120
	private Action`1 <onStatusFilterClick>k__BackingField; // 0x128
	private static DelegateBridge __Hotfix0_get_onSlotClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onSlotClick; // 0x8
	private static DelegateBridge __Hotfix0_get_onCharDineClick; // 0x10
	private static DelegateBridge __Hotfix0_set_onCharDineClick; // 0x18
	private static DelegateBridge __Hotfix0_get_onProfessionFilterClick; // 0x20
	private static DelegateBridge __Hotfix0_set_onProfessionFilterClick; // 0x28
	private static DelegateBridge __Hotfix0_get_onStatusFilterClick; // 0x30
	private static DelegateBridge __Hotfix0_set_onStatusFilterClick; // 0x38
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x40
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	private Action`1 onSlotClick { get; set; }
	private Action`1 onCharDineClick { get; set; }
	private Action`1 onProfessionFilterClick { get; set; }
	private Action`1 onStatusFilterClick { get; set; }

	// RVA: 0x260d208 VA: 0x7594c25208
	private Action`1 get_onSlotClick() { }
	// RVA: 0x260d270 VA: 0x7594c25270
	public Void set_onSlotClick(Action`1 value) { }
	// RVA: 0x260d2f4 VA: 0x7594c252f4
	private Action`1 get_onCharDineClick() { }
	// RVA: 0x260d35c VA: 0x7594c2535c
	public Void set_onCharDineClick(Action`1 value) { }
	// RVA: 0x260d3e0 VA: 0x7594c253e0
	private Action`1 get_onProfessionFilterClick() { }
	// RVA: 0x260d448 VA: 0x7594c25448
	public Void set_onProfessionFilterClick(Action`1 value) { }
	// RVA: 0x260d4cc VA: 0x7594c254cc
	private Action`1 get_onStatusFilterClick() { }
	// RVA: 0x260d534 VA: 0x7594c25534
	public Void set_onStatusFilterClick(Action`1 value) { }
	// RVA: 0x260d5b8 VA: 0x7594c255b8
	public override Void OnValueChanged(SandboxV2SquadGroupProp property) { }
	// RVA: 0x260d998 VA: 0x7594c25998
	private Void _InitIfNot() { }
	// RVA: 0x260dcc4 VA: 0x7594c25cc4
	public Void .ctor() { }
}
```