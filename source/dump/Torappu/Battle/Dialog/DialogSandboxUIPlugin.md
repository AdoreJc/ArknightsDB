# DialogSandboxUIPlugin

**Namespace:** `Torappu.Battle.Dialog`


## Fields

- `DialogSandboxUIPluginIconPair _iconPrefab`

- `Button _bag`

- `SimpleLayoutContent _iconRoot`

- `Single _fadeDuration`

- `IconListAdapter m_adapter`

- `Boolean m_inited`


## Methods

- `Void _InitIfNot()`

- `Boolean _ExecuteUIOperation(Command)`

- `Void _UpdateBag(Command)`

- `Void _ExecuteUiOperationItem(Command)`

- `Boolean _ExecuteHeader(Command)`

- `Boolean _ExecuteEnd(Command)`

- `Void _UpdateBag(Boolean)`

- `Void OnBagBtnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Dialog
public class DialogSandboxUIPlugin : MonoBehaviour, IPlugin, IHotfixable
{
	private DialogSandboxUIPluginIconPair _iconPrefab; // 0x18
	private Button _bag; // 0x20
	private SimpleLayoutContent _iconRoot; // 0x28
	private Single _fadeDuration; // 0x30
	private IconListAdapter m_adapter; // 0x38
	private Boolean m_inited; // 0x40
	private List`1 m_iconDatas; // 0x48
	private static DelegateBridge __Hotfix0_GetExecutors; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__ExecuteUIOperation; // 0x10
	private static DelegateBridge __Hotfix0__UpdateBag; // 0x18
	private static DelegateBridge __Hotfix0__ExecuteUiOperationItem; // 0x20
	private static DelegateBridge __Hotfix0__ExecuteHeader; // 0x28
	private static DelegateBridge __Hotfix0__ExecuteEnd; // 0x30
	private static DelegateBridge __Hotfix1__UpdateBag; // 0x38
	private static DelegateBridge __Hotfix0_OnBagBtnClicked; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x1d2ad9c VA: 0x7594342d9c
	public Dictionary`2 GetExecutors() { }
	// RVA: 0x1d2af9c VA: 0x7594342f9c
	private Void _InitIfNot() { }
	// RVA: 0x1d2b188 VA: 0x7594343188
	private Boolean _ExecuteUIOperation(Command command) { }
	// RVA: 0x1d2b21c VA: 0x759434321c
	private Void _UpdateBag(Command command) { }
	// RVA: 0x1d2b354 VA: 0x7594343354
	private Void _ExecuteUiOperationItem(Command command) { }
	// RVA: 0x1d2b6b0 VA: 0x75943436b0
	private Boolean _ExecuteHeader(Command command) { }
	// RVA: 0x1d2b788 VA: 0x7594343788
	private Boolean _ExecuteEnd(Command command) { }
	// RVA: 0x1d2b5a4 VA: 0x75943435a4
	private Void _UpdateBag(Boolean enable) { }
	// RVA: 0x1d2b87c VA: 0x759434387c
	public Void OnBagBtnClicked() { }
	// RVA: 0x1d2b9e4 VA: 0x75943439e4
	public Void .ctor() { }
}
```