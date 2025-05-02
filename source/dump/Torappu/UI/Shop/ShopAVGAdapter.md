# ShopAVGAdapter

**Namespace:** `Torappu.UI.Shop`


## Fields

- `ShopStateItemContainer _container`

- `String m_waitForSignal`


## Methods

- `Boolean _ExecuteSwitchShopTopTab(Command)`

- `Void _ReceiveSwitchShopTopTabSignal(Command)`

- `Void Start()`

- `Void OnDestroy()`

- `Void <>xLuaBaseProxy_OnReset()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopAVGAdapter : ExecutorComponent
{
	private ShopStateItemContainer _container; // 0x50
	private String m_waitForSignal; // 0x58
	private static DelegateBridge __Hotfix0_GetExecutors; // 0x0
	private static DelegateBridge __Hotfix0_GetSignalReceivers; // 0x8
	private static DelegateBridge __Hotfix0_OnReset; // 0x10
	private static DelegateBridge __Hotfix0_ForceCommandEnd; // 0x18
	private static DelegateBridge __Hotfix0__ExecuteSwitchShopTopTab; // 0x20
	private static DelegateBridge __Hotfix0__ReceiveSwitchShopTopTabSignal; // 0x28
	private static DelegateBridge __Hotfix0_Start; // 0x30
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x24616b4 VA: 0x7594a796b4
	public override Dictionary`2 GetExecutors() { }
	// RVA: 0x2461854 VA: 0x7594a79854
	public override Dictionary`2 GetSignalReceivers() { }
	// RVA: 0x2461990 VA: 0x7594a79990
	public override Void OnReset() { }
	// RVA: 0x2461a00 VA: 0x7594a79a00
	protected override Void ForceCommandEnd() { }
	// RVA: 0x2461a88 VA: 0x7594a79a88
	private Boolean _ExecuteSwitchShopTopTab(Command command) { }
	// RVA: 0x2461cc8 VA: 0x7594a79cc8
	private Void _ReceiveSwitchShopTopTabSignal(Command command) { }
	// RVA: 0x2461de0 VA: 0x7594a79de0
	private Void Start() { }
	// RVA: 0x2461e9c VA: 0x7594a79e9c
	private Void OnDestroy() { }
	// RVA: 0x2461f58 VA: 0x7594a79f58
	public Void .ctor() { }
	// RVA: 0x2461fc8 VA: 0x7594a79fc8
	private Dictionary`2 <>xLuaBaseProxy_GetSignalReceivers() { }
	// RVA: 0x2461fd0 VA: 0x7594a79fd0
	private Void <>xLuaBaseProxy_OnReset() { }
}
```