# CarvingHomeEntryPageGroupView

**Namespace:** `Torappu.UI.Carving`


## Fields

- `SimpleLayoutContent _content`

- `Boolean m_hasInited`

- `Adapter m_adapter`

- `String m_cacheFocusItemId`


## Methods

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingHomeEntryPageGroupView : DataBinder`1, IHotfixable
{
	private SimpleLayoutContent _content; // 0x20
	private Boolean m_hasInited; // 0x28
	private Adapter m_adapter; // 0x30
	private List`1 m_cachedItemList; // 0x38
	private String m_cacheFocusItemId; // 0x40
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2d93460 VA: 0x75953ab460
	public override Void OnValueChanged(CarvingHomeEntryProperty property) { }
	// RVA: 0x2d93558 VA: 0x75953ab558
	private Void _InitIfNot() { }
	// RVA: 0x2d936bc VA: 0x75953ab6bc
	public Void .ctor() { }
}
```