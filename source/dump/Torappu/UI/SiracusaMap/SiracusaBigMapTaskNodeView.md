# SiracusaBigMapTaskNodeView

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `Graphic _graphicCharCard`

- `GameObject _objAvatar`

- `UIDynImage _imgLogo`

- `Text _txtName`

- `UIDynImage _imgCharAvatar`

- `RectTransform _imgTriangle`

- `Single _defaultWidth`

- `Single _stepWidth`

- `Single _stepCount`

- `Single _stepTime`

- `SiracusaMapMapNodeViewModel m_viewModel`

- `AutoPackSpriteHub m_taskCharAvatarHub`

- `Tweener m_tweener`


## Methods

- `Void _TryToPlayTriangleTween()`

- `Void _StopTween()`

- `Void SetTaskCharAvatarHub(AutoPackSpriteHub)`

- `Void EventOnNodeClicked()`

- `Void <_TryToPlayTriangleTween>b__16_1(Single)`

- `Void <>xLuaBaseProxy_Hide(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaBigMapTaskNodeView : SiracusaMapNodeViewBase
{
	private Graphic _graphicCharCard; // 0x28
	private GameObject _objAvatar; // 0x30
	private UIDynImage _imgLogo; // 0x38
	private Text _txtName; // 0x40
	private UIDynImage _imgCharAvatar; // 0x48
	private RectTransform _imgTriangle; // 0x50
	private Single _defaultWidth; // 0x58
	private Single _stepWidth; // 0x5c
	private Single _stepCount; // 0x60
	private Single _stepTime; // 0x64
	private SiracusaMapMapNodeViewModel m_viewModel; // 0x68
	private AutoPackSpriteHub m_taskCharAvatarHub; // 0x70
	private Tweener m_tweener; // 0x78
	private static DelegateBridge __Hotfix0_GetViewType; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_Hide; // 0x10
	private static DelegateBridge __Hotfix0__TryToPlayTriangleTween; // 0x18
	private static DelegateBridge __Hotfix0__StopTween; // 0x20
	private static DelegateBridge __Hotfix0_SetTaskCharAvatarHub; // 0x28
	private static DelegateBridge __Hotfix0_EventOnNodeClicked; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x240c778 VA: 0x7594a24778
	public override ViewType GetViewType() { }
	// RVA: 0x240c7e0 VA: 0x7594a247e0
	public override Void Render(SiracusaMapMapNodeViewModel viewModel) { }
	// RVA: 0x240cc78 VA: 0x7594a24c78
	public override Void Hide(Boolean isFastMode) { }
	// RVA: 0x240ca18 VA: 0x7594a24a18
	private Void _TryToPlayTriangleTween() { }
	// RVA: 0x240cd04 VA: 0x7594a24d04
	private Void _StopTween() { }
	// RVA: 0x240b3f8 VA: 0x7594a233f8
	public Void SetTaskCharAvatarHub(AutoPackSpriteHub spriteHub) { }
	// RVA: 0x240cd94 VA: 0x7594a24d94
	public Void EventOnNodeClicked() { }
	// RVA: 0x240ce3c VA: 0x7594a24e3c
	public Void .ctor() { }
	// RVA: 0x240ceac VA: 0x7594a24eac
	private Void <_TryToPlayTriangleTween>b__16_1(Single val) { }
	// RVA: 0x240cf18 VA: 0x7594a24f18
	private Void <>xLuaBaseProxy_Hide(Boolean P0) { }
}
```