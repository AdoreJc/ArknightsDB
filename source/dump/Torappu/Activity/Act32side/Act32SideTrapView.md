# Act32SideTrapView

**Namespace:** `Torappu.Activity.Act32side`


## Fields

- `AnimationWrapper _animationWrapper`

- `UIAtlasObject _atlasHub`

- `Text _selectCount`

- `GameObject _saveBtn`

- `Action m_onSaveSquad`


## Methods

- `Void OnClickSaveSquad()`

- `Void RenderView(TemplateTrapGroupViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act32side
public class Act32SideTrapView : TemplateTrapView, IHotfixable
{
	private AnimationWrapper _animationWrapper; // 0x20
	private List`1 _trapItemViewList; // 0x28
	private List`1 _selectedViewList; // 0x30
	private UIAtlasObject _atlasHub; // 0x38
	private Text _selectCount; // 0x40
	private GameObject _saveBtn; // 0x48
	private Action`2 m_onSelectAction; // 0x50
	private Action m_onSaveSquad; // 0x58
	private static DelegateBridge __Hotfix0_SetAction; // 0x0
	private static DelegateBridge __Hotfix0_StartFadeInTween; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0_OnClickSaveSquad; // 0x18
	private static DelegateBridge __Hotfix0_RenderView; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x3257dc8 VA: 0x759586fdc8
	public override Void SetAction(Action`2 selectAction, Action onSaveSquad) { }
	// RVA: 0x3257e64 VA: 0x759586fe64
	public override Tween StartFadeInTween() { }
	// RVA: 0x3257ef8 VA: 0x759586fef8
	public override Void OnValueChanged(TemplateTrapProperty property) { }
	// RVA: 0x32583c8 VA: 0x75958703c8
	public Void OnClickSaveSquad() { }
	// RVA: 0x3257fa0 VA: 0x759586ffa0
	public Void RenderView(TemplateTrapGroupViewModel viewModel) { }
	// RVA: 0x3258464 VA: 0x7595870464
	public Void .ctor() { }
}
```