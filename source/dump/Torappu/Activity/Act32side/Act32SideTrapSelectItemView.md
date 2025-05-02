# Act32SideTrapSelectItemView

**Namespace:** `Torappu.Activity.Act32side`


## Fields

- `UIAtlasImage _iconImg`

- `Text _name`

- `Text _detail`

- `GameObject _selectItem`

- `GameObject _notSelectItem`

- `AnimationWrapper _animWrapper`

- `String _animClip`

- `UIAtlasObject trapHub`

- `Int32 m_index`

- `TemplateTrapViewModel m_viewModel`

- `Tween m_tween`

- `String m_cacheSelectId`


## Methods

- `Void RenderSelectTrap(Int32, TemplateTrapViewModel)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act32side
public class Act32SideTrapSelectItemView : MonoBehaviour, IHotfixable
{
	private const String UI_ICON_IMG; // 0x0
	private UIAtlasImage _iconImg; // 0x18
	private Text _name; // 0x20
	private Text _detail; // 0x28
	private GameObject _selectItem; // 0x30
	private GameObject _notSelectItem; // 0x38
	private AnimationWrapper _animWrapper; // 0x40
	private String _animClip; // 0x48
	public Action`2 onSelectAction; // 0x50
	public UIAtlasObject trapHub; // 0x58
	private Int32 m_index; // 0x60
	private TemplateTrapViewModel m_viewModel; // 0x68
	private Tween m_tween; // 0x70
	private String m_cacheSelectId; // 0x78
	private static DelegateBridge __Hotfix0_RenderSelectTrap; // 0x0
	private static DelegateBridge __Hotfix0_OnClick; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x32574a8 VA: 0x759586f4a8
	public Void RenderSelectTrap(Int32 index, TemplateTrapViewModel viewModel) { }
	// RVA: 0x32576dc VA: 0x759586f6dc
	public Void OnClick() { }
	// RVA: 0x3257760 VA: 0x759586f760
	public Void .ctor() { }
}
```