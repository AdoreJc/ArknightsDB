# TemplateShopResourceBar

**Namespace:** `Torappu.UI.TemplateShop`


## Fields

- `Text _shopCoinCount`

- `Image _shopCoinIcon`

- `Image _shopBarImage`

- `String m_cacheShopId`


## Methods

- `Void InitAndBind(String)`

- `Boolean CheckIfDataChanged(PlayerDataModel, PlayerDataModel, PlayerDataDelta)`

- `Void OnPlayerDataChanged()`

- `Void _TryUpdateCoinCount()`

- `Void OnEnable()`

- `Void OnDisable()`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateShop
public class TemplateShopResourceBar : MonoBehaviour, IPlayerDataListener, IHotfixable
{
	public Text _shopCoinCount; // 0x18
	public Image _shopCoinIcon; // 0x20
	public Image _shopBarImage; // 0x28
	private String m_cacheShopId; // 0x30
	private static DelegateBridge __Hotfix0_InitAndBind; // 0x0
	private static DelegateBridge __Hotfix0_CheckIfDataChanged; // 0x8
	private static DelegateBridge __Hotfix0_OnPlayerDataChanged; // 0x10
	private static DelegateBridge __Hotfix0__TryUpdateCoinCount; // 0x18
	private static DelegateBridge __Hotfix0_OnEnable; // 0x20
	private static DelegateBridge __Hotfix0_OnDisable; // 0x28
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x2358620 VA: 0x7594970620
	public Void InitAndBind(String shopId) { }
	// RVA: 0x235ff40 VA: 0x7594977f40
	public Boolean CheckIfDataChanged(PlayerDataModel prevData, PlayerDataModel curData, PlayerDataDelta delta) { }
	// RVA: 0x23600a4 VA: 0x75949780a4
	public Void OnPlayerDataChanged() { }
	// RVA: 0x235fdf8 VA: 0x7594977df8
	private Void _TryUpdateCoinCount() { }
	// RVA: 0x236010c VA: 0x759497810c
	private Void OnEnable() { }
	// RVA: 0x2360178 VA: 0x7594978178
	private Void OnDisable() { }
	// RVA: 0x23601e4 VA: 0x75949781e4
	private Void OnDestroy() { }
	// RVA: 0x2360250 VA: 0x7594978250
	public Void .ctor() { }
}
```