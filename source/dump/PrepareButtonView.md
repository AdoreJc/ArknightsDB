# PrepareButtonView

**Namespace:** ` `


## Fields

- `GameObject _container`

- `TwoStateToggle _btnToggle`

- `UIAnimationLocation _activeTween`

- `Boolean m_isInited`

- `AnimationSwitchTween m_switchTween`


## Methods

- `Void _InitIfNot()`

- `Void SetButtonVisible(Boolean)`

- `Void SetButtonActive(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class PrepareButtonView : IHotfixable
{
	private GameObject _container; // 0x10
	private TwoStateToggle _btnToggle; // 0x18
	private UIAnimationLocation _activeTween; // 0x20
	private Boolean m_isInited; // 0x30
	private AnimationSwitchTween m_switchTween; // 0x38
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_SetButtonVisible; // 0x8
	private static DelegateBridge __Hotfix0_SetButtonActive; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x299fd30 VA: 0x7594fb7d30
	private Void _InitIfNot() { }
	// RVA: 0x299f7a4 VA: 0x7594fb77a4
	public Void SetButtonVisible(Boolean v) { }
	// RVA: 0x299f880 VA: 0x7594fb7880
	public Void SetButtonActive(Boolean isActive) { }
	// RVA: 0x299fe14 VA: 0x7594fb7e14
	public Void .ctor() { }
}
```