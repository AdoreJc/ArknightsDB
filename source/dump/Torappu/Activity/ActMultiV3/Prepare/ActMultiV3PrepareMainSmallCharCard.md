# ActMultiV3PrepareMainSmallCharCard

**Namespace:** `Torappu.Activity.ActMultiV3.Prepare`


## Fields

- `ActMultiV3CharCardBase _cardPrefab`

- `Transform _container`

- `UIColorGraphic _btnGraphic`

- `GameObject _teampTag`

- `ActMultiV3CharCardBase m_card`

- `ActMultiV3PrepareMainSmallCharCardModel m_cachedModel`

- `Boolean <enableTempTag>k__BackingField`

- `Boolean <tempTagValid>k__BackingField`


## Properties

- `Boolean enableTempTag`

- `Boolean enableClick`

- `Boolean tempTagValid`


## Methods

- `Boolean get_enableTempTag()`

- `Void set_enableTempTag(Boolean)`

- `Void set_enableClick(Boolean)`

- `Void set_onClick(Action`1)`

- `Boolean get_tempTagValid()`

- `Void set_tempTagValid(Boolean)`

- `Void RenderCard(ActMultiV3PrepareMainSmallCharCardModel)`

- `Void _InitIfNot()`

- `Void EventOnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3.Prepare
public class ActMultiV3PrepareMainSmallCharCard : MonoBehaviour, IHotfixable
{
	private ActMultiV3CharCardBase _cardPrefab; // 0x18
	private Transform _container; // 0x20
	private UIColorGraphic _btnGraphic; // 0x28
	private GameObject _teampTag; // 0x30
	private ActMultiV3CharCardBase m_card; // 0x38
	private Action`1 m_clickListener; // 0x40
	private ActMultiV3PrepareMainSmallCharCardModel m_cachedModel; // 0x48
	private Boolean <enableTempTag>k__BackingField; // 0x50
	private Boolean <tempTagValid>k__BackingField; // 0x51
	private static DelegateBridge __Hotfix0_get_enableTempTag; // 0x0
	private static DelegateBridge __Hotfix0_set_enableTempTag; // 0x8
	private static DelegateBridge __Hotfix0_set_enableClick; // 0x10
	private static DelegateBridge __Hotfix0_set_onClick; // 0x18
	private static DelegateBridge __Hotfix0_get_tempTagValid; // 0x20
	private static DelegateBridge __Hotfix0_set_tempTagValid; // 0x28
	private static DelegateBridge __Hotfix0_RenderCard; // 0x30
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x38
	private static DelegateBridge __Hotfix0_EventOnClick; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public Boolean enableTempTag { get; set; }
	public Boolean enableClick { set; }
	public Action`1 onClick { set; }
	public Boolean tempTagValid { get; set; }

	// RVA: 0x31621ec VA: 0x759577a1ec
	public Boolean get_enableTempTag() { }
	// RVA: 0x3162254 VA: 0x759577a254
	public Void set_enableTempTag(Boolean value) { }
	// RVA: 0x31622d4 VA: 0x759577a2d4
	public Void set_enableClick(Boolean value) { }
	// RVA: 0x3162358 VA: 0x759577a358
	public Void set_onClick(Action`1 value) { }
	// RVA: 0x31623dc VA: 0x759577a3dc
	public Boolean get_tempTagValid() { }
	// RVA: 0x3162444 VA: 0x759577a444
	public Void set_tempTagValid(Boolean value) { }
	// RVA: 0x31624c4 VA: 0x759577a4c4
	public Void RenderCard(ActMultiV3PrepareMainSmallCharCardModel model) { }
	// RVA: 0x31625b0 VA: 0x759577a5b0
	private Void _InitIfNot() { }
	// RVA: 0x31627b0 VA: 0x759577a7b0
	public Void EventOnClick() { }
	// RVA: 0x31628c0 VA: 0x759577a8c0
	public Void .ctor() { }
}
```