# SquadCardViewWithPredefine

**Namespace:** `Torappu.UI.Squad`


## Fields

- `GameObject _panelEmpty`

- `GameObject _panelLock`

- `GameObject _panelActive`

- `GameObject _panelPredefined`

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

- `Void <_InitIfNot>b__14_0(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Squad
public class SquadCardViewWithPredefine : MonoBehaviour, IHotfixable
{
	private GameObject _panelEmpty; // 0x18
	private GameObject _panelLock; // 0x20
	private GameObject _panelActive; // 0x28
	private GameObject _panelPredefined; // 0x30
	private Single _cardScale; // 0x38
	private Options m_optionsCache; // 0x40
	private UICharacterCardPanel m_charCardPanel; // 0x58
	private Boolean m_isInited; // 0x60
	private Int32 m_indexCache; // 0x64
	private Action`1 m_onClick; // 0x68
	private static DelegateBridge __Hotfix0_get_onClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onClick; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_RenderCard; // 0x18
	private static DelegateBridge __Hotfix0_EventOnClick; // 0x20
	private static DelegateBridge __Hotfix0__InvokeOnClick; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public Action`1 onClick { get; set; }

	// RVA: 0x23c4c44 VA: 0x75949dcc44
	public Action`1 get_onClick() { }
	// RVA: 0x23c4cac VA: 0x75949dccac
	public Void set_onClick(Action`1 value) { }
	// RVA: 0x23c4d30 VA: 0x75949dcd30
	private Void _InitIfNot() { }
	// RVA: 0x23c4f48 VA: 0x75949dcf48
	public Void RenderCard(Options options) { }
	// RVA: 0x23c50a4 VA: 0x75949dd0a4
	public Void EventOnClick() { }
	// RVA: 0x23c510c VA: 0x75949dd10c
	private Void _InvokeOnClick() { }
	// RVA: 0x23c51b0 VA: 0x75949dd1b0
	public Void .ctor() { }
	// RVA: 0x23c522c VA: 0x75949dd22c
	private Void <_InitIfNot>b__14_0(Int32 _) { }
}
```