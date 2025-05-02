# SiracusaOperaFrameHolder

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `SimpleLayoutContent _content`

- `UIIntEvent _onSelectFrame`

- `Boolean m_isInited`

- `Adapter m_adapter`


## Methods

- `Void _InitIfNot()`

- `Void Render(UIPage, List`1, Int32, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaOperaFrameHolder : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _content; // 0x18
	private UIIntEvent _onSelectFrame; // 0x20
	private Boolean m_isInited; // 0x28
	private Adapter m_adapter; // 0x30
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x23faccc VA: 0x7594a12ccc
	private Void _InitIfNot() { }
	// RVA: 0x23fa1e8 VA: 0x7594a121e8
	public Void Render(UIPage page, List`1 viewModelList, Int32 selectIndex, Boolean needRefresh) { }
	// RVA: 0x23fae20 VA: 0x7594a12e20
	public Void .ctor() { }
}
```