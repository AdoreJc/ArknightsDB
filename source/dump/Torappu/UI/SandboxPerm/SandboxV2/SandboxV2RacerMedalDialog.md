# SandboxV2RacerMedalDialog

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `RectTransform _rectBack`

- `SimpleLayoutContent _content`

- `Adapter m_adapter`

- `Boolean m_hasInited`


## Methods

- `Void EventOnBackClicked()`

- `Void _InitIfNot()`

- `Void <>xLuaBaseProxy_OnInit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2RacerMedalDialog : UICompDialog`1, IHotfixable
{
	private const Int32 MEDAL_COUNT_PER_ROW; // 0x0
	private RectTransform _rectBack; // 0x48
	private SimpleLayoutContent _content; // 0x50
	private Adapter m_adapter; // 0x58
	private Boolean m_hasInited; // 0x60
	private List`1 m_medalList; // 0x68
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_OnRender; // 0x8
	private static DelegateBridge __Hotfix0_EventOnBackClicked; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x25e7d94 VA: 0x7594bffd94
	protected override Void OnInit() { }
	// RVA: 0x25e7f68 VA: 0x7594bfff68
	protected override Void OnRender(Options input) { }
	// RVA: 0x25e8250 VA: 0x7594c00250
	public Void EventOnBackClicked() { }
	// RVA: 0x25e7e08 VA: 0x7594bffe08
	private Void _InitIfNot() { }
	// RVA: 0x25e83b8 VA: 0x7594c003b8
	public Void .ctor() { }
	// RVA: 0x25e849c VA: 0x7594c0049c
	private Void <>xLuaBaseProxy_OnInit() { }
}
```