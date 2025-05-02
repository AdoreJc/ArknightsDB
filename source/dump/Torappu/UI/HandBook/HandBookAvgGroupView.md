# HandBookAvgGroupView

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `SimpleLayoutContent _content`

- `Text _titleText`

- `Adapter m_adapter`

- `Boolean m_isInited`


## Methods

- `Void set_onAvgItemClick(Action`1)`

- `Void _InitIfNot()`

- `Void Render(HandBookAvgGroupViewModel)`

- `Void _OnAvgItemClicked(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookAvgGroupView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _content; // 0x18
	private Text _titleText; // 0x20
	private Adapter m_adapter; // 0x28
	private Boolean m_isInited; // 0x30
	private Action`1 <onAvgItemClick>k__BackingField; // 0x38
	private static DelegateBridge __Hotfix0_get_onAvgItemClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onAvgItemClick; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge __Hotfix0__OnAvgItemClicked; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private Action`1 onAvgItemClick { get; set; }

	// RVA: 0x2ea9008 VA: 0x75954c1008
	private Action`1 get_onAvgItemClick() { }
	// RVA: 0x2ea9070 VA: 0x75954c1070
	public Void set_onAvgItemClick(Action`1 value) { }
	// RVA: 0x2ea90f4 VA: 0x75954c10f4
	private Void _InitIfNot() { }
	// RVA: 0x2ea92a4 VA: 0x75954c12a4
	public Void Render(HandBookAvgGroupViewModel groupViewModel) { }
	// RVA: 0x2ea9398 VA: 0x75954c1398
	private Void _OnAvgItemClicked(String storyId) { }
	// RVA: 0x2ea9450 VA: 0x75954c1450
	public Void .ctor() { }
}
```