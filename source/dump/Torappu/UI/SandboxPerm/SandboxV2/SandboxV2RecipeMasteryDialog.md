# SandboxV2RecipeMasteryDialog

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `UIRenderTextureImage _blurBackground`

- `Image _foodIconImage`

- `Text _foodNameText`

- `Text _foodUsageText`

- `Text _foodDescText`

- `SimpleLayoutContent _goodContent`

- `UIAnimationLocation _animationLocation`

- `Adapter m_adapter`

- `Single m_clipLength`

- `UIItemViewModel m_cachedItem`

- `Int32 m_goodCount`

- `UIAnimationTween m_animationTween`


## Methods

- `Void OnConfirmEvent()`

- `Void PlayAudio()`

- `Void _ResetAnimation()`

- `UIRenderTextureImage <>xLuaBaseProxy_GetBlurTarget()`

- `Void <>xLuaBaseProxy_OnInit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2RecipeMasteryDialog : UICompDialog`1
{
	private UIRenderTextureImage _blurBackground; // 0x48
	private Image _foodIconImage; // 0x50
	private Text _foodNameText; // 0x58
	private Text _foodUsageText; // 0x60
	private Text _foodDescText; // 0x68
	private GameObject[] _successPanels; // 0x70
	private GameObject[] _failedPanels; // 0x78
	private SimpleLayoutContent _goodContent; // 0x80
	private UIAnimationLocation _animationLocation; // 0x88
	private Adapter m_adapter; // 0x98
	private Single m_clipLength; // 0xa0
	private UIItemViewModel m_cachedItem; // 0xa8
	private Int32 m_goodCount; // 0xb0
	private UIAnimationTween m_animationTween; // 0xb8
	private static DelegateBridge __Hotfix0_OnConfirmEvent; // 0x0
	private static DelegateBridge __Hotfix0_PlayAudio; // 0x8
	private static DelegateBridge __Hotfix0_GetBlurTarget; // 0x10
	private static DelegateBridge __Hotfix0_OnInit; // 0x18
	private static DelegateBridge __Hotfix0_OnRender; // 0x20
	private static DelegateBridge __Hotfix0__ResetAnimation; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x24d1d1c VA: 0x7594ae9d1c
	public Void OnConfirmEvent() { }
	// RVA: 0x24d1dd0 VA: 0x7594ae9dd0
	public Void PlayAudio() { }
	// RVA: 0x24d1e78 VA: 0x7594ae9e78
	protected override UIRenderTextureImage GetBlurTarget() { }
	// RVA: 0x24d1ee0 VA: 0x7594ae9ee0
	protected override Void OnInit() { }
	// RVA: 0x24d20e4 VA: 0x7594aea0e4
	protected override Void OnRender(Options input) { }
	// RVA: 0x24d2068 VA: 0x7594aea068
	private Void _ResetAnimation() { }
	// RVA: 0x24d23d8 VA: 0x7594aea3d8
	public Void .ctor() { }
	// RVA: 0x24d2468 VA: 0x7594aea468
	private UIRenderTextureImage <>xLuaBaseProxy_GetBlurTarget() { }
	// RVA: 0x24d2470 VA: 0x7594aea470
	private Void <>xLuaBaseProxy_OnInit() { }
}
```