# ClimbTowerSquadExpansionSlotItemView

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `LayoutElement _layoutElement`

- `Single _charItemSpacing`

- `SimpleLayoutContent _charList`

- `ClimbTowerSquadExpansionCharItemView _charItemPrefab`

- `UIAnimationLocation _fallAnim`

- `CanvasGroup _spCanvasGroup`

- `Single _spPanelTweenDuration`

- `Text _textSpName`

- `UIAtlasImage _imageChrPortrait`

- `Boolean m_isGroupedCharSlot`

- `Boolean m_isGroupSelect`

- `Boolean m_haveAnySelect`

- `String m_selectCharId`

- `IClimbTowerExpansionSlot m_slotModel`

- `Adapter m_adapter`

- `FadeSwitchTween m_fadeTween`

- `Boolean m_hasInited`

- `String m_portraitCache`


## Methods

- `Void set_onCharSelect(Action`3)`

- `Void Render(String, Boolean, Boolean, IClimbTowerExpansionSlot)`

- `Void _InitIfNot()`

- `Void _UpdateLayoutElement()`

- `Void ResetAnim()`

- `IEnumerator PlayFallAnim()`

- `IEnumerator PlayExpandAnim()`

- `Void RegisterTutorialGo()`

- `Void <PlayExpandAnim>b__28_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerSquadExpansionSlotItemView : MonoBehaviour, IHotfixable
{
	private LayoutElement _layoutElement; // 0x18
	private Single _charItemSpacing; // 0x20
	private SimpleLayoutContent _charList; // 0x28
	private ClimbTowerSquadExpansionCharItemView _charItemPrefab; // 0x30
	private UIAnimationLocation _fallAnim; // 0x38
	private CanvasGroup _spCanvasGroup; // 0x48
	private Single _spPanelTweenDuration; // 0x50
	private Text _textSpName; // 0x58
	private UIAtlasImage _imageChrPortrait; // 0x60
	private Boolean m_isGroupedCharSlot; // 0x68
	private Boolean m_isGroupSelect; // 0x69
	private Boolean m_haveAnySelect; // 0x6a
	private String m_selectCharId; // 0x70
	private IClimbTowerExpansionSlot m_slotModel; // 0x78
	private Adapter m_adapter; // 0x80
	private List`1 m_charItemList; // 0x88
	private FadeSwitchTween m_fadeTween; // 0x90
	private Boolean m_hasInited; // 0x98
	private String m_portraitCache; // 0xa0
	private Action`3 <onCharSelect>k__BackingField; // 0xa8
	private static DelegateBridge __Hotfix0_get_onCharSelect; // 0x0
	private static DelegateBridge __Hotfix0_set_onCharSelect; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__UpdateLayoutElement; // 0x20
	private static DelegateBridge __Hotfix0_ResetAnim; // 0x28
	private static DelegateBridge __Hotfix0_PlayFallAnim; // 0x30
	private static DelegateBridge __Hotfix0_PlayExpandAnim; // 0x38
	private static DelegateBridge __Hotfix0_RegisterTutorialGo; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	private Action`3 onCharSelect { get; set; }

	// RVA: 0x2ccdc10 VA: 0x75952e5c10
	private Action`3 get_onCharSelect() { }
	// RVA: 0x2ccdc78 VA: 0x75952e5c78
	public Void set_onCharSelect(Action`3 value) { }
	// RVA: 0x2ccdcfc VA: 0x75952e5cfc
	public Void Render(String selectCharId, Boolean isGroupSelect, Boolean haveAnySelect, IClimbTowerExpansionSlot slotModel) { }
	// RVA: 0x2cce0dc VA: 0x75952e60dc
	private Void _InitIfNot() { }
	// RVA: 0x2cce2cc VA: 0x75952e62cc
	private Void _UpdateLayoutElement() { }
	// RVA: 0x2cce77c VA: 0x75952e677c
	public Void ResetAnim() { }
	// RVA: 0x2cce91c VA: 0x75952e691c
	public IEnumerator PlayFallAnim() { }
	// RVA: 0x2cce9f0 VA: 0x75952e69f0
	public IEnumerator PlayExpandAnim() { }
	// RVA: 0x2cceac4 VA: 0x75952e6ac4
	public Void RegisterTutorialGo() { }
	// RVA: 0x2ccecec VA: 0x75952e6cec
	public Void .ctor() { }
	// RVA: 0x2ccedb8 VA: 0x75952e6db8
	private Void <PlayExpandAnim>b__28_0() { }
}
```