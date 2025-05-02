# Act32SideTrapItemView

**Namespace:** `Torappu.Activity.Act32side`


## Fields

- `UIAtlasImage _iconImg`

- `GameObject _selectBar`

- `GameObject _unlockPart`

- `GameObject _lockedPart`

- `UIAtlasImage _tinyIcon`

- `Text _name`

- `Text _detail`

- `GameObject _isNewFlag`

- `Text _unlockText`

- `AnimationWrapper _animationWrapper`

- `String _clipName`

- `UIAtlasObject trapHub`

- `Int32 m_currentSelectCount`

- `Int32 m_maxSelectCount`

- `Boolean m_isSelectedCache`

- `TemplateTrapViewModel m_trapViewModel`

- `Tween m_tween`


## Methods

- `Void RenderView(Int32, Int32, TemplateTrapViewModel)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act32side
public class Act32SideTrapItemView : MonoBehaviour, IHotfixable
{
	private const String SMALL_ICON_PATH; // 0x0
	private UIAtlasImage _iconImg; // 0x18
	private GameObject _selectBar; // 0x20
	private GameObject _unlockPart; // 0x28
	private GameObject _lockedPart; // 0x30
	private UIAtlasImage _tinyIcon; // 0x38
	private Text _name; // 0x40
	private Text _detail; // 0x48
	private GameObject _isNewFlag; // 0x50
	private Text _unlockText; // 0x58
	private AnimationWrapper _animationWrapper; // 0x60
	private String _clipName; // 0x68
	public Action`2 onSelectAction; // 0x70
	public UIAtlasObject trapHub; // 0x78
	private Int32 m_currentSelectCount; // 0x80
	private Int32 m_maxSelectCount; // 0x84
	private Boolean m_isSelectedCache; // 0x88
	private TemplateTrapViewModel m_trapViewModel; // 0x90
	private Tween m_tween; // 0x98
	private static DelegateBridge __Hotfix0_RenderView; // 0x0
	private static DelegateBridge __Hotfix0_OnClick; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3257080 VA: 0x759586f080
	public Void RenderView(Int32 currentSelectCount, Int32 maxSelectCount, TemplateTrapViewModel trapViewModel) { }
	// RVA: 0x3257378 VA: 0x759586f378
	public Void OnClick() { }
	// RVA: 0x3257438 VA: 0x759586f438
	public Void .ctor() { }
}
```