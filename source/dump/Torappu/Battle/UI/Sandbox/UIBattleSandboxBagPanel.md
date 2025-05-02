# UIBattleSandboxBagPanel

**Namespace:** `Torappu.Battle.UI.Sandbox`


## Fields

- `SimpleLayoutContent _resList`

- `SimpleLayoutContent _totalCountList`

- `Text _goldText`

- `Text _coinText`

- `Transform _emptyIcon`

- `SandboxGameMode m_gameMode`

- `SandboxItemListAdapter m_resAdapter`

- `SandboxSmallItemListAdapter m_totalCountList`

- `Boolean m_hasInited`

- `Action m_callback`


## Properties

- `SandboxGameMode sandboxGameMode`


## Methods

- `SandboxGameMode get_sandboxGameMode()`

- `Void Init()`

- `Void _InitIfNot()`

- `Void OnItemCollect(String, Int32)`

- `Void Render(Action)`

- `Void CloseBagPanel()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.Sandbox
public class UIBattleSandboxBagPanel : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _resList; // 0x18
	private SimpleLayoutContent _totalCountList; // 0x20
	private Text _goldText; // 0x28
	private Text _coinText; // 0x30
	private Transform _emptyIcon; // 0x38
	private SandboxGameMode m_gameMode; // 0x40
	private SandboxItemListAdapter m_resAdapter; // 0x48
	private SandboxSmallItemListAdapter m_totalCountList; // 0x50
	private Boolean m_hasInited; // 0x58
	private Action m_callback; // 0x60
	private static DelegateBridge __Hotfix0_get_sandboxGameMode; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_OnItemCollect; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge __Hotfix0_CloseBagPanel; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	private SandboxGameMode sandboxGameMode { get; }

	// RVA: 0x2091380 VA: 0x75946a9380
	private SandboxGameMode get_sandboxGameMode() { }
	// RVA: 0x2091430 VA: 0x75946a9430
	public Void Init() { }
	// RVA: 0x2091498 VA: 0x75946a9498
	private Void _InitIfNot() { }
	// RVA: 0x209188c VA: 0x75946a988c
	public Void OnItemCollect(String itemId, Int32 count) { }
	// RVA: 0x2091a80 VA: 0x75946a9a80
	public Void Render(Action callback) { }
	// RVA: 0x2091cd4 VA: 0x75946a9cd4
	public Void CloseBagPanel() { }
	// RVA: 0x2091d50 VA: 0x75946a9d50
	public Void .ctor() { }
}
```