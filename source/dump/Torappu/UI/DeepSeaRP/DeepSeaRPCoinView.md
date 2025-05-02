# DeepSeaRPCoinView

**Namespace:** `Torappu.UI.DeepSeaRP`


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
// Namespace : Torappu.UI.DeepSeaRP
public class DeepSeaRPCoinView : MonoBehaviour, IPlayerDataListener, IHotfixable
{
	private Text _textCoin; // 0x18
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_CheckIfDataChanged; // 0x8
	private static DelegateBridge __Hotfix0_OnPlayerDataChanged; // 0x10
	private static DelegateBridge __Hotfix0_get_activityId; // 0x18
	private static DelegateBridge __Hotfix0__TryUpdateCoin; // 0x20
	private static DelegateBridge __Hotfix0_OnEnable; // 0x28
	private static DelegateBridge __Hotfix0_OnDisable; // 0x30
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public static String activityId { get; }

	// RVA: 0x29c7188 VA: 0x7594fdf188
	public Void Init() { }
	// RVA: 0x29c730c VA: 0x7594fdf30c
	public Boolean CheckIfDataChanged(PlayerDataModel prevData, PlayerDataModel curData, PlayerDataDelta delta) { }
	// RVA: 0x29c753c VA: 0x7594fdf53c
	public Void OnPlayerDataChanged() { }
	// RVA: 0x29c7450 VA: 0x7594fdf450
	public static String get_activityId() { }
	// RVA: 0x29c71f0 VA: 0x7594fdf1f0
	private Void _TryUpdateCoin() { }
	// RVA: 0x29c75a4 VA: 0x7594fdf5a4
	private Void OnEnable() { }
	// RVA: 0x29c7610 VA: 0x7594fdf610
	private Void OnDisable() { }
	// RVA: 0x29c767c VA: 0x7594fdf67c
	private Void OnDestroy() { }
	// RVA: 0x29c76e8 VA: 0x7594fdf6e8
	public Void .ctor() { }
}
```