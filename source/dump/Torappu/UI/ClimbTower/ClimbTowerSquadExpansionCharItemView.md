# ClimbTowerSquadExpansionCharItemView

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `UIAtlasImage _imageChrPortrait`

- `Image _imgProfession`

- `Image _imgRarity`

- `Image _imgEvolve`

- `Text _textName`

- `Text _textLv`

- `LayoutElement _layoutElement`

- `UIAnimationLocation _switchAnim`

- `UIAnimationLocation _maskSwitchAnim`

- `CanvasGroup _canvasGroup`

- `Single _enterTweenDuration`

- `GameObject _spIconGo`

- `GameObject _npcIconGo`

- `GameObject _hotspotGo`

- `TwoStateToggle _toggleView`

- `Boolean m_hasInited`

- `Boolean m_isGiveUp`

- `String m_portraitCache`

- `Int32 m_index`

- `Boolean m_isSelect`

- `String m_charId`

- `Single m_spacing`

- `String m_groupId`

- `UISwitchTween m_enterTween`

- `AnimationSwitchTween m_switchTween`

- `AnimationSwitchTween m_maskSwitchTween`


## Properties

- `GameObject hotspotGo`

- `LayoutElement layoutElement`


## Methods

- `GameObject get_hotspotGo()`

- `Void set_onCharSelect(Action`3)`

- `LayoutElement get_layoutElement()`

- `Void RenderGiveUpView(Boolean, Boolean)`

- `Void RenderCharView(Int32, String, Boolean, Boolean, Boolean, ClimbTowerSquadExpansionCharModel, Single)`

- `Void _InitIfNot()`

- `IEnumerator PlayEnterAnim(Action)`

- `Void ResetEnterAnim()`

- `Void OnCharSelect()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerSquadExpansionCharItemView : MonoBehaviour, IHotfixable
{
	private UIAtlasImage _imageChrPortrait; // 0x18
	private Image _imgProfession; // 0x20
	private Image _imgRarity; // 0x28
	private Image _imgEvolve; // 0x30
	private Text _textName; // 0x38
	private Text _textLv; // 0x40
	private LayoutElement _layoutElement; // 0x48
	private UIAnimationLocation _switchAnim; // 0x50
	private UIAnimationLocation _maskSwitchAnim; // 0x60
	private CanvasGroup _canvasGroup; // 0x70
	private Single _enterTweenDuration; // 0x78
	private GameObject _spIconGo; // 0x80
	private GameObject _npcIconGo; // 0x88
	private GameObject _hotspotGo; // 0x90
	private TwoStateToggle _toggleView; // 0x98
	private Boolean m_hasInited; // 0xa0
	private Boolean m_isGiveUp; // 0xa1
	private String m_portraitCache; // 0xa8
	private Int32 m_index; // 0xb0
	private Boolean m_isSelect; // 0xb4
	private String m_charId; // 0xb8
	private Single m_spacing; // 0xc0
	private String m_groupId; // 0xc8
	private UISwitchTween m_enterTween; // 0xd0
	private AnimationSwitchTween m_switchTween; // 0xd8
	private AnimationSwitchTween m_maskSwitchTween; // 0xe0
	private Action`3 <onCharSelect>k__BackingField; // 0xe8
	private static DelegateBridge __Hotfix0_get_hotspotGo; // 0x0
	private static DelegateBridge __Hotfix0_get_onCharSelect; // 0x8
	private static DelegateBridge __Hotfix0_set_onCharSelect; // 0x10
	private static DelegateBridge __Hotfix0_get_layoutElement; // 0x18
	private static DelegateBridge __Hotfix0_RenderGiveUpView; // 0x20
	private static DelegateBridge __Hotfix0_RenderCharView; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0_PlayEnterAnim; // 0x38
	private static DelegateBridge __Hotfix0_ResetEnterAnim; // 0x40
	private static DelegateBridge __Hotfix0_OnCharSelect; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public GameObject hotspotGo { get; }
	private Action`3 onCharSelect { get; set; }
	public LayoutElement layoutElement { get; }

	// RVA: 0x2cccff4 VA: 0x75952e4ff4
	public GameObject get_hotspotGo() { }
	// RVA: 0x2ccd05c VA: 0x75952e505c
	private Action`3 get_onCharSelect() { }
	// RVA: 0x2ccd0c4 VA: 0x75952e50c4
	public Void set_onCharSelect(Action`3 value) { }
	// RVA: 0x2ccd148 VA: 0x75952e5148
	public LayoutElement get_layoutElement() { }
	// RVA: 0x2ccd1b0 VA: 0x75952e51b0
	public Void RenderGiveUpView(Boolean isSelected, Boolean haveAnySelect) { }
	// RVA: 0x2ccd52c VA: 0x75952e552c
	public Void RenderCharView(Int32 index, String groupId, Boolean isGroup, Boolean isCharSelect, Boolean haveAnySelect, ClimbTowerSquadExpansionCharModel charModel, Single spacing) { }
	// RVA: 0x2ccd288 VA: 0x75952e5288
	private Void _InitIfNot() { }
	// RVA: 0x2ccd824 VA: 0x75952e5824
	public IEnumerator PlayEnterAnim(Action tickAction) { }
	// RVA: 0x2ccd91c VA: 0x75952e591c
	public Void ResetEnterAnim() { }
	// RVA: 0x2ccd99c VA: 0x75952e599c
	public Void OnCharSelect() { }
	// RVA: 0x2ccda98 VA: 0x75952e5a98
	public Void .ctor() { }
}
```