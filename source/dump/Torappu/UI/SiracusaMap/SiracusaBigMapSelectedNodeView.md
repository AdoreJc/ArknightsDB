# SiracusaBigMapSelectedNodeView

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `UIDynImage _imgLogo`

- `Text _txtName`

- `StageRankView _stageRankView`

- `AnimationWrapper _animationWrapper`

- `UIAtlasImage _imgCornerFlag`

- `UIAtlasObject _atlasObject`

- `Tween m_tween`


## Methods

- `Void <Hide>b__12_0()`

- `Void <>xLuaBaseProxy_Show(Boolean)`

- `Void <>xLuaBaseProxy_Hide(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaBigMapSelectedNodeView : SiracusaMapNodeViewBase
{
	private const String ANIM_SELECT_ENTER; // 0x0
	private const String ANIM_SELECT_EXIT; // 0x0
	private UIDynImage _imgLogo; // 0x28
	private Text _txtName; // 0x30
	private StageRankView _stageRankView; // 0x38
	private AnimationWrapper _animationWrapper; // 0x40
	private UIAtlasImage _imgCornerFlag; // 0x48
	private UIAtlasObject _atlasObject; // 0x50
	private Tween m_tween; // 0x58
	private static DelegateBridge __Hotfix0_GetViewType; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_Show; // 0x10
	private static DelegateBridge __Hotfix0_Hide; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x240bc28 VA: 0x7594a23c28
	public override ViewType GetViewType() { }
	// RVA: 0x240bc90 VA: 0x7594a23c90
	public override Void Render(SiracusaMapMapNodeViewModel viewModel) { }
	// RVA: 0x240bf10 VA: 0x7594a23f10
	public override Void Show(Boolean isFastMode) { }
	// RVA: 0x240c04c VA: 0x7594a2404c
	public override Void Hide(Boolean isFastMode) { }
	// RVA: 0x240c1e4 VA: 0x7594a241e4
	public Void .ctor() { }
	// RVA: 0x240c254 VA: 0x7594a24254
	private Void <Hide>b__12_0() { }
	// RVA: 0x240c270 VA: 0x7594a24270
	private Void <>xLuaBaseProxy_Show(Boolean P0) { }
	// RVA: 0x240c27c VA: 0x7594a2427c
	private Void <>xLuaBaseProxy_Hide(Boolean P0) { }
}
```