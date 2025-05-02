# HomeCheckInGridView

**Namespace:** `Torappu.UI.Home`


## Fields

- `SimpleLayoutContent _content`

- `Text _textTitle`

- `Text _textDesc`

- `Boolean m_hasInited`

- `Adapter m_adapter`

- `Int32 m_cachedCurrCheckInIndex`

- `Boolean m_cachedCanCheckIn`

- `Boolean m_cachedIsJustCheckIn`

- `Int32 m_cachedFocusIndex`


## Methods

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeCheckInGridView : DataBinder`1, IHotfixable
{
	private SimpleLayoutContent _content; // 0x20
	private Text _textTitle; // 0x28
	private Text _textDesc; // 0x30
	private Boolean m_hasInited; // 0x38
	private Adapter m_adapter; // 0x40
	private List`1 m_cachedItemList; // 0x48
	private Int32 m_cachedCurrCheckInIndex; // 0x50
	private Boolean m_cachedCanCheckIn; // 0x54
	private Boolean m_cachedIsJustCheckIn; // 0x55
	private Int32 m_cachedFocusIndex; // 0x58
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2830178 VA: 0x7594e48178
	public override Void OnValueChanged(HomeCheckInProperty property) { }
	// RVA: 0x28302a0 VA: 0x7594e482a0
	private Void _InitIfNot() { }
	// RVA: 0x2830404 VA: 0x7594e48404
	public Void .ctor() { }
}
```