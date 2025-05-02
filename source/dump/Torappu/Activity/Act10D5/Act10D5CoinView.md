# Act10D5CoinView

**Namespace:** `Torappu.Activity.Act10D5`


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
// Namespace : Torappu.Activity.Act10D5
public class Act10D5CoinView : MonoBehaviour, IPlayerDataListener, IHotfixable
{
	private Text _textCoin; // 0x18
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_CheckIfDataChanged; // 0x8
	private static DelegateBridge __Hotfix0_OnPlayerDataChanged; // 0x10
	private static DelegateBridge __Hotfix0__TryUpdateCoin; // 0x18
	private static DelegateBridge __Hotfix0__GetMiniStoryAct; // 0x20
	private static DelegateBridge __Hotfix0_OnEnable; // 0x28
	private static DelegateBridge __Hotfix0_OnDisable; // 0x30
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x34856b0 VA: 0x7595a9d6b0
	public Void Init() { }
	// RVA: 0x34857c4 VA: 0x7595a9d7c4
	public Boolean CheckIfDataChanged(PlayerDataModel prevData, PlayerDataModel curData, PlayerDataDelta delta) { }
	// RVA: 0x3485980 VA: 0x7595a9d980
	public Void OnPlayerDataChanged() { }
	// RVA: 0x3485718 VA: 0x7595a9d718
	private Void _TryUpdateCoin() { }
	// RVA: 0x34858a0 VA: 0x7595a9d8a0
	private static PlayerMiniStoryActivity _GetMiniStoryAct(String actId, PlayerDataModel data) { }
	// RVA: 0x34859e8 VA: 0x7595a9d9e8
	private Void OnEnable() { }
	// RVA: 0x3485a54 VA: 0x7595a9da54
	private Void OnDisable() { }
	// RVA: 0x3485ac0 VA: 0x7595a9dac0
	private Void OnDestroy() { }
	// RVA: 0x3485b2c VA: 0x7595a9db2c
	public Void .ctor() { }
}
```