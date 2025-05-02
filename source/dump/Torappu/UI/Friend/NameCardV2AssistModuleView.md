# NameCardV2AssistModuleView

**Namespace:** `Torappu.UI.Friend`


## Fields

- `Image _bgImg`

- `SimpleLayoutContent _assistCharContent`

- `UIAnimationLocation _switchAnim`

- `UIAnimationLocation _switchIconAnim`

- `Button _openAssistStateBtn`

- `UIColorGraphic _clickColorGraphic`

- `AnimationSwitchTween m_switchTween`

- `Boolean m_hasInited`

- `Tween m_switchIconTween`

- `NameCardV2AssistModuleModel m_cachedModel`

- `AssistCharAdapter m_adapter`


## Properties

- `Boolean isSwitchTweenShow`


## Methods

- `Boolean get_isSwitchTweenShow()`

- `Void _InitIfNot()`

- `Void OpenAssistState()`

- `Void SwitchModuleStyle()`

- `Void <>xLuaBaseProxy_OnApplyStyle(NameCardV2SkinStyle)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class NameCardV2AssistModuleView : NameCardV2BaseRemovableModuleView`1
{
	private const Int32 ASSIST_CHAR_SLOT; // 0x0
	private Image _bgImg; // 0xb8
	private Image[] _coloredIcons; // 0xc0
	private Text[] _coloredTexts; // 0xc8
	private SimpleLayoutContent _assistCharContent; // 0xd0
	private UIAnimationLocation _switchAnim; // 0xd8
	private UIAnimationLocation _switchIconAnim; // 0xe8
	private GameObject[] _switchIconGos; // 0xf8
	private Button _openAssistStateBtn; // 0x100
	private UIColorGraphic _clickColorGraphic; // 0x108
	private AnimationSwitchTween m_switchTween; // 0x110
	private Boolean m_hasInited; // 0x118
	private Tween m_switchIconTween; // 0x120
	private NameCardV2AssistModuleModel m_cachedModel; // 0x128
	private AssistCharAdapter m_adapter; // 0x130
	private static DelegateBridge __Hotfix0_get_isSwitchTweenShow; // 0x0
	private static DelegateBridge __Hotfix0_OnModuleViewRendered; // 0x8
	private static DelegateBridge __Hotfix0_OnApplyStyle; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0_OpenAssistState; // 0x20
	private static DelegateBridge __Hotfix0_SwitchModuleStyle; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public Boolean isSwitchTweenShow { get; }

	// RVA: 0x28df50c VA: 0x7594ef750c
	public Boolean get_isSwitchTweenShow() { }
	// RVA: 0x28df580 VA: 0x7594ef7580
	public override Void OnModuleViewRendered(NameCardV2AssistModuleModel model) { }
	// RVA: 0x28df80c VA: 0x7594ef780c
	protected override Void OnApplyStyle(NameCardV2SkinStyle style) { }
	// RVA: 0x28df6c8 VA: 0x7594ef76c8
	private Void _InitIfNot() { }
	// RVA: 0x28dfc04 VA: 0x7594ef7c04
	public Void OpenAssistState() { }
	// RVA: 0x28dfcb4 VA: 0x7594ef7cb4
	public Void SwitchModuleStyle() { }
	// RVA: 0x28dff8c VA: 0x7594ef7f8c
	public Void .ctor() { }
	// RVA: 0x28e001c VA: 0x7594ef801c
	private Void <>xLuaBaseProxy_OnApplyStyle(NameCardV2SkinStyle P0) { }
}
```