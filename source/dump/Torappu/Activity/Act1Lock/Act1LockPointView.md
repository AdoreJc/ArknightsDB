# Act1LockPointView

**Namespace:** `Torappu.Activity.Act1Lock`


## Fields

- `Text _textPoint`


## Methods

- `Void Init()`

- `Boolean CheckIfDataChanged(PlayerDataModel, PlayerDataModel, PlayerDataDelta)`

- `Void OnPlayerDataChanged()`

- `Void _TryUpdatePoints()`

- `Void OnEnable()`

- `Void OnDisable()`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Lock
public class Act1LockPointView : MonoBehaviour, IPlayerDataListener, IHotfixable
{
	private Text _textPoint; // 0x18
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_CheckIfDataChanged; // 0x8
	private static DelegateBridge __Hotfix0_OnPlayerDataChanged; // 0x10
	private static DelegateBridge __Hotfix0__TryUpdatePoints; // 0x18
	private static DelegateBridge __Hotfix0_OnEnable; // 0x20
	private static DelegateBridge __Hotfix0_OnDisable; // 0x28
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x3399b74 VA: 0x75959b1b74
	public Void Init() { }
	// RVA: 0x3399cf8 VA: 0x75959b1cf8
	public Boolean CheckIfDataChanged(PlayerDataModel prevData, PlayerDataModel curData, PlayerDataDelta delta) { }
	// RVA: 0x3399e3c VA: 0x75959b1e3c
	public Void OnPlayerDataChanged() { }
	// RVA: 0x3399bdc VA: 0x75959b1bdc
	private Void _TryUpdatePoints() { }
	// RVA: 0x3399ea4 VA: 0x75959b1ea4
	private Void OnEnable() { }
	// RVA: 0x3399f10 VA: 0x75959b1f10
	private Void OnDisable() { }
	// RVA: 0x3399f7c VA: 0x75959b1f7c
	private Void OnDestroy() { }
	// RVA: 0x3399fe8 VA: 0x75959b1fe8
	public Void .ctor() { }
}
```