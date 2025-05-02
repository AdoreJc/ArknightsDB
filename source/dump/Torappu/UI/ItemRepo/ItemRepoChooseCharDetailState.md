# ItemRepoChooseCharDetailState

**Namespace:** `Torappu.UI.ItemRepo`


## Fields

- `ItemRepoChooseCharDetailStateBean m_stateBean`

- `Image _professionImg`

- `Text _charName`

- `Text _charTopName`

- `Image _charRarity`

- `UIAtlasImage _portrait`

- `Text _descText`

- `Text _usageText`

- `Text _ensureText`


## Methods

- `Void OpenCharacterShow()`

- `Void SendBuy()`

- `Void <SendBuy>b__13_0(VoucherGachaDetailResponse)`

- `Void <SendBuy>b__13_1()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ItemRepo
public class ItemRepoChooseCharDetailState : PopupFloatState
{
	private ItemRepoChooseCharDetailStateBean m_stateBean; // 0x70
	private Image _professionImg; // 0x78
	private Text _charName; // 0x80
	private Text _charTopName; // 0x88
	private Image _charRarity; // 0x90
	private UIAtlasImage _portrait; // 0x98
	private Text _descText; // 0xa0
	private Text _usageText; // 0xa8
	private Text _ensureText; // 0xb0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OpenCharacterShow; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_ShowGacha; // 0x18
	private static DelegateBridge __Hotfix0_SendBuy; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2d31c24 VA: 0x7595349c24
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2d31c8c VA: 0x7595349c8c
	public Void OpenCharacterShow() { }
	// RVA: 0x2d31d88 VA: 0x7595349d88
	protected override Void OnEnter() { }
	// RVA: 0x2d3230c VA: 0x759534a30c
	public static Void ShowGacha(GameObject thisObj, List`1 items, Action onConfirmed) { }
	// RVA: 0x2d327f8 VA: 0x759534a7f8
	public Void SendBuy() { }
	// RVA: 0x2d32a58 VA: 0x759534aa58
	public Void .ctor() { }
	// RVA: 0x2d32b04 VA: 0x759534ab04
	private Void <SendBuy>b__13_0(VoucherGachaDetailResponse response) { }
	// RVA: 0x2d32bac VA: 0x759534abac
	private Void <SendBuy>b__13_1() { }
	// RVA: 0x2d32c7c VA: 0x759534ac7c
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```