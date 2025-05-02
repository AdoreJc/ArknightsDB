# SiracusaSmallMapSelectedNodeView

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `UIDynImage _imgLogo`

- `Text _txtName`

- `AnimationWrapper _animationWrapper`

- `Tween m_tween`


## Methods

- `Void <Hide>b__9_0()`

- `Void <>xLuaBaseProxy_Show(Boolean)`

- `Void <>xLuaBaseProxy_Hide(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaSmallMapSelectedNodeView : SiracusaMapNodeViewBase
{
	private const String ANIM_SELECT_ENTER; // 0x0
	private const String ANIM_SELECT_EXIT; // 0x0
	private UIDynImage _imgLogo; // 0x28
	private Text _txtName; // 0x30
	private AnimationWrapper _animationWrapper; // 0x38
	private Tween m_tween; // 0x40
	private static DelegateBridge __Hotfix0_GetViewType; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_Show; // 0x10
	private static DelegateBridge __Hotfix0_Hide; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2415764 VA: 0x7594a2d764
	public override ViewType GetViewType() { }
	// RVA: 0x24157cc VA: 0x7594a2d7cc
	public override Void Render(SiracusaMapMapNodeViewModel viewModel) { }
	// RVA: 0x2415984 VA: 0x7594a2d984
	public override Void Show(Boolean isFastMode) { }
	// RVA: 0x2415ad4 VA: 0x7594a2dad4
	public override Void Hide(Boolean isFastMode) { }
	// RVA: 0x2415c6c VA: 0x7594a2dc6c
	public Void .ctor() { }
	// RVA: 0x2415cd8 VA: 0x7594a2dcd8
	private Void <Hide>b__9_0() { }
	// RVA: 0x2415cf4 VA: 0x7594a2dcf4
	private Void <>xLuaBaseProxy_Show(Boolean P0) { }
	// RVA: 0x2415cfc VA: 0x7594a2dcfc
	private Void <>xLuaBaseProxy_Hide(Boolean P0) { }
}
```