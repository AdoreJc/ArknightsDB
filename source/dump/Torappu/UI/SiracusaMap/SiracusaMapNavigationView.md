# SiracusaMapNavigationView

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `GameObject _objExtraPart`

- `SiracusaMapNavigationCharButtonView _entryCharCardBtn`

- `AnimationWrapper _foldAnimWrapper`

- `CanvasGroup _canvas`

- `Boolean m_isFold`

- `Boolean m_isPlayingFoldAnim`

- `String m_actId`

- `Boolean m_isInited`

- `FadeSwitchTween m_fadeTween`

- `SiracusaMapController <closure>k__BackingField`


## Properties

- `SiracusaMapController closure`


## Methods

- `SiracusaMapController get_closure()`

- `Void set_closure(SiracusaMapController)`

- `Void set_onNavigationClick(Action`2)`

- `Void _InitIfNot()`

- `String _GetAnimNameByState(Boolean)`

- `Void _InitEntryFoldAnim(String, Boolean)`

- `Void _PlayEntryFoldAnim(Boolean)`

- `Void _OnNavigationBtnClick(String, NavigationType)`

- `Void _RenderDotsPart(Int32)`

- `Boolean _CheckIfNaviNeedShowNew(String)`

- `Void OnFoldClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaMapNavigationView : DataBinder`1
{
	private List`1 _entryStageBtnList; // 0x20
	private GameObject _objExtraPart; // 0x28
	private SiracusaMapNavigationCharButtonView _entryCharCardBtn; // 0x30
	private List`1 _objDots; // 0x38
	private AnimationWrapper _foldAnimWrapper; // 0x40
	private CanvasGroup _canvas; // 0x48
	private const String FOLD_ANIM; // 0x0
	private const String UNFOLD_ANIM; // 0x0
	private Boolean m_isFold; // 0x50
	private Boolean m_isPlayingFoldAnim; // 0x51
	private String m_actId; // 0x58
	private Boolean m_isInited; // 0x60
	private FadeSwitchTween m_fadeTween; // 0x68
	private SiracusaMapController <closure>k__BackingField; // 0x70
	private Action`2 <onNavigationClick>k__BackingField; // 0x78
	private static DelegateBridge __Hotfix0_get_closure; // 0x0
	private static DelegateBridge __Hotfix0_set_closure; // 0x8
	private static DelegateBridge __Hotfix0_get_onNavigationClick; // 0x10
	private static DelegateBridge __Hotfix0_set_onNavigationClick; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0__GetAnimNameByState; // 0x28
	private static DelegateBridge __Hotfix0__InitEntryFoldAnim; // 0x30
	private static DelegateBridge __Hotfix0__PlayEntryFoldAnim; // 0x38
	private static DelegateBridge __Hotfix0__OnNavigationBtnClick; // 0x40
	private static DelegateBridge __Hotfix0__RenderDotsPart; // 0x48
	private static DelegateBridge __Hotfix0__CheckIfNaviNeedShowNew; // 0x50
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x58
	private static DelegateBridge __Hotfix0_OnFoldClick; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public SiracusaMapController closure { get; set; }
	public Action`2 onNavigationClick { get; set; }

	// RVA: 0x23dc810 VA: 0x75949f4810
	public SiracusaMapController get_closure() { }
	// RVA: 0x23dc878 VA: 0x75949f4878
	public Void set_closure(SiracusaMapController value) { }
	// RVA: 0x23dc8fc VA: 0x75949f48fc
	public Action`2 get_onNavigationClick() { }
	// RVA: 0x23dc964 VA: 0x75949f4964
	public Void set_onNavigationClick(Action`2 value) { }
	// RVA: 0x23dc9e8 VA: 0x75949f49e8
	private Void _InitIfNot() { }
	// RVA: 0x23dcd1c VA: 0x75949f4d1c
	private String _GetAnimNameByState(Boolean isFold) { }
	// RVA: 0x23dcc64 VA: 0x75949f4c64
	private Void _InitEntryFoldAnim(String animName, Boolean sampleAtStart) { }
	// RVA: 0x23dcdc8 VA: 0x75949f4dc8
	private Void _PlayEntryFoldAnim(Boolean isFold) { }
	// RVA: 0x23dcedc VA: 0x75949f4edc
	private Void _OnNavigationBtnClick(String entryId, NavigationType entryType) { }
	// RVA: 0x23dcfa0 VA: 0x75949f4fa0
	private Void _RenderDotsPart(Int32 dotsShowCount) { }
	// RVA: 0x23dd0c8 VA: 0x75949f50c8
	private Boolean _CheckIfNaviNeedShowNew(String entryId) { }
	// RVA: 0x23dd240 VA: 0x75949f5240
	public override Void OnValueChanged(SiracusaMapPanelMapProperty property) { }
	// RVA: 0x23dd858 VA: 0x75949f5858
	public Void OnFoldClick() { }
	// RVA: 0x23dd8d4 VA: 0x75949f58d4
	public Void .ctor() { }
}
```