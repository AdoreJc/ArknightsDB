# CrisisV2RuneDetailView

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `CanvasGroup _canvasEmpty`

- `CanvasGroup _canvasHardMode`

- `CrisisV2RuneDetailSlotView _slotView`

- `CrisisV2RuneDetailPackView _packView`

- `GameObject _panelFocus`

- `UIAtlasImage _imgBgGlow`

- `Color _colBgGlowNormal`

- `Color _colBgGlowHard`

- `Boolean m_hasInited`

- `FadeSwitchTween m_emptyTween`

- `FadeSwitchTween m_hardModeTween`


## Methods

- `Void RegisterTutorialGo()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2RuneDetailView : DataBinder`1
{
	private CanvasGroup _canvasEmpty; // 0x20
	private CanvasGroup _canvasHardMode; // 0x28
	private CrisisV2RuneDetailSlotView _slotView; // 0x30
	private CrisisV2RuneDetailPackView _packView; // 0x38
	private GameObject _panelFocus; // 0x40
	private UIAtlasImage _imgBgGlow; // 0x48
	private Color _colBgGlowNormal; // 0x50
	private Color _colBgGlowHard; // 0x60
	private Boolean m_hasInited; // 0x70
	private FadeSwitchTween m_emptyTween; // 0x78
	private FadeSwitchTween m_hardModeTween; // 0x80
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_RegisterTutorialGo; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2c13184 VA: 0x759522b184
	public override Void OnValueChanged(CrisisV2MapProp property) { }
	// RVA: 0x2c1343c VA: 0x759522b43c
	public Void RegisterTutorialGo() { }
	// RVA: 0x2c132e4 VA: 0x759522b2e4
	private Void _InitIfNot() { }
	// RVA: 0x2c13564 VA: 0x759522b564
	public Void .ctor() { }
}
```