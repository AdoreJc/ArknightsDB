# UniEquipUnlockPreviewView

**Namespace:** `Torappu.UI.UniEquip`


## Fields

- `UIFadeFloatPanel _floatPanel`

- `SimpleLayoutContent _content`

- `UIAnimationLocation _animLocation`

- `AnimationSwitchTween m_animSwitchTween`

- `InfoAdapter m_infoAdapter`

- `Boolean m_isInited`

- `Boolean m_isAnimInited`


## Methods

- `Void _InitIfNot()`

- `Void _InitAnimIfNot()`

- `Void _SetVisible(Boolean)`

- `Void _PlayAnim(Boolean)`

- `IEnumerator _InfoEffectAnim(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.UniEquip
public class UniEquipUnlockPreviewView : DataBinder`1
{
	private UIFadeFloatPanel _floatPanel; // 0x20
	private SimpleLayoutContent _content; // 0x28
	private UIAnimationLocation _animLocation; // 0x30
	private AnimationSwitchTween m_animSwitchTween; // 0x40
	private InfoAdapter m_infoAdapter; // 0x48
	private Boolean m_isInited; // 0x50
	private Boolean m_isAnimInited; // 0x51
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__InitAnimIfNot; // 0x10
	private static DelegateBridge __Hotfix0__SetVisible; // 0x18
	private static DelegateBridge __Hotfix0__PlayAnim; // 0x20
	private static DelegateBridge __Hotfix0__InfoEffectAnim; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x230fb5c VA: 0x7594927b5c
	public override Void OnValueChanged(UnlockViewProperty property) { }
	// RVA: 0x230fc40 VA: 0x7594927c40
	private Void _InitIfNot() { }
	// RVA: 0x230fe4c VA: 0x7594927e4c
	private Void _InitAnimIfNot() { }
	// RVA: 0x230fd0c VA: 0x7594927d0c
	private Void _SetVisible(Boolean v) { }
	// RVA: 0x230ff38 VA: 0x7594927f38
	private Void _PlayAnim(Boolean isShow) { }
	// RVA: 0x230ffe4 VA: 0x7594927fe4
	private IEnumerator _InfoEffectAnim(Boolean isShow) { }
	// RVA: 0x23100d4 VA: 0x75949280d4
	public Void .ctor() { }
}
```