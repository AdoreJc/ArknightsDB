# Act9D0CoinView

**Namespace:** `Torappu.Activity.Act9D0`


## Fields

- `Text _textCoin`


## Methods

- `Void Init()`

- `Boolean CheckIfDataChanged(PlayerDataModel, PlayerDataModel, PlayerDataDelta)`

- `Void OnPlayerDataChanged()`

- `Void _TryUpdateCoin()`

- `Void OnEnable()`

- `Void OnDisable()`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act9D0
public class Act9D0CoinView : MonoBehaviour, IPlayerDataListener, IHotfixable
{
	private Text _textCoin; // 0x18
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_CheckIfDataChanged; // 0x8
	private static DelegateBridge __Hotfix0_OnPlayerDataChanged; // 0x10
	private static DelegateBridge __Hotfix0__TryUpdateCoin; // 0x18
	private static DelegateBridge __Hotfix0_OnEnable; // 0x20
	private static DelegateBridge __Hotfix0_OnDisable; // 0x28
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x319cdcc VA: 0x75957b4dcc
	public Void Init() { }
	// RVA: 0x31a318c VA: 0x75957bb18c
	public Boolean CheckIfDataChanged(PlayerDataModel prevData, PlayerDataModel curData, PlayerDataDelta delta) { }
	// RVA: 0x31a32d0 VA: 0x75957bb2d0
	public Void OnPlayerDataChanged() { }
	// RVA: 0x31a3070 VA: 0x75957bb070
	private Void _TryUpdateCoin() { }
	// RVA: 0x31a3338 VA: 0x75957bb338
	private Void OnEnable() { }
	// RVA: 0x31a33a4 VA: 0x75957bb3a4
	private Void OnDisable() { }
	// RVA: 0x31a3410 VA: 0x75957bb410
	private Void OnDestroy() { }
	// RVA: 0x31a347c VA: 0x75957bb47c
	public Void .ctor() { }
}
```