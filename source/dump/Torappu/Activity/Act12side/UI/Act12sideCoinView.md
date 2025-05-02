# Act12sideCoinView

**Namespace:** `Torappu.Activity.Act12side.UI`


## Fields

- `String m_actId`


## Methods

- `Void Init(String)`

- `Boolean CheckIfDataChanged(PlayerDataModel, PlayerDataModel, PlayerDataDelta)`

- `Void OnPlayerDataChanged()`

- `Void _TryUpdateCoin()`

- `Void OnEnable()`

- `Void OnDisable()`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12side.UI
public class Act12sideCoinView : MonoBehaviour, IHotfixable, IPlayerDataListener
{
	private Text[] _coinTextList; // 0x18
	private String m_actId; // 0x20
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_CheckIfDataChanged; // 0x8
	private static DelegateBridge __Hotfix0_OnPlayerDataChanged; // 0x10
	private static DelegateBridge __Hotfix0__TryUpdateCoin; // 0x18
	private static DelegateBridge __Hotfix0_OnEnable; // 0x20
	private static DelegateBridge __Hotfix0_OnDisable; // 0x28
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x3461c4c VA: 0x7595a79c4c
	public Void Init(String actId) { }
	// RVA: 0x3461e54 VA: 0x7595a79e54
	public Boolean CheckIfDataChanged(PlayerDataModel prevData, PlayerDataModel curData, PlayerDataDelta delta) { }
	// RVA: 0x3461f94 VA: 0x7595a79f94
	public Void OnPlayerDataChanged() { }
	// RVA: 0x3461cd8 VA: 0x7595a79cd8
	private Void _TryUpdateCoin() { }
	// RVA: 0x3461ffc VA: 0x7595a79ffc
	private Void OnEnable() { }
	// RVA: 0x3462068 VA: 0x7595a7a068
	private Void OnDisable() { }
	// RVA: 0x34620d4 VA: 0x7595a7a0d4
	private Void OnDestroy() { }
	// RVA: 0x3462140 VA: 0x7595a7a140
	public Void .ctor() { }
}
```