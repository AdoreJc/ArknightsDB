# SiracusaBigMapNormalNodeView

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `UIDynImage _imgLogo`

- `Text _txtName`

- `StageRankView _stageRankView`

- `AnimationWrapper _animationWrapper`

- `UIAtlasImage _imgCornerFlag`

- `UIAtlasObject _atlasObject`

- `SiracusaMapMapNodeViewModel m_viewModel`

- `Tween m_tween`


## Methods

- `Void EventOnNodeClicked()`

- `Void <Show>b__11_0()`

- `Void <>xLuaBaseProxy_Show(Boolean)`

- `Void <>xLuaBaseProxy_Hide(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaBigMapNormalNodeView : SiracusaMapNodeViewBase
{
	private const String ANIM_NORMAL_ENTER; // 0x0
	private UIDynImage _imgLogo; // 0x28
	private Text _txtName; // 0x30
	private StageRankView _stageRankView; // 0x38
	private AnimationWrapper _animationWrapper; // 0x40
	private UIAtlasImage _imgCornerFlag; // 0x48
	private UIAtlasObject _atlasObject; // 0x50
	private SiracusaMapMapNodeViewModel m_viewModel; // 0x58
	private Tween m_tween; // 0x60
	private static DelegateBridge __Hotfix0_GetViewType; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_Show; // 0x10
	private static DelegateBridge __Hotfix0_Hide; // 0x18
	private static DelegateBridge __Hotfix0_EventOnNodeClicked; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x240b5a4 VA: 0x7594a235a4
	public override ViewType GetViewType() { }
	// RVA: 0x240b608 VA: 0x7594a23608
	public override Void Render(SiracusaMapMapNodeViewModel viewModel) { }
	// RVA: 0x240b89c VA: 0x7594a2389c
	public override Void Show(Boolean isFastMode) { }
	// RVA: 0x240ba34 VA: 0x7594a23a34
	public override Void Hide(Boolean isFastMode) { }
	// RVA: 0x240badc VA: 0x7594a23adc
	public Void EventOnNodeClicked() { }
	// RVA: 0x240bb84 VA: 0x7594a23b84
	public Void .ctor() { }
	// RVA: 0x240bbf4 VA: 0x7594a23bf4
	private Void <Show>b__11_0() { }
	// RVA: 0x240bc10 VA: 0x7594a23c10
	private Void <>xLuaBaseProxy_Show(Boolean P0) { }
	// RVA: 0x240bc1c VA: 0x7594a23c1c
	private Void <>xLuaBaseProxy_Hide(Boolean P0) { }
}
```