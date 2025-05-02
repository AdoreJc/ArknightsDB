# Act12D6CoinView

**Namespace:** `Torappu.Activity.Act12D6`


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
// Namespace : Torappu.Activity.Act12D6
public class Act12D6CoinView : MonoBehaviour, IPlayerDataListener, IHotfixable
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


	// RVA: 0x34723d0 VA: 0x7595a8a3d0
	public Void Init() { }
	// RVA: 0x347257c VA: 0x7595a8a57c
	public Boolean CheckIfDataChanged(PlayerDataModel prevData, PlayerDataModel curData, PlayerDataDelta delta) { }
	// RVA: 0x34726e8 VA: 0x7595a8a6e8
	public Void OnPlayerDataChanged() { }
	// RVA: 0x3472438 VA: 0x7595a8a438
	private Void _TryUpdateCoin() { }
	// RVA: 0x3472750 VA: 0x7595a8a750
	private Void OnEnable() { }
	// RVA: 0x34727bc VA: 0x7595a8a7bc
	private Void OnDisable() { }
	// RVA: 0x3472828 VA: 0x7595a8a828
	private Void OnDestroy() { }
	// RVA: 0x3472894 VA: 0x7595a8a894
	public Void .ctor() { }
}
```