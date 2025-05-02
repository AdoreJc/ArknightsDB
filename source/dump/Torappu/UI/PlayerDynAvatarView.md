# PlayerDynAvatarView

**Namespace:** `Torappu.UI`


## Fields

- `UIAnimationLocation _animLocation`

- `UISpineLocation _spineLocation`

- `UIColorGraphic _colorGraphic`

- `Tween m_animTween`


## Properties

- `UIColorGraphic colorGraphic`


## Methods

- `UIColorGraphic get_colorGraphic()`

- `Void OnEnable()`

- `Void _ReplayAnimation()`

- `Void _ReplaySpine()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class PlayerDynAvatarView : MonoBehaviour, IHotfixable
{
	private UIAnimationLocation _animLocation; // 0x18
	private UISpineLocation _spineLocation; // 0x28
	private UIColorGraphic _colorGraphic; // 0x38
	private Tween m_animTween; // 0x40
	private static DelegateBridge __Hotfix0_get_colorGraphic; // 0x0
	private static DelegateBridge __Hotfix0_OnEnable; // 0x8
	private static DelegateBridge __Hotfix0__ReplayAnimation; // 0x10
	private static DelegateBridge __Hotfix0__ReplaySpine; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public UIColorGraphic colorGraphic { get; }

	// RVA: 0x2278b5c VA: 0x7594890b5c
	public UIColorGraphic get_colorGraphic() { }
	// RVA: 0x2278bc4 VA: 0x7594890bc4
	private Void OnEnable() { }
	// RVA: 0x2278c34 VA: 0x7594890c34
	private Void _ReplayAnimation() { }
	// RVA: 0x2278d78 VA: 0x7594890d78
	private Void _ReplaySpine() { }
	// RVA: 0x2278e10 VA: 0x7594890e10
	public Void .ctor() { }
}
```