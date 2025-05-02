# Act12sidePhotoState

**Namespace:** `Torappu.Activity.Act12side.UI`


## Fields

- `RectTransform _bgRt`

- `GameObject _btnJumpGo`

- `Text _textJumpDesc`

- `Text _textName`

- `Text _textDesc`

- `Image _imgPhoto`

- `Act12sidePhotoStateBean m_stateBean`

- `Boolean m_hasInited`

- `Act12sideStageController m_stageController`


## Properties

- `Act12sideStageController actController`


## Methods

- `Act12sideStageController get_actController()`

- `Void _InitIfNot()`

- `Void _FetchStageController()`

- `Void OnBtnJump()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12side.UI
public class Act12sidePhotoState : PopupFloatState
{
	private RectTransform _bgRt; // 0x70
	private GameObject _btnJumpGo; // 0x78
	private Text _textJumpDesc; // 0x80
	private Text _textName; // 0x88
	private Text _textDesc; // 0x90
	private Image _imgPhoto; // 0x98
	private PhotoSprite[] _photoSpriteList; // 0xa0
	private Act12sidePhotoStateBean m_stateBean; // 0xa8
	private Boolean m_hasInited; // 0xb0
	private Act12sideStageController m_stageController; // 0xb8
	private static DelegateBridge __Hotfix0_get_actController; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__FetchStageController; // 0x18
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x20
	private static DelegateBridge __Hotfix0_OnBtnJump; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	protected Act12sideStageController actController { get; }

	// RVA: 0x345fbdc VA: 0x7595a77bdc
	protected Act12sideStageController get_actController() { }
	// RVA: 0x345fe24 VA: 0x7595a77e24
	protected override Void OnEnter() { }
	// RVA: 0x3460098 VA: 0x7595a78098
	private Void _InitIfNot() { }
	// RVA: 0x345fc88 VA: 0x7595a77c88
	private Void _FetchStageController() { }
	// RVA: 0x346018c VA: 0x7595a7818c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x34601f4 VA: 0x7595a781f4
	public Void OnBtnJump() { }
	// RVA: 0x34602c4 VA: 0x7595a782c4
	public Void .ctor() { }
	// RVA: 0x3460370 VA: 0x7595a78370
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```