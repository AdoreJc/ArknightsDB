# CrisisResourceBar

**Namespace:** `Torappu.UI.Crisis`


## Fields

- `GameObject _shopCoinResourceBar`

- `GameObject _unlockCoinResourceBar`

- `Text _shopCoinCount`

- `Text _unlockCoinCount`


## Methods

- `Void InitAndBind(Option)`

- `Boolean CheckIfDataChanged(PlayerDataModel, PlayerDataModel, PlayerDataDelta)`

- `Void OnPlayerDataChanged()`

- `Void UnBind()`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Crisis
public class CrisisResourceBar : MonoBehaviour, IPlayerDataListener, IHotfixable
{
	private GameObject _shopCoinResourceBar; // 0x18
	private GameObject _unlockCoinResourceBar; // 0x20
	private Text _shopCoinCount; // 0x28
	private Text _unlockCoinCount; // 0x30
	private static DelegateBridge __Hotfix0_InitAndBind; // 0x0
	private static DelegateBridge __Hotfix0_CheckIfDataChanged; // 0x8
	private static DelegateBridge __Hotfix0_OnPlayerDataChanged; // 0x10
	private static DelegateBridge __Hotfix0_UnBind; // 0x18
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2c36f54 VA: 0x759524ef54
	public Void InitAndBind(Option option) { }
	// RVA: 0x2c37054 VA: 0x759524f054
	public Boolean CheckIfDataChanged(PlayerDataModel prevData, PlayerDataModel curData, PlayerDataDelta delta) { }
	// RVA: 0x2c37180 VA: 0x759524f180
	public Void OnPlayerDataChanged() { }
	// RVA: 0x2c372b4 VA: 0x759524f2b4
	public Void UnBind() { }
	// RVA: 0x2c37320 VA: 0x759524f320
	private Void OnDestroy() { }
	// RVA: 0x2c3738c VA: 0x759524f38c
	public Void .ctor() { }
}
```