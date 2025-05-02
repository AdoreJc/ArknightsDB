# RuneSquadCardView

**Namespace:** `Torappu.UI.Squad`


## Fields

- `GameObject _panelEmpty`

- `GameObject _panelLock`

- `GameObject _panelActive`

- `Single _cardScale`

- `Options m_optionsCache`

- `UICharacterCardPanel m_charCardPanel`

- `Boolean m_isInited`

- `Int32 m_indexCache`


## Methods

- `Void set_onClick(Action`1)`

- `Void _InitIfNot()`

- `Void RenderCard(Options)`

- `Void EventOnClick()`

- `Void _InvokeOnClick()`

- `Void <_InitIfNot>b__13_0(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Squad
public class RuneSquadCardView : MonoBehaviour, IHotfixable
{
	private GameObject _panelEmpty; // 0x18
	private GameObject _panelLock; // 0x20
	private GameObject _panelActive; // 0x28
	private Single _cardScale; // 0x30
	private Options m_optionsCache; // 0x38
	private UICharacterCardPanel m_charCardPanel; // 0x50
	private Boolean m_isInited; // 0x58
	private Int32 m_indexCache; // 0x5c
	private Action`1 m_onClick; // 0x60
	private static DelegateBridge __Hotfix0_get_onClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onClick; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_RenderCard; // 0x18
	private static DelegateBridge __Hotfix0_EventOnClick; // 0x20
	private static DelegateBridge __Hotfix0__InvokeOnClick; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public Action`1 onClick { get; set; }

	// RVA: 0x23c3200 VA: 0x75949db200
	public Action`1 get_onClick() { }
	// RVA: 0x23c3268 VA: 0x75949db268
	public Void set_onClick(Action`1 value) { }
	// RVA: 0x23c32ec VA: 0x75949db2ec
	private Void _InitIfNot() { }
	// RVA: 0x23c3504 VA: 0x75949db504
	public Void RenderCard(Options options) { }
	// RVA: 0x23c3634 VA: 0x75949db634
	public Void EventOnClick() { }
	// RVA: 0x23c369c VA: 0x75949db69c
	private Void _InvokeOnClick() { }
	// RVA: 0x23c3740 VA: 0x75949db740
	public Void .ctor() { }
	// RVA: 0x23c37bc VA: 0x75949db7bc
	private Void <_InitIfNot>b__13_0(Int32 _) { }
}
```