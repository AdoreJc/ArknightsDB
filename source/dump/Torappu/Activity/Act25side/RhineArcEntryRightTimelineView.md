# RhineArcEntryRightTimelineView

**Namespace:** `Torappu.Activity.Act25side`


## Fields

- `Image _backLine`

- `Image _availLine`

- `RhineArcTimelineItem _item`

- `Transform _container`

- `LayoutElement _layoutElement`

- `Boolean m_renderFlag`


## Methods

- `Void _RenderIfFirstTime(Int32, Group)`

- `Void Render(Group)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act25side
public class RhineArcEntryRightTimelineView : MonoBehaviour, IHotfixable
{
	private Image _backLine; // 0x18
	private Image _availLine; // 0x20
	private RhineArcTimelineItem _item; // 0x28
	private Transform _container; // 0x30
	private LayoutElement _layoutElement; // 0x38
	private List`1 m_itemList; // 0x40
	private Boolean m_renderFlag; // 0x48
	private static DelegateBridge __Hotfix0__RenderIfFirstTime; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x32735c8 VA: 0x759588b5c8
	private Void _RenderIfFirstTime(Int32 count, Group groupViewModel) { }
	// RVA: 0x3273824 VA: 0x759588b824
	public Void Render(Group groupViewModel) { }
	// RVA: 0x3273a70 VA: 0x759588ba70
	public Void .ctor() { }
}
```